A segurança de rede se relaciona diretamente com a continuidade de negócios de uma organização. As violações de segurança de rede podem interromper o comércio eletrônico, causar a perda de dados comerciais, ameaçar a privacidade das pessoas e comprometer a integridade das informações. Essas violações podem resultar em perda de receita para empresas, roubo de propriedade intelectual, ações judiciais e até ameaçar a segurança pública.

## Vetores de ataques de rede

Um vetor de ataque é um caminho pelo qual um atacante poder obter acesso a um servidor, equipamento ou rede. Os vetores de ataque são originários de dentro ou de fora da rede corporativa.

## Superfície de ataque

Uma superfície de ataque é a soma total das vulnerabilidades em um sistema que pode ser acessado por um invasor. A superfície de ataque pode consistir em portas abertas em servidores ou hosts, software executado em servidores voltados para a Internet, protocolos de rede sem fio e até mesmo usuários.

## Nuvem e virtualização

A nuvem está desempenhando um papel cada vez maior nas redes corporativas. A computação em nuvem permite que as organizações usem serviços como armazenamento de dados ou aplicativos baseados em nuvem, para estender sua capacidade ou recursos sem adicionar infraestrutura. Por sua própria natureza, a nuvem está fora do perímetro de rede tradicional, permitindo que uma organização tenha um data center que pode ou não residir atrás do firewall tradicional.

- **Hiperjacking** - Um invasor pode seqüestrar um hipervisor VM (software de controle de VM) e usá-lo como um ponto de lançamento para atacar outros dispositivos na rede do data center.
- **Ativação instantânea** - Quando uma VM que não foi usada por um período de tempo é colocada on-line, ela pode ter políticas de segurança desatualizadas que se desviam da segurança da linha de base e podem introduzir vulnerabilidades de segurança.
- **Tempestades de antivírus** - Isso acontece quando todas as VMs tentam baixar arquivos de dados antivírus ao mesmo tempo.

# Ameaças à Rede

**Exploit** - O mecanismo que é usado para alavancar uma vulnerabilidade para comprometer um ativo. As explorações podem ser remotas ou locais. Uma **exploração remota** é aquela que funciona através da rede sem qualquer acesso prévio ao sistema de destino. O invasor não precisa de uma conta no sistema final para explorar a vulnerabilidade. Em uma **exploração local**, o ator de ameaça tem algum tipo de acesso administrativo ou de usuário ao sistema final. Uma exploração local não significa necessariamente que o invasor tenha acesso físico ao sistema final.

> **uma exploração local requer acesso interno à rede, como um usuário com uma conta na rede. Uma exploração remota não requer uma conta na rede para explorar a vulnerabilidade dessa rede.**

## Ferramentas de Teste de Penetração de Rede

*a lista não é exaustiva, pois novas ferramentas são continuamente desenvolvidas.*

Categorias de Ferramentas | Descrição
---- | ----
crackers da senha | As senhas são a ameaça de segurança mais vulnerável. As ferramentas de quebra de senha são freqüentemente chamadas de ferramentas de recuperação de senha e podem ser usadas para quebrar ou recuperar a senha. Isso é feito removendo a senha original, depois de ignorar a criptografia de dados, ou pela descoberta direta da senha. Os crackers de senhas repetidamente fazem suposições para decifrar a senha e acessar o sistema. Exemplos de ferramentas de quebra de senha incluem John the Ripper, Ophcrack, L0phtCrack, THC Hydra, RainbowCrack e Medusa.
ferramentas de hacking sem fio | As redes sem fio são mais suscetíveis a ameaças à segurança da rede. As ferramentas de hackers sem fio são usadas para invadir intencionalmente uma rede sem fio para detectar vulnerabilidades de segurança. Exemplos de ferramentas de hacking sem fio incluem Aircrack-ng, Kismet, InSSIDer, KisMAC, Firesheep e NetStumbler.
digitalização de rede e ferramentas de hacking | As ferramentas de verificação de rede são usadas para investigar dispositivos, servidores e hosts de rede em busca de portas TCP ou UDP abertas. Exemplos de ferramentas de digitalização incluem Nmap, SuperScan, Angry IP Scanner e NetScanTools.
ferramentas de elaboração de pacotes | Ferramentas de criação de pacotes são usadas para sondar e testar a robustez de um firewall usando pacotes forjados especialmente criados. Exemplos de tais ferramentas incluem Hping, Scapy, Socat, Yersinia, Netcat, Nping e Nemesis.
sniffer de pacotes | As ferramentas de farejadores de pacotes são usadas para capturar e analisar pacotes em LANs Ethernet ou WLANs tradicionais. As ferramentas incluem Wireshark, Tcpdump, Ettercap, Dsniff, EtherApe, Paros, Fiddler, Ratproxy e SSLstrip.
detectores de rootkit | Um detector de rootkit é um verificador de integridade de diretório e arquivo usado por white hats para detectar root kits instalados. Exemplos de ferramentas incluem AIDE, Netfilter e PF: OpenBSD Packet Filter.
fuzzers para pesquisar vulnerabilidades | Fuzzers são ferramentas usadas por agentes de ameaças ao tentar descobrir vulnerabilidades de segurança de um sistema de computador. Exemplos de difusores incluem Skipfish, Wapiti e W3af.
ferramentas forenses | Hackers White hat usam ferramentas forenses para farejar qualquer vestígio de evidência existente em um sistema de computador específico. Exemplos de ferramentas incluem Sleuth Kit, Helix, Maltego e Encase.
depuradores | Ferramentas de depuração são usadas por Black Hats para fazer engenharia reversa de arquivos binários ao escrever exploits. Eles também são usados por white hats ao analisar malware. As ferramentas de depuração incluem GDB, WinDbg, IDA Pro, and Immunity Debugger.
hackeando sistemas operacionais | Os sistemas operacionais de hacking são sistemas operacionais especialmente projetados, pré-carregados com ferramentas e tecnologias otimizadas para hackers. Exemplos de sistemas operacionais de hacking especialmente projetados incluem Kali Linux, SELinux, Knoppix, Parrot OS e BackBox Linux.
ferramentas de criptografia | Essas ferramentas salvaguardam o conteúdo dos dados de uma organização quando são armazenados ou transmitidos. As ferramentas de criptografia usam esquemas de algoritmo para codificar os dados e evitar o acesso não autorizado aos dados. Exemplos dessas ferramentas incluem VeraCrypt, CipherShed, Open SSH, OpenSSL, OpenVPN e Stunnel.
ferramentas de exploração de vulnerabilidade | Essas ferramentas identificam se um host remoto é vulnerável a um ataque de segurança. Exemplos de ferramentas de exploração de vulnerabilidade incluem Metasploit, Core Impact, Sqlmap, Social Engineer Tool Kit e Netsparker.
scanner de vulnerabilidades | Essas ferramentas examinam uma rede ou sistema para identificar portas abertas. Eles também podem ser usados para verificar vulnerabilidades conhecidas e verificar VMs, dispositivos BYOD e bancos de dados do cliente Exemplos dessas ferramentas incluem Nipper, Securia PSI, Core Impact, Nessus, SAINT e Open VAS.

## Categorias de ataques

*a lista de ataques não é exaustiva, pois novas maneiras de atacar redes são continuamente descobertas.*

|**Categoria de Ataque**|**Descrição**|
|---|---|
|Ataque de escuta|Um ataque de espionagem ocorre quando um agente de ameaça captura e escuta o tráfego da rede. Esse ataque também é chamado de sniffing ou snooping.|
|Ataque de modificação de dados|Ataques de modificação de dados ocorrem quando um agente de ameaça capturou o tráfego da empresa e alterou os dados nos pacotes sem o conhecimento do remetente ou receptor.|
|Ataque de Falsificação de Endereços IP|Um ataque de falsificação de endereço IP ocorre quando um ator de ameaça constrói um pacote IP que parece se originar de um endereço válido dentro da intranet corporativa.|
|Ataques baseados em senha|Ataques baseados em senha ocorrem quando um ator de ameaça obtém as credenciais de uma conta de usuário válida. Em seguida, os atores de ameaças usam essa conta para obter listas de outros usuários e informações de rede. Eles também podem alterar as configurações de servidor e rede e modificar, redirecionar ou excluir dados.|
|Ataque de negação de serviço (DoS)|Um ataque de DoS impede o uso normal de um computador ou rede por usuários válidos. Depois de obter acesso a uma rede, um ataque DoS pode travar aplicativos ou serviços de rede. Um ataque de DoS pode inundar um computador ou toda a rede com tráfego até que um desligamento ocorra devido à sobrecarga. Um ataque de DoS também pode bloquear o tráfego, o que resulta na perda de acesso aos recursos da rede por usuários autorizados.|
|Ataque man-in-the-middle (MiTM)|Um ataque MiTM ocorre quando os agentes da ameaça se posicionam entre a origem e o destino. Agora eles podem monitorar, capturar e controlar ativamente a comunicação de forma transparente.|
|Ataque de chave comprometida|Um ataque de chave comprometida ocorre quando um ator de ameaça obtém uma chave secreta. Isto é referido como uma chave comprometida. Uma chave comprometida pode ser usada para obter acesso a uma comunicação segura sem que o remetente ou o destinatário esteja ciente do ataque.|
|Ataque Sniffer|Um sniffer é um aplicativo ou dispositivo que pode ler, monitorar e capturar trocas de dados de rede e ler pacotes de rede. Se os pacotes não estiverem criptografados, um sniffer fornece uma visão completa dos dados dentro do pacote. Até mesmo pacotes encapsulados podem ser quebrados abertos e lidos, a menos que sejam criptografados e que o ator de ameaça não tenha acesso à chave.|

# Mitigação de Ameaças

## Políticas de Negócios

Políticas de negócios são as diretrizes que são desenvolvidas por uma organização para governar suas ações. As políticas definem padrões de comportamento correto para a empresa e seus funcionários. Na rede, as políticas definem as atividades permitidas na rede.

Uma organização deve ter diretivas orientadoras, conforme abaixo:

- Políticas da empresa;
- Políticas de funcionários;
- **Políticas de segurança** 

**Políticas de Segurança**

As políticas de segurança são usadas para informar os usuários, funcionários e gerentes sobre os requisitos de uma organização para proteger os ativos de tecnologia e informação. Uma política de segurança também especifica os mecanismos necessários para atender aos requisitos de segurança e fornece uma linha de base a partir da qual adquirir, configurar e auditar sistemas e redes de computadores para conformidade.

- Essas políticas identificam um conjunto de objetivos de segurança para uma empresa, definem as regras de comportamento para usuários e administradores e especificam os requisitos do sistema.
- Esses objetivos, regras e requisitos garantem coletivamente a segurança de uma rede e dos sistemas de computador em uma organização.
- Assim como um plano de continuidade, uma política de segurança é um documento em constante evolução com base em mudanças no cenário de ameaças, vulnerabilidades e requisitos de negócios e funcionários.

A tabela lista as diretivas que podem ser incluídas em uma diretiva de segurança.

|**Política**|**Descrição**|
|---|---|
|**Política de identificação e autenticação**|Especifica pessoas autorizadas que podem ter acesso a recursos de rede e procedimentos de verificação de identidade.|
|**Políticas de senha**|Garante que as senhas atendam aos requisitos mínimos e sejam alteradas regularmente.|
|**Acceptable Use Policy (AUP)**|Identifica os aplicativos e usos de rede que são aceitáveis para a organização. Também podem identificar as ramificações, se esta política for violada.|
|**Política de acesso remoto**|Identifica como os usuários remotos podem acessar uma rede e o que é acessível por meio de conectividade remota.|
|**Políticas de Manutenção de Rede**|Especifica procedimentos de atualização de sistemas operacionais dos dispositivos de rede e de aplicativos de usuário final.|
|**Procedimentos de tratamento de incidentes**|Descreve como os incidentes de segurança são tratados.|

## Mitigando Ataques de Reconhecimento

Os ataques de reconhecimento são tipicamente o precursor de outros ataques que têm a intenção de obter acesso não autorizado a uma rede ou interromper a funcionalidade da rede. Um profissional de segurança de rede pode detectar quando um ataque de reconhecimento está em andamento recebendo notificações de alarmes pré-configurados.

Os ataques de reconhecimento podem ser mitigados de várias maneiras, incluindo o seguinte:

- Implementando a autenticação para garantir o acesso adequado.
- Usando criptografia para tornar os ataques de sniffer de pacotes inúteis.
- Usando ferramentas anti-sniffer para detectar ataques de sniffer de pacotes.
- Implementando uma infraestrutura comutada.
- Usando um firewall e IPS.

É impossível impedir a varredura de portas, mas usar um sistema de prevenção de intrusões (IPS) e firewall pode limitar as informações que podem ser descobertas com um scanner de porta. As varreduras de ping podem ser paradas se o eco ICMP e a resposta de eco estiverem desligados nos roteadores de borda; contudo, quando esses serviços são desligados, os dados de diagnóstico de rede são perdidos.

## Tópicos importantes

Tópico 3.4.0 - O software antivírus é o principal meio de mitigar ataques de vírus e cavalos de Tróia. Ao usar um software antivírus, a propagação de vírus e ataques de cavalo de Tróia pode ser reduzida.

Tópico 3.5.0\ - Controle o tráfego plano, como mensagens ARP ou propagandas de protocolo de roteamento são gerados por um dispositivo de rede a fim apoiar operações de rede. A autenticação de protocolo de roteamento fornece uma medida extra de segurança para autenticar a origem das atualizações de roteamento. Criptografar conexões de acesso remoto, utilizando o protocolo NTP, e usando AAA, são todas as medidas implementadas para proteger o tráfego plano de gerenciamento.

Tópico 3.3.0 - O Cisco Talos Group fornece blogs e podcasts sobre tópicos relacionados à segurança de vários especialistas do setor. Esses blogs e podcasts fornecem conselhos, pesquisas e técnicas de mitigação recomendadas.

Tópico 3.2.0 - A seção de política de identificação e autenticação da política de segurança geralmente especifica pessoas autorizadas que podem ter acesso a recursos de rede e procedimentos de verificação de identidade.

Tópico 3.4.0\ - As quatro fases da mitigação de worm são:

- Contenção
- Inoculação
- Quarentena
- Tratamento

A desinfecção de sistemas é realizada na fase de tratamento e envolve encerrar o processo worm, remover arquivos infectados e corrigir vulnerabilidades exploradas pelo worm.

Tópico 3.2.0 - Um ambiente BYOD requer uma organização para acomodar uma variedade de dispositivos e métodos de acesso. Dispositivos pessoais, que não estão sob o controle da empresa, podem ser aceitos e, portanto, segurança é um fator essencial. Os custos de hardware no local serão reduzidos, permitindo que a empresa priorize a disponibilização de ferramentas de colaboração e outros softwares para usuários BYOD.

Tópico 3.5.0\ - Há três áreas funcionais da estrutura do Cisco Network Foundation Protection (NFP):

- Plano de controle: Responsável pelas funções de roteamento. Consiste no tráfego gerado por dispositivos de rede para operar a rede
- Plano de gestão: Responsável pela gestão de dispositivos de rede
- Plano dos dados (encaminhamento): Responsável pela transmissão de dados do usuário

Tópico 3.3.0 - Aircrack-ng, Kismet, InSSIDer, KisMAC, Firesheep e NetStumbler são exemplos de ferramentas usadas para invadir uma rede sem fio.

Tópico 3.1.0 - Uma das principais funções do Instituto SyAdmin, Auditoria, Rede e Segurança (SANS) é a manutenção do sistema de alerta precoce do Internet Storm Center.

Tópico 3.4.0\ - Para mitigar as varreduras de ping, as mensagens de eco e echo\ -reply ICMP podem ser bloqueadas nos roteadores de borda da rede. Isso vem a um custo. Porque o ICMP é usado igualmente para dados diagnósticos da rede, estes dados diagnósticos serão obstruídos também.

# Protegendo o acesso

## Acesso administrativo seguro

A segurança do acesso administrativo é uma tarefa de segurança extremamente importante. Se uma pessoa não autorizada obtiver acesso administrativo a um roteador, essa pessoa poderá alterar parâmetros de roteamento, desabilitar funções de roteamento ou descobrir e obter acesso a outros sistemas dentro da rede.

Várias tarefas importantes estão envolvidas na proteção do acesso administrativo a um dispositivo de infraestrutura:

- **Restringir a acessibilidade do dispositivo** - Limite as portas acessíveis, restrinja os comunicadores permitidos e restrinja os métodos permitidos de acesso.
- **Registro e conta para todos os acessos** - Grave qualquer pessoa que acessa um dispositivo, o que aconteceu durante o acesso e quando o acesso ocorreu para fins de auditoria.
- **Autenticar acesso** - Certifique-se de que o acesso seja concedido somente a usuários, grupos e serviços autenticados. Limite o número de tentativas de login com falha e o tempo permitido entre logins.
- **Autorizar ações** - Restringir as ações e exibições permitidas por qualquer usuário, grupo ou serviço específico.
- **Apresentar notificação legal** - Exibir um aviso legal, que deve ser desenvolvido com consultor jurídico da empresa, para diferentes tipos de acesso ao dispositivo.
- **Garanta a confidencialidade dos dados** - Proteja os dados armazenados localmente e confidenciais de serem visualizados e copiados. Considere a vulnerabilidade dos dados em trânsito em um canal de comunicação para sniffing, sequestro de sessão e ataques de man-in-the-middle (MITM).

## Proteja o roteador de borda

Os roteadores são um alvo principal para ataques porque esses dispositivos atuam como polícia de trânsito, que direcionam o tráfego para dentro, fora de, e entre redes. O roteador de borda é o último roteador entre a rede interna e uma rede não confiável, como a Internet. As três áreas de segurança do roteador que devem ser mantidas são segurança física, segurança do sistema operacional e endurecimento do roteador.

## Configurar SSH

O Telnet simplifica o acesso remoto ao dispositivo, mas não é seguro. Os dados contidos em um pacote Telnet são transmitidos sem criptografia. Por esse motivo, é altamente recomendável ativar o Secure Shell (SSH) em dispositivos para acesso remoto seguro.

## Tópicos importantes

Tópico 4.1.0 - Como a camada de acesso (Network Edge) é o ponto de conexão para os endpoints, ele desempenha um grande papel para garantir que a rede esteja protegida contra ataques maliciosos. Essa proteção inclui certificar-se de que os usuários finais e os endpoints que se conectam à rede são impedidos de acessar serviços para os quais eles não estão autorizados.

Tópico 4.4.0 - O SSH fornece segurança para conexões de gerenciamento remoto em um dispositivo de rede.O SSH faz isso através de criptografia para autenticação de sessão (nome de usuário e senha), bem como para transmissão de dados. O protocolo Telnet envia o nome de usuário e a senha em um texto sem formatação, que pode ser visado para a obtenção do nome de usuário e da senha por meio da captura de dados. A Telnet e o SSH usam o TCP, são compatíveis com os processos de autenticação e estabelecem conexões com os hosts no CLI.

Tópico 4.2.0 - Diretrizes de senha fortes para roteadores Cisco incluem:

- Use um comprimento mínimo de senha de oito ou mais caracteres lembrando que mais tempo é melhor.
- Uma senha não pode começar com um espaço, mas espaços dentro de uma frase secreta é permitida em um roteador Cisco.
- O comando **service password-encryption** Só pode proteger as senhas sendo visualizadas dentro da configuração, não à medida que são enviadas pela rede.

Tópico 4.3.0 - Um banner pode ser usado para criar mensagens mostradas nos dispositivos de rede Cisco. Uma mensagem de banner pode proteger a organização a partir de uma perspectiva legal e deve ser revisada por consultor jurídico antes de ser implantado.

Tópico 4.4.0 - O SSH fornece um login remoto seguro por meio de uma interface virtual. O SSH fornece uma autenticação de senha mais forte do que o Telnet. O SSH também criptografa os dados durante a sessão.

Tópico 4.2.0 - Para evitar que todas as senhas configuradas apareçam em texto simples em arquivos de configuração, um administrador pode executar o **service password-encryption** comando. Este comando criptografa todas as senhas configuradas no arquivo de configuração.

Tópico 4.3.0 - O **login block-for 180 attempts 2 within 30**comando fará comando o dispositivo bloquear a autenticação após 2 tentativas malsucedidas dentro de 30 segundos por uma duração de 180 segundos. Um dispositivo inspecionando o tráfego em um link não tem nada a ver com o roteador. A configuração do roteador não pode impedir o acesso não autorizado à sala de equipamentos. Um verme não tentaria acessar o roteador para se propagar para outra parte da rede.

Tópico 4.1.0 - Das três áreas de segurança do roteador, segurança física, endurecimento do roteador e segurança do sistema operacional, a segurança física envolve localizar o roteador em uma sala segura acessível apenas para pessoal autorizado que pode realizar a recuperação de senha.

Tópico 4.1.0 - Os firewalls são comumente usados na borda da rede para criar uma zona desmilitarizada (DMZ). O DMZ contém servidores que são comumente acessados por usuários externos. Ao tê-los em um DMZ, evita ter servidores dentro da rede corporativa com outros dispositivos corporativos.

Tópico 4.2.0 - O **enable secret** comando protege o acesso ao modo Exec Privilegiado de um roteador ou switch do Cisco.

Tópico 4.1.0 - Ao proteger o acesso administrativo local e remoto a um dispositivo de rede, certifique-se de registrar qualquer pessoa que acesse o dispositivo, as ações tiradas durante o acesso e a data/hora do acesso. Outras boas práticas são limitar o número de portas e métodos de acesso, autenticar o acesso, autorizar ações realizadas por aqueles que acessam o dispositivo, exibem notificação legal e protegem os dados visualizados e/ou copiados. Limite a quantidade de protocolos usados para acesso remoto e considere usar o SSH versão 2 ou HTTPS. Os protocolos de descoberta não são relevantes para o acesso administrativo.

