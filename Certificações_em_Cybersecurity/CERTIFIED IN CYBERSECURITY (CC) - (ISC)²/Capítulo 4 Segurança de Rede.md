
# CERTIFIED IN CYBERSECURITY (CC) - (ISC)²

Tags: #certificação #cybersecurity #ISC² #rede #network #lan #wan #mac #tcp/ip


## Rede (Network)

Uma rede é simplesmente dois ou mais computadores conectados para compartilhar dados, informações ou recursos.

#### Tipos de Redes

Existem dois tipos básicos de redes:

-   **Rede de área local (LAN)** - Uma rede de área local (LAN) é uma rede normalmente abrangendo um único andar ou edifício. Esta é geralmente uma área geográfica limitada.
-   **Rede de longa distância (WAN** ) - Rede de longa distância (WAN) é o termo geralmente atribuído às conexões de longa distância entre redes geograficamente remotas.

#### Dispositivos de Rede

**Hub**
Os hubs são usados ​​para conectar vários dispositivos em uma rede. Eles são menos prováveis ​​de serem vistos em redes comerciais ou corporativas do que em redes domésticas.

**Switch**
Os switches são dispositivos com fio que conhecem os endereços dos dispositivos conectados a eles e direcionam o tráfego para essa porta/dispositivo em vez de retransmitir para todos os dispositivos.

Oferecendo maior eficiência para entrega de tráfego e melhorando a taxa de transferência geral de dados, os switches são mais inteligentes que os hubs.

**Roteador**
Os roteadores são usados ​​para controlar o fluxo de tráfego em redes e geralmente são usados ​​para conectar redes semelhantes e controlar o fluxo de tráfego entre elas. Os roteadores podem ser com ou sem fio e podem conectar vários switches.

**Firewall**
Os firewalls são ferramentas essenciais para gerenciar e controlar o tráfego de rede e proteger a rede. Um firewall é um dispositivo de rede usado para filtrar o tráfego. Os firewalls filtram o tráfego com base em um conjunto definido de regras, também chamadas de filtros ou listas de controle de acesso.

**Servidor**
Um servidor é um computador que fornece informações a outros computadores em uma rede. Os servidores geralmente são protegidos de maneira diferente das estações de trabalho para proteger as informações que eles contêm.

**Endpoints**
Endpoints são as extremidades de um link de comunicação de rede. Uma extremidade geralmente está em um servidor onde reside um recurso e a outra extremidade geralmente é um cliente fazendo uma solicitação para usar um recurso de rede.


#### Endereço do Dispositivo

##### Endereço Media Access Control (MAC)
Cada dispositivo de rede recebe um endereço Media Access Control (MAC). Dois dispositivos não podem ter o mesmo endereço MAC na mesma rede local; caso contrário, ocorre um conflito de endereços.

##### Endereço de Protocolo de Internet (IP)
 Embora os endereços MAC sejam geralmente atribuídos no firmware da interface, os hosts IP associam esse endereço a um endereço lógico exclusivo. Esse endereço IP lógico representa a interface de rede dentro da rede e pode ser útil para manter as comunicações quando um dispositivo físico é trocado por um novo hardware.



## Modelo de Interconexão de Sistemas Abertos (OSI)

O Modelo OSI foi desenvolvido para estabelecer uma maneira comum de descrever a estrutura de comunicação para sistemas de computadores interconectados. O modelo OSI serve como uma estrutura abstrata, ou modelo teórico, de como os protocolos devem funcionar em um mundo ideal, em um hardware ideal. Assim, o modelo OSI tornou-se uma referência conceitual comum usada para entender a comunicação de vários componentes hierárquicos, desde interfaces de software até hardware físico.

O modelo OSI divide as tarefas de rede em sete camadas distintas. Cada camada é responsável por executar tarefas ou operações específicas com o objetivo de suportar a troca de dados (ou seja, comunicação de rede) entre dois computadores. As camadas são referenciadas alternadamente por nome ou número de camada.

#### Encapsulamento (Encapsulation)

Execução de ocultação de dados e ocultação de código durante todas as fases de desenvolvimento de software e uso operacional.



## Transmission Control Protocol/Internet Protocol (TCP/IP)

Modelo de protocolo de interconexão de redes criado pelo IETF, que especifica quatro camadas de funcionalidade: **Camada de enlace** (comunicações físicas), **Camada de Internet** (comunicação rede a rede), **Camada de transporte** (base canais para conexões e troca de dados sem conexão entre hosts), e **Camada de Aplicação**, onde outros protocolos e programas aplicativos do usuário fazem uso de serviços de rede.

Na Camada de Aplicação, os protocolos TCP/IP incluem Telnet, Protocolo de Transferência de Arquivos (FTP), Protocolo Simples de Transporte de Correio (SMTP) e Serviço de Nome de Domínio (DNS) .

O TCP/IP pode ser encontrado em quase todos os sistemas operacionais disponíveis, mas consome uma quantidade significativa de recursos e é relativamente fácil de invadir porque foi projetado para facilidade de uso e não para segurança.



## Internet Protocol (IPv4 and IPv6)

O IP é atualmente implantado e usado em todo o mundo em duas versões principais. O IPv4 fornece um espaço de endereço de 32 bits, que no final da década de 1980 estava esgotado. O IPv6 foi introduzido em dezembro de 1995 e fornece um espaço de endereço de 128 bits junto com vários outros recursos importantes.


## Wi-Fi

A rede sem fio é um método popular de conectar sistemas corporativos e domésticos devido à facilidade de implantação e ao custo relativamente baixo. Ele tornou a rede mais versátil do que nunca. Estações de trabalho e sistemas portáteis não estão mais presos a um cabo, mas podem circular livremente dentro do alcance do sinal dos pontos de acesso sem fio implantados. No entanto, com essa liberdade, surgem vulnerabilidades adicionais.



## Segurança da Rede

As vulnerabilidades do TCP/IP são numerosas. Pilhas TCP/IP implementadas incorretamente em vários sistemas operacionais são vulneráveis ​​a vários ataques DoS/DDoS, ataques de fragmentos, ataques de pacotes superdimensionados, ataques de spoofing e ataques man-in-the-middle .

O TCP/IP (assim como a maioria dos protocolos) também está sujeito a ataques passivos via monitoramento ou detecção. Monitoramento de rede, ou sniffing, é o ato de monitorar padrões de tráfego para obter informações sobre uma rede. 



## Portas e Protocolos (Applications/Services)

#### Portas Físicas

As portas físicas são as portas nos roteadores, switches, servidores, computadores, etc. que você conecta os fios, por exemplo, cabos de fibra ótica, cabos Cat5, etc., para criar uma rede.

#### Portas Lógicas

Uma porta lógica (também chamada de soquete) é pouco mais que um número de endereço que ambas as extremidades do link de comunicação concordam em usar ao transferir dados. As portas permitem que um único endereço IP seja capaz de suportar várias comunicações simultâneas, cada uma usando um número de porta diferente.


Alguns protocolos de rede transmitem informações em texto não criptografado, o que significa que não são criptografadas e não devem ser usadas. Abaixo alguns dos protocolos inseguros juntamente com as alternativas seguras recomendadas.

##### 21 - FTP Protocolo de transferência de arquivos
A porta 21, File Transfer Protocol (FTP) envia o nome de usuário e a senha usando texto sem formatação do cliente para o servidor. Isso pode ser interceptado por um invasor e posteriormente usado para recuperar informações confidenciais do servidor. A alternativa segura, SFTP, na porta 22 usa criptografia para proteger as credenciais do usuário e os pacotes de dados que estão sendo transferidos.

##### 53 - DNS Serviço de nome de domínio
A porta 53, Domain Name Service (DNS), ainda é amplamente utilizada. No entanto, usar DNS sobre TLS (DoT) na porta 853 protege as informações de DNS de serem modificadas em trânsito.

##### 80 - HTTP Protocolo de Transferência de Hipertexto
A porta 80, HyperText Transfer Protocol (HTTP) é a base de quase todo o tráfego do navegador da web na Internet. As informações enviadas via HTTP não são criptografadas e são suscetíveis a ataques de sniffing. HTTPS usando criptografia TLS é o preferido, pois protege os dados em trânsito entre o servidor e o navegador.

endpoint <------> Web server



## Tipos de Ameaças (Threats)

**Malware**
Um programa que é inserido em um sistema, geralmente de forma encoberta, com a intenção de comprometer a confidencialidade, integridade ou disponibilidade dos dados, aplicativos ou sistema operacional da vítima ou de outra forma incomodar ou interromper a vítima.

**Ransonware**
Malware usado com a finalidade de facilitar um ataque de resgate. Os ataques de ransomware geralmente usam criptografia para “bloquear” os arquivos em um computador afetado e exigem o pagamento de uma taxa de resgate em troca do código de “desbloqueio”.

**Virus**
O vírus de computador é talvez a forma mais antiga de código malicioso para atormentar os administradores de segurança. Um vírus é um pedaço de código autorreplicante que se espalha sem o consentimento do usuário, mas frequentemente com a ajuda dele (o usuário precisa clicar em um link ou abrir um arquivo).

**Worm**
Os worms representam um risco significativo para a segurança da rede. Eles contêm o mesmo potencial destrutivo de outros objetos de código malicioso com uma diferença adicional: eles se propagam sem exigir nenhuma intervenção humana.

**Trojan**
O cavalo de Tróia é um programa de software que parece benevolente, mas carrega uma carga útil maliciosa nos bastidores que tem o potencial de causar estragos em um sistema ou rede. Por exemplo, o ransomware geralmente usa um Trojan para infectar uma máquina de destino e, em seguida, usa a tecnologia de criptografia para criptografar documentos, planilhas e outros arquivos armazenados no sistema com uma chave conhecida apenas pelo criador do malware.

**Spoofing**
Um ataque com o objetivo de obter acesso a um sistema de destino por meio do uso de uma identidade falsificada.

**Phishing**
Um ataque que tenta desviar usuários legítimos para sites maliciosos por meio do abuso de URLs ou hiperlinks em e-mails pode ser considerado phishing.  Está associado à engenharia social.

**DOS/DDOS**
Um ataque de negação de serviço (DoS) é um ataque de consumo de recursos de rede que tem como objetivo principal impedir atividades legítimas em um sistema vitimado. Ataques envolvendo vários sistemas de vítimas secundárias inocentes são conhecidos como ataques distribuídos de negação de serviço (DDoS).



## Sistema de Detecção de Intrusão (IDS)

Uma intrusão ocorre quando um invasor é capaz de contornar ou frustrar os mecanismos de segurança e obter acesso aos recursos de uma organização. A detecção de intrusão é uma forma específica de monitoramento que monitora informações gravadas e eventos em tempo real para detectar atividades anormais que indiquem um possível incidente ou intrusão. **Um sistema de detecção de intrusão (IDS) automatiza a inspeção de logs e eventos do sistema em tempo real para detectar tentativas de intrusão e falhas do sistema.**

Os tipos de IDS são comumente classificados como baseados em host e baseados em rede. Um IDS baseado em host (HIDS) monitora um único computador ou host. Um IDS baseado em rede (NIDS) monitora uma rede observando padrões de tráfego de rede.

#### Sistema de detecção de intrusão baseado em host (HIDS)
Um HIDS monitora a atividade em um único computador, incluindo chamadas de processo e informações registradas no sistema, aplicativo, segurança e logs de firewall baseados em host.

####  Sistema de Detecção de Intrusão de Rede (NIDS)
Um NIDS monitora e avalia a atividade da rede para detectar ataques ou anomalias de eventos. Ele não pode monitorar o conteúdo do tráfego criptografado, mas pode monitorar outros detalhes do pacote. Um NIDS geralmente é capaz de detectar o início de um ataque ou ataques em andamento, mas nem sempre pode fornecer informações sobre o sucesso de um ataque.

#### Informações de segurança e gerenciamento de eventos (SIEM)
O gerenciamento de segurança envolve o uso de ferramentas que coletam informações sobre o ambiente de TI de várias fontes diferentes para examinar melhor a segurança geral da organização e simplificar os esforços de segurança. Essas ferramentas são geralmente conhecidas como soluções de gerenciamento de eventos e informações de segurança (ou SIEM, pronuncia-se “SIM”). A ideia geral de uma solução SIEM é coletar dados de log de várias fontes em toda a empresa para entender melhor as possíveis preocupações de segurança e distribuir os recursos de acordo.



## Sistema de Prevenção de Intrusão (IPS)

Um sistema de prevenção de intrusão (IPS) é um tipo especial de IDS ativo que tenta automaticamente detectar e bloquear ataques antes que atinjam os sistemas de destino. Uma diferença distintiva entre um IDS e um IPS é que o IPS é colocado de acordo com o tráfego. Ou seja, todo o tráfego deve passar pelo IPS e o IPS pode escolher qual tráfego encaminhar e qual bloquear após analisá-lo. Isso permite que o IPS evite que um ataque atinja um alvo. Como os sistemas IPS são mais eficazes na prevenção de ataques baseados em rede, é comum ver a função IPS integrada aos firewalls.

Assim como o IDS, existem IPS baseados em rede (NIPS) e IPS baseados em host (HIPS).



## Cloud

A computação em nuvem é geralmente associada a um conjunto de recursos de computação baseados na Internet e normalmente vendida como um serviço, fornecido por um provedor de serviços em nuvem (CSP). 

A computação em nuvem tem muitos benefícios para as organizações, que incluem, mas não estão limitados a: 

-   O uso é medido e cobrado de acordo com as unidades (ou instâncias) consumidas. Isso também pode ser cobrado de departamentos ou funções específicas.
-   Custo de propriedade reduzido. Não há necessidade de comprar nenhum ativo para uso diário, nenhuma perda de valor do ativo ao longo do tempo e redução de outros custos relacionados de manutenção e suporte.
-   Custos reduzidos de energia e resfriamento, juntamente com efeito de ambiente de “TI verde” com uso otimizado de recursos e sistemas de TI.
-   Permite que uma empresa amplie novos softwares ou serviços/soluções baseados em dados por meio de sistemas em nuvem rapidamente e sem a necessidade de instalar hardware massivo localmente.

Os tipos de modelos de serviços de computação em nuvem incluem Software como Serviço (SaaS) , Plataforma como Serviço (PaaS) e Infraestrutura como Serviço (IaaS) .

##### Software como Serviço (SaaS)

SaaS é um modelo distribuído em que os aplicativos de software são hospedados por um fornecedor ou provedor de serviços em nuvem e disponibilizados aos clientes por meio de recursos de rede.

##### Plataforma como Serviço (PaaS)

A PaaS é uma forma de os clientes alugarem hardware, sistemas operacionais, armazenamento e capacidade de rede pela Internet de um provedor de serviços em nuvem. A PaaS normalmente fornece um conjunto de blocos de construção de software e ferramentas de desenvolvimento, como linguagens de programação e suporte a um ambiente de tempo de execução, que facilitam a construção de aplicativos escaláveis ​​e de alta qualidade, fornecendo assim o ambiente mais adequado para os clientes criarem e operarem seu próprio software.

##### Infraestrutura como Serviço (IaaS)

Os modelos IaaS fornecem recursos básicos de computação aos consumidores. Isso inclui servidores, armazenamento e, em alguns casos, recursos de rede.


### Modelos de Implantação

##### Público

Nuvens públicas são o que geralmente chamamos de nuvem para o usuário público. É muito fácil obter acesso a uma nuvem pública. Não existe um mecanismo real, além de solicitar e pagar pelo serviço em nuvem. É aberto ao público e, portanto, um recurso compartilhado que muitas pessoas poderão usar como parte de um pool de recursos. Um modelo de implantação de nuvem pública inclui ativos disponíveis para qualquer consumidor alugar ou arrendar e é hospedado por um provedor de serviços de nuvem (CSP) externo.

##### Privado

As nuvens privadas começam com o mesmo conceito técnico das nuvens públicas, exceto que, em vez de serem compartilhadas com o público, geralmente são desenvolvidas e implantadas por uma organização privada que constrói sua própria nuvem. Portanto, esse modelo de implantação inclui ativos baseados em nuvem para uma única organização.

##### Hibrido

Um modelo de implantação de nuvem híbrida é criado combinando duas formas de modelos de implantação de computação em nuvem, geralmente uma nuvem pública e uma privada.



## Design de Rede

O objetivo do projeto de rede é satisfazer os requisitos de comunicação de dados e resultar em um desempenho geral eficiente.

##### Segmentação de Rede

A segmentação de rede envolve o controle do tráfego entre dispositivos em rede. A segmentação completa ou física da rede ocorre quando uma rede é isolada de todas as comunicações externas, de modo que as transações só podem ocorrer entre dispositivos dentro da rede segmentada.

##### Zona Desmilitarizada (DMZ)

Uma DMZ é uma área de rede projetada para ser acessada por visitantes externos, mas ainda isolada da rede privada da organização. Com uma DMZ, os sistemas host acessíveis por meio do firewall são fisicamente separados da rede interna por meio de comutadores seguros ou usando um firewall adicional para controlar o tráfego entre o servidor da web e a rede interna.

Dispositivos que frequentemente devem interagir com o ambiente externo (como um servidor de e-mail) geralmente ficam melhor situados na DMZ.

##### Rede Local Virtual (VLAN)

As VLANs são criadas por switches para segmentar logicamente uma rede sem alterar sua topologia física. Uma rede local virtual é um grupo lógico de estações de trabalho, servidores e dispositivos de rede que parecem estar na mesma LAN, apesar de sua distribuição geográfica.

##### Rede Privada Virtual (VPN)

Uma rede virtual privada (VPN) é um túnel de comunicação que fornece transmissão ponto a ponto de autenticação e tráfego de dados em uma rede não confiável.

Os usuários remotos empregam VPNs para acessar a rede de sua organização e, dependendo da implementação da VPN, eles podem ter a maioria dos mesmos recursos disponíveis como se estivessem fisicamente no escritório.

##### Defesa em Profundidade (Defense in Depth)

A defesa em profundidade usa vários tipos de controles de acesso em camadas literais ou teóricas para ajudar uma organização a evitar uma postura de segurança monolítica.

##### Controle de Acesso à Rede (Network Access Control - NAC)

O controle de acesso à rede (NAC) é um conceito de controle de acesso a um ambiente por meio da estrita adesão e implementação da política de segurança. O objetivo é garantir que todos os dispositivos que pretendam aderir à rede só o façam quando cumprirem os requisitos definidos nas políticas da organização.

**Exemplo**: O acesso à internet do hotel ou shopping centers. Normalmente, um usuário que se conecta a rede hoteleira ou shopping é obrigado a reconhecer a política de uso aceitável antes de ser autorizada a acessar a internet.

##### Zero Trust

As redes de confiança zero geralmente são redes microssegmentadas, com firewalls em quase todos os pontos de conexão. A confiança zero encapsula ativos de informação, os serviços que se aplicam a eles e suas propriedades de segurança. 