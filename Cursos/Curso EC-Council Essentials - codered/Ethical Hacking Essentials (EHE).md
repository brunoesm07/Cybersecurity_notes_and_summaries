# Módulo 1 - Information Security Fundamentals

## Desafios de Segurança

- Conformidade com as leis e regulamentos governamentais;
- Falta de profissionais de segurança cibernética qualificados;
- Dificuldade em centralizar a segurança em um ambiente de computação distribuída;
- Regulamentos de privacidade e proteção de dados fragmentados e complexos;
- Problemas de conformidade devido à implementação de políticas de BYOD nas empresas;
- Realocação de dados confidenciais de data centers legados para a nuvem sem configuração adequada

Os invasores tentam várias ferramentas e técnicas de ataque para **explorar vulnerabilidades** em um sistema de computador ou em sua política e controles de segurança para cumprir seus objetivos.

## Classificaçãos de Ataques

#### Ataques Passivos

Os ataques passivos envolvem a interceptação e **monitoramento do tráfego de rede** e o fluxo de dados na rede do alvo. Esses ataques são muito difíceis de detectar, pois o invasor
não tem interação ativa com o sistema ou rede de destino. Exemplos: **Sniffing**, **Network traffic analysis** e **eavesdropping** 

#### Ataques Ativos

Adulteram os dados em trânsito ou **interrompem a comunicação** ou serviços entre os sistemas para contornar ou invadir sistemas seguros. Eles penetram ou infectam a rede interna do alvo e obtem acesso a um sistema remoto para comprometer a rede interna. Exemplos: **DoS, Man-in-the-Middle, SQL injection, malwares (viruses, worms, ransomware), escalada de privilégios**, etc.

#### Ataques de Proximidade

São executados quando o atacante está em proximidade física com o sistema ou rede de destino, a fim de coletar, modificar ou **interromper o acesso** às informações. Exemplos: **Engenharia Social, Shoulder Surfing, Dumpster diving**

#### Ataques Internos

Ataques internos são executados por pessoas confiáveis e envolvem o uso de acesso privilegiado para **violar regras** ou causar intencionalmente uma ameaça às informações ou sistemas de informação da organização.  Esses ataques afetam as operações de negócios, reputação e lucro da organização. É difícil descobrir um ataque interno. Exemplos: **engenharia social, roubo de dispositivos físicos e implantação de keyloggers e backdoors**

#### Ataques de Distribuição

Ocorrem quando invasores **adulteram hardware ou software** antes da instalação. Os invasores adulteram o hardware ou software em sua origem ou em trânsito.


#### Ameaças ao IoT

Dispositivos IoT têm pouca ou nenhuma segurança, o que os torna vulneráveis ​​a vários tipos de ataques. Devido a restrições de hardware como memória, bateria, etc. esses aplicativos IoT não incluem mecanismos de segurança complexos  para proteger os dispositivos contra ataques.

## ISO/IEC 27001

A ISO/IEC 27001 especifica os requisitos para estabelecer, implementar, manter e melhorar continuamente um sistema de gerenciamento de segurança da informação dentro do contexto de uma organização. Inclui requisitos para a avaliação e tratamento de informações riscos de segurança adaptados às necessidades da organização.

O regulamento destina-se para vários usos diferentes, incluindo:

- Formular requisitos e objetivos de segurança
- Garantir o custo-benefício dos riscos de segurança 
- Garantir a conformidade com leis e regulamentos
- Definir novos processos de gestão de segurança da informação
- Identificar e esclarecer os processos de gestão de segurança da informação existentes
- Utilização pela gestão das organizações para determinar o estado da informação atividades de gerenciamento de segurança
- Implementação de segurança da informação que habilita os negócios
- Fornecer informações relevantes sobre segurança da informação para clientes

## General Data Protection Regulation (GDPR)

O Regulamento Geral de Proteção de Dados (GDPR) é um dos mais rigorosos requisitos de privacidade e leis de segurança globalmente. Embora tenha sido elaborado e aprovado pela União Europeia (UE), impõe obrigações para organizações em qualquer lugar, desde que tenham como alvo ou coletem dados relacionados a pessoas na UE.


# Módulo 2 - Ethical Hacking Fundamentals

## Metodologia Cyber Kill Chain

Cyber Kill Chain é uma maneira eficiente e eficaz de ilustrar como um adversário pode atacar
a organização alvo. Este modelo ajuda as organizações a entender as várias ameaças possíveis
em todas as fases de um ataque e as contramedidas necessárias para se defender contra tais ataques.

A seguir, as várias fases incluídas na metodologia Cyber Kill Chain:

#### Reconnaissance (Reconhecimento)

Um adversário realiza reconhecimento para **coletar** o máximo de **informações** sobre o alvo
quanto possível para sondar os pontos fracos antes de realmente atacar. Eles procuram informações publicamente disponíveis na Internet, informações de rede, sistema de informações e informações das organizações. Ao conduzir reconhecimento em diferentes níveis de rede, o adversário pode obter informações endereços IP específicos e detalhes de funcionários.

O adversário pode usar ferramentas automatizadas, como portas e serviços abertos, vulnerabilidades em aplicativos e credenciais de login, para obter informações. Tais informações podem ajudar o adversário em obter acesso backdoor à rede de destino.

- Passivo: quando um invasor está usando técnicas de reconhecimento passivo, ele não interage com o alvo diretamente e depende de informações publicamente disponíveis.
- Ativo: envolvem interações diretas com o alvo. Por exemplo, eles podem fazer chamadas telefônicas para o help desk ou departamento técnico.

#### Weaponization (Armamento)

O adversário **analisa** os dados coletados na etapa anterior para identificar as vulnerabilidades e técnicas que podem ser exploraras para obter acesso não autorizado à organização alvo. O adversário seleciona ou cria uma carga útil maliciosa de entrega. Por exemplo, o adversário
pode enviar (delivery) um e-mail de phishing para um funcionário da organização de destino, que pode incluir um anexo malicioso (weaponization) como um vírus ou worm que, quando baixado, instala um backdoor no sistema que permite acesso remoto ao adversário.

#### Delivery (Entrega)

A carga útil é transmitida à vítima pretendida como um anexo de e-mail, por meio de um link malicioso em sites ou por meio de um aplicativo da web vulnerável ou unidade USB. A entrega é uma etapa chave que mede a eficácia das estratégias de defesa implementadas pela organização-alvo.

#### Exploitation (Exploração)

Depois que a carga maliciosa é transmitida à vítima pretendida, a exploração desencadeia o
código malicioso do adversário para explorar uma vulnerabilidade no sistema operacional,
aplicativo ou servidor em um sistema de destino.

Explorar vulnerabilidades de software ou hardware para obter acesso remoto ao sistema alvo.

#### Installation (Instalação)

Após a injeção do código malicioso em um sistema de destino, o invasor ganha a capacidade de espalhar a infecção para outros sistemas finais na rede. Além disso, o invasor tenta esconder a presença de atividades maliciosas dos controles de segurança como firewalls usando várias técnicas como criptografia.

#### Command and Control

O invasor cria um canal de comando e controle, que estabelece uma comunicação de mão dupla
entre o sistema da vítima e o servidor controlado pelo invasor para comunicar e passar dados para frente e para trás.

#### Actions on Objectives (Ações sobre Objetivos)

O invasor controla o sistema da vítima de um local remoto e finalmente cumpre os objetivos pretendidos. O invasor obtém acesso a dados confidenciais, interrompe os serviços ou rede, ou destroi a capacidade operacional do alvo. Além disso, o invasor pode usar isso como um ponto de partida para realizar outros ataques.

## Indicators of Compromise - IoCs

A compreensão dos IoCs ajuda os profissionais de segurança a detectar rapidamente as ameaças que entram na organização e proteger contra ameaças em evolução. 

- **Indicadores de e-mail** -> Incluem o endereço de e-mail do remetente, assunto do e-mail e anexos ou links. 
- **Indicadores de rede** -> incluem URLs, nomes de domínio e endereços IP. Informam detalhes sobre o sistema operacional, tipo de navegador e outras informações específicas do computador.
- **Indicadores baseados em host** -> são encontrados realizando uma análise do sistema infectado dentro da rede organizacional. Incluem nomes de arquivo, hashes, chaves de registro, DLLs e mutex.
 - **Indicadores comportamentais** -> esses indicadores são úteis para identificar quando serviços de sistema legítimos são usados ​​para atividades anormais ou inesperadas. Incluem documentos de execução de script do PowerShell e execução de comando remoto.

## O que é Hackear?

Hacking no campo da segurança de computadores refere-se à exploração de vulnerabilidades do sistema e comprometimento dos controles de segurança para obter acesso não autorizado ou inapropriado aos recursos do sistema.

O hacker é uma pessoa que invade um sistema ou rede sem autorização para destruir, roubar dados confidenciais ou realizar ataques maliciosos.

#### Fases de hacking

Em geral, existem cinco fases de hacking:

- **Reconhecimento (reconnaissance)**
- **Varredura (scanning)**
- **Obtenção de Acesso (gaining access)** -> refere-se ao ponto em que o invasor obtém acesso ao sistema operacional ou aos aplicativos no computador ou na rede. Depois que um invasor obtém acesso ao sistema de destino, ele tenta escalar privilégios para assumir o controle total.
- **Manutenção do Acesso (maintaining access)**
- **Limpeza de Pistas (clearing tracks)** -> limpar rastros refere-se às atividades
realizada por um invasor para ocultar atos maliciosos.

Os termos “cracker” e “attacker” referem-se a pessoas que empregam suas habilidades de hacker para fins ofensivos (maliciosos).

O termo “hacker ético” refere-se a profissionais de segurança que empregam suas habilidades de hacking para fins defensivos. Sempre com consentimento da empresa.

A avaliação de um hacker ético sobre a segurança do sistema de informação de um cliente procura responder a três perguntas básicas:

1. O que um invasor pode ver no sistema de destino?
2. O que um invasor pode fazer com essa informação?
3. As tentativas dos invasores estão sendo notadas nos sistemas de destino?

#### Escopo e Limitações do Ethical Hacking

**Escopo**
- Fator crucial de avaliação de risco, auditoria, combate à fraude e melhores práticas de segurança de sistemas de informação.
- É usado para identificar riscos e destacar ações corretivas. Isso também reduz os custos de TIC resolvendo vulnerabilidades.

**Limitações**
- A menos que as empresas já saibam o que eles estão procurando e por qual motivo estão contratando um fornecedor externo para hackear os seus sistemas, é provável que não haveria muito a ganhar com a experiência.
- Um hacker ético só pode ajudar a organização a entender melhor seu sistema de segurança; cabe à organização realizar as melhorias de segurança na rede.

#### Skills de um Hacker Ético

**Habilidades técnicas**

- Conhecimento profundo dos principais ambientes operacionais, como Windows, Unix, Linux e Mac
- Conhecimento profundo de conceitos de rede, hardware e software
- Conhecimento das áreas de segurança e assuntos relacionados
- Alto conhecimento técnico de como lançar ataques sofisticados

**Habilidades não-técnicas**

- A capacidade de aprender e adaptar-se rapidamente a novas tecnologias
- Um forte senso ético de trabalho e boa resolução de problemas
- Compromisso com as políticas de segurança de uma organização
- Uma consciência dos padrões e leis locais

## Ferramentas de Hacking Ético

#### Google Hacking

Google hacking refere-se ao uso de operadores avançados de pesquisa do Google para criar complexas consultas de pesquisa para extrair informações confidenciais ou ocultas. Os atacantes podem usar o **Google Hacking Database (GHDB)**, um banco de dados de consultas, para identificar dados confidenciais.

A sintaxe para usar um operador de pesquisa avançada é a seguinte: operator: **search_term**

#### Ferramentas de Reconhecimento

São usadas para coletar informações básicas sobre os sistemas de destino para que se possa explora-los.

- **[Web Data Extractor](http://www.webextractor.com)** -> extrai automaticamente informações específicas de páginas da web: dados de contato direcionados (e-mail, telefone e fax) do site, URL e meta tags (título, descrição, palavra-chave) e assim por diante.
- [**Whois Lookup**](https://whois.domaintools.com) -> O serviço fornece informações Whois, como informações do registrante, e-mail, informações de contato, data de criação e expiração e uma lista de servidores de domínio.

#### Ferramentas de Scanning

- **[Nmap](https://nmap.org)** ->  scanner de segurança para exploração de rede e hacking. Isto permite que você descubra hosts, portas e serviços em uma rede de computadores, criando assim um "mapa" da rede.
- **[MegaPing](http://www.magnetosoft.com)** -> inclui scanners como o Comprehensive Security Scanner, o Port scanner (TCP e portas UDP), scanner de IP, scanner NetBIOS e Share Scanner.

# Módulo 3 - Information Security Threats and Vulnerability Assessment

É importante entender a diferença entre uma ameaça à segurança e uma vulnerabilidade. Ameaças à segurança são incidentes que impactam negativamente a infraestrutura de TI da organização, enquanto as vulnerabilidades são falhas de segurança ou falhas em um sistema ou rede que tornam as ameaças possíveis de serem exploradas.

Os invasores usam ameaças cibernéticas para se infiltrar e roubar dados como dados individuais
informações pessoais, financeiras e credenciais de login.

A criticidade de uma ameaça é baseada em quanto dano que pode causar, o quão incontrolável é, ou o nível de complexidade na identificação com antecedência.

Exemplos de ameaça:
- Roubo de dados confidenciais de uma organização
- Infecção de um sistema com malware
- Alteração dos dados em um servidor de banco de dados

## Fontes de Ameaças

Elas podem ser classificadas como ameaças naturais, ameaças não intencionais e ameaças intencionais.

**Ameaças Naturais** -> Fatores naturais, como incêndios, inundações, falhas de energia, raios, meteoros e terremotos são ameaças potenciais aos ativos de uma organização.

**Ameaças não intencionais** -> Ameaças não intencionais são ameaças que existem devido ao potencial de erros não intencionais ocorrendo dentro da organização. Os exemplos incluem negligência, erros do operador, administradores não qualificados, funcionários preguiçosos ou não treinados e acidentes.

**Ameaças intencionais** -> podem ser internas ou externas

- **Internas**: Essas ameaças são executadas por pessoas de dentro da organização, como por exemplo funcionários descontentes. As causas dos ataques internos podem ser vingança, desrespeito, frustração ou falta de consciência de segurança.

- **Externas**: Os invasores podem realizar tais ataques para obter ganhos financeiros, para prejudicar a reputação da organização-alvo, ou simplesmente por curiosidade.

## Malware

Malware é um software malicioso que danifica ou desativa sistemas de computador e fornece acesso limitado ou controle total dos sistemas ao criador do malware para atividades maliciosas. Malware inclui vírus, worms, trojans, rootkits, backdoors, botnets, ransomware, spyware, adware, scareware, crapware, roughware, crypters, keyloggers, etc.

Algumas técnicas usadas para distribuir malware na web são:

- **Black hat SEO**: usa táticas agressivas de SEO, como preenchimento de palavras-chave, inserção de páginas de entrada, troca de página e adição de palavras-chave não relacionadas para obter classificações mais altas nos mecanismos de pesquisa.

- **Click-jacking**: os invasores injetam malware em sites que parecem legítimos para induzir os usuários a clicar neles.Quando clicado, o malware embutido no link é executado sem o conhecimento ou consentimento do usuário.

- **Spear-Phishing**

- **Malvertising**: Esta técnica envolve a incorporação de anúncios carregados de malware em
canais de publicidade on-line legítimos para espalhar malware em sistemas de usuários.

- **Sites legítimos comprometidos**: frequentemente, os invasores usam sites comprometidos para
infectar sistemas com malware.

#### Componentes do Malware

Os autores e invasores de malware os criam usando componentes que podem ajudá-los a atingir seus objetivos. Certos componentes essenciais da maioria dos programas de malware são os seguintes:

- **Crypter**: software que pode ocultar a existência de malware. Os invasores usam para iludir a detecção de antivírus.

- **Downloader**: é um tipo de Trojan que baixa outro malware (ou) código malicioso e arquivos da Internet para um PC ou dispositivo.

- **Dropper**: pode transportar código de malware e executar malware em um sistema de destino sem ser detectado por scanners antivírus.

- **Exploit**: é a parte do malware que contém código ou uma sequência de comandos que podem tirar proveito de um bug ou vulnerabilidade em um sistema ou dispositivo digital.

- **Injector**: injeta exploits ou códigos maliciosos disponíveis no malware em outros processos em execução vulneráveis ​​e muda o método de execução para ocultar ou impedir sua remoção.

- **Obfuscator**: é um programa que oculta o código malicioso de malware através de várias técnicas, tornando difícil para os mecanismos de segurança detectá-lo ou removê-lo.

- **Packer**: comprime o arquivo de malware para converter o código e os dados do malware em um formato ilegível.

- **Payload**: é a parte do malware que executa a atividade desejada quando ativado. Pode ser usado para excluir ou modificar arquivos, degradando o sistema, abrindo portas, alterando configurações e assim por diante, para comprometer o sistema de segurança.

- **Código Malicioso**:  pedaço de código que define a funcionalidade básica do malware e compreende comandos que resultam em violações de segurança.

#### Tipos de Malware

Um malware é um software malicioso projetado para executar atividades conforme pretendido pelo invasor, sem o consentimento do usuário. Isso pode ser na forma de código executável, conteúdo ativo, scripts ou outros tipos de software.

Abaixo estão vários tipos de malware:

- Trojans -> programa no qual um código malicioso ou prejudicial é contido dentro de um programa ou dados aparentemente inofensivos, que mais tarde podem ganhar controle e causar danos.

- Vírus

- Ransomware -> tipo de malware que restringe, através de criptografia, o acesso ao sistema do computador infectado ou arquivos críticos e documentos armazenados nele e, em seguida, exige um pagamento de resgate.

- Worms -> são programas maliciosos autônomos que se replicam, executam e se espalham em conexões de rede de forma independente, sem intervenção humana. Os invasores costumam usar cargas de worms para instalar backdoors em computadores infectados, o que os transforma em "zumbis" e cria uma botnet.

- Rootkits -> softwares projetados para obter acesso a um computador sem serem detectados. O objetivo de um rootkit é obter privilégios de root em um sistema.

- Spyware -> software furtivo de monitoramento de computador que permite gravar secretamente todas as atividades do usuário. Isso permite que um invasor reúna informações sobre uma vítima ou organização, como endereços de e-mail, logins de usuários, senhas, números de cartão de crédito e credenciais bancárias.

- Keylogger -> software ou dispositivos de hardware que registram as teclas pressionadas no teclado de computador. Um keylogger, quando associado a spyware, ajuda a transmitir as informações de um usuário para um atacante.

- Botnets -> conjunto de computadores comprometidos conectados à Internet utilizados, sem a permissão do usuário, para executar tarefas distribuídas automatizadas. Botmasters lançam ataques DDoS em usuários-alvo específicos que consomem a largura de banda do computador da vítima.. Podem também usar bots para aumentar o faturamento de anúncios na web, clicando automaticamente nestes.

#### Virus Maker Tools

- DELmE’s Batch Virus Maker -> programa de criação de vírus com muitas opções para infectar o PC da vítima.
- JPS Virus Maker ->usada para criar vírus personalizados.
- Bhavesh Virus Maker SKW
- SonicBat Batch Virus Maker

#### Worm Makers Tools 

- Internet Worm Maker Thing -> ferramenta de código aberto usada para criar worms.
- Batch Worm Generator
- C++ Worm Generator


### Contramedidas de Malware

Impedem a entrada de malware em um sistema e minimizam o risco causado por ele em sua entrada.

##### Trojan
- Evite abrir anexos de e-mail recebidos de remetentes desconhecidos
- Bloqueie todas as portas desnecessárias no host e use um firewall
- Evite aceitar programas transferidos por mensagens instantâneas
- Fortalecer definições de configuração padrão fracas e desabilitar funcionalidades não utilizadas, incluindo protocolos e serviços
- Monitore o tráfego de rede interna em busca de portas estranhas ou tráfego criptografado
- Evite baixar e executar aplicativos de fontes não confiáveis
- Instalar patches e atualizações de segurança para o sistema operacional e aplicativos
- Escaneie drives USB externos e DVDs com software antivírus antes de usá-los
- Restrinja as permissões no ambiente da área de trabalho para impedir a instalação de aplicativos maliciosos
- Execute antivírus baseado em host, firewall e software de detecção de intrusão

##### Virus e Worms
- Instale um software antivírus que detecte e remova infecções à medida que aparecem
- Preste atenção às instruções ao baixar arquivos ou programas da Internet
- Atualize regularmente o software antivírus
- Evite abrir anexos recebidos de remetentes desconhecidos, pois os vírus se espalham por meio de anexos de e-mail
- Como as infecções por vírus podem corromper os dados, certifique-se de fazer backups regulares dos dados
- Agende varreduras regulares para todas as unidades após a instalação do software antivírus
- Mantenha-se informado sobre as últimas ameaças de vírus
- Certifique-se de que os bloqueadores de pop-up estejam ativados e use um firewall de Internet
- Execute anti-spyware ou anti-adware uma vez por semana
- Não abra arquivos com mais de uma extensão de tipo de arquivo

## Vulnerabilidades

Uma vulnerabilidade refere-se a uma fraqueza no projeto ou implementação de um sistema que pode ser explorado para comprometer a segurança do sistema. As vulnerabilidades presentes em um sistema ou rede são classificadas nas seguintes categorias:

##### Configuração incorreta

É a vulnerabilidade mais comum e é causada principalmente por erro, que permite que invasores obtenham acesso não autorizado ao sistema. Pode acontecer intencionalmente ou não e afeta servidores web, plataformas de aplicativos, bancos de dados e redes.

##### Instalações Defaut (padrão)

Ao não alterar as configurações padrão durante a implantação do software ou hardware permite-se que o invasor adivinhe as configurações, facilitando a invasão do sistema.

##### Buffer Overflows

São vulnerabilidades de software comuns que ocorrem devido a erros de codificação que permitem aos invasores obter acesso ao sistema de destino.

##### Unpatched Servers

Os servidores são um componente essencial da infraestrutura de qualquer organização. Há vários casos em que as organizações executam servidores sem patches e mal configurados. A atualização de software regularmente corrigindo bugs pode ajudar a mitigar.

##### Senhas Padrão ou Fracas

Os fabricantes fornecem aos usuários senhas padrão para acessar o dispositivo durante sua configuração inicial, que os usuários devem alterar para uso futuro.

##### Zero Day

Vulnerabilidades de dia zero são vulnerabilidades até então desconhecidas em software/hardware. Estes são explorados pelos atacantes antes de serem reconhecidos e corrigidos pelos desenvolvedores ou analistas de segurança.

##### Plataforma Legada

As vulnerabilidades da plataforma legada são expostas a partir de códigos antigos ou familiares.

### Vulnerabilidades de Redes

##### Tecnológicas
- Protocolos TCP/IP
- Sistemas Operacionais
- Dispositivos de rede -> roteadores, firewall e switches 

##### Configurações
- Conta de usuário
- Conta do sistema -> originado da configuração de senhas fracas para as contas.
- Configuração incorreta do dispositivo de rede

##### Política de Segurança
- Política não escrita -> são difíceis de implementar e fazer cumprir
- Falta de continuidade
- Falta de consciência

### Impacto das Vulnerabilidades

- Divulgação de informações: um site ou aplicativo pode expor informações específicas do sistema em formação.
- Negação de serviço: vulnerabilidades podem impedir que os usuários acessem os serviços do site ou outros recursos. 
- Escalonamento de privilégios: os invasores podem obter acesso elevado a um sistema protegido.
- Acesso não autorizado: Os invasores podem obter acesso não autorizado a um sistema, uma rede, dados ou um aplicativo.
- Roubo de identidade: Os invasores podem roubar as informações pessoais ou financeiras de usuários para cometer fraudes com sua identidade.
- Exfiltração de dados: Vulnerabilidades podem levar à recuperação não autorizada e transmissão de dados sensíveis.
- Danos à reputação: Vulnerabilidades podem causar danos à reputação de uma empresa. Danos à reputação têm impacto direto sobre clientes, vendas e lucro.
- Consequências legais: Se os dados pessoais dos clientes forem comprometidos, a organização pode precisar enfrentar consequências legais na forma de multas e sanções regulatórias.

### Ferramentas para Pesquisa de Vulnerabilidades

A pesquisa de vulnerabilidade é o processo de análise de protocolos, serviços e configurações para
descobrir as vulnerabilidades e falhas de projeto. Um hacker ético precisa acompanhar as vulnerabilidades descobertas mais recentemente.

- Microsoft Vulnerability Research (MSVR) (https://www.microsoft.com)
- Dark Reading (https://www.darkreading.com)
- SecurityTracker (https://securitytracker.com)
- Trend Micro (https://www.trendmicro.com)
- Security Magazine (https://www.securitymagazine.com)
- PenTest Magazine (https://pentestmag.com)
- Revista SC (https://www.scmagazine.com)
- Exploit Database (https://www.exploit-db.com)
- SecurityFocus (https://www.securityfocus.com)
- Help Net Security (https://www.helpnetsecurity.com)
- HackerStorm (http://www.hackerstorm.co.uk)
- Computerworld (https://www.computerworld.com)
- WindowsSecurity (http://www.windowsecurity.com)
- D'Crypt (https://www.d-crypt.com)

### Sistemas de Pontuação e Banco de Dados de Vulnerabilidades

Devido à crescente gravidade dos ataques cibernéticos, a pesquisa de vulnerabilidade tornou-se crítica, pois ajuda a mitigar a chance de ataques. Sistemas de pontuação e bancos de dados de vulnerabilidades são usados ​​por analistas de segurança para classificar vulnerabilidades do sistema de informação e para fornecer uma pontuação da gravidade geral e riscos associados.

Alguns dos sistemas de pontuação e bancos de dados de vulnerabilidade:

- Sistema de Pontuação de Vulnerabilidade Comum ([CVSS](: https://www.first.org, https://nvd.nist.gov))
- Vulnerabilidades e Exposições Comuns ([CVE](: https://cve.mitre.org))
- Base de Dados Nacional de Vulnerabilidades ([NVD](: https://nvd.nist.gov))
- Enumeração de Fraqueza Comum ([CWE](https://cwe.mitre.org))

### Ciclo de Vida do Gerenciamento de Vulnerabilidades

É um processo importante que ajuda a identificar e corrigir falhas de segurança antes que elas possam ser exploradas. O gerenciamento de vulnerabilidades fornece os melhores resultados quando é implementado em uma sequência de fases bem organizadas.

As fases envolvidas no gerenciamento de vulnerabilidades são:

- Identificar ativos críticos e definir o risco com base na criticidade e valor de cada sistema.
- Varredura de vulnerabilidade para avaliar os pontos fracos da infraestrutura da organização
- Avaliação de Risco: determina se o nível de risco para um determinado ativo é alto, moderado ou baixo.
- Remediação: processo de aplicação de correções em sistemas vulneráveis ​​para reduzir o impacto e a gravidade das vulnerabilidades.
- Verificação: a equipe de segurança realiza uma nova verificação dos sistemas para avaliar se os requisitos de correção estão concluídos e se as correções individuais foram aplicadas aos ativos impactados.
- Monitoramento: As organizações precisam realizar monitoramento regular para manter a segurança do sistema.

### Ferramentas de Avaliação de Vulnerabilidades

Os analistas de segurança podem usar ferramentas de avaliação de vulnerabilidade para identificar os pontos fracos presentes na postura de segurança da organização.

- Qualys Vulnerability Management (https://www.qualys.com)
- OpenVAS (https://www.openvas.org)
- GFI LanGuard (: https://www.gfi.com)
- Nessus Professional (https://www.tenable.com) 
- Nikto (https://cirt.net)
- Qualys FreeScan (https://freescan.qualys.com)

### Exploração de Vulnerabilidade (Exploitation)

A exploração de vulnerabilidade envolve a execução de várias etapas complexas e inter-relacionadas para obter acesso a um sistema remoto.

Etapas envolvidas na exploração de vulnerabilidades:

1. Identifique a vulnerabilidade
2. Determine o risco associado à vulnerabilidade
3. Determine a capacidade da vulnerabilidade (Se o risco for baixo, os invasores podem determinar a capacidade de explorar essa vulnerabilidade para obter acesso remoto ao sistema de destino.)
4. Desenvolva a exploração (atacantes usam exploits de sites de exploração como o [Exploit Database](https://www.exploit-db.com))
5. Selecione o método de entrega
6. Gere e entregue a carga útil (maliciosas) (Os atacantes geram ou selecionam cargas maliciosas usando ferramentas como Metasploit e o entregam ao sistema remoto usando engenharia social ou através de uma rede.)
7. Obtenha o acesso remoto (Agora, os invasores podem executar vários comandos maliciosos no shell remoto e controlar o sistema.)