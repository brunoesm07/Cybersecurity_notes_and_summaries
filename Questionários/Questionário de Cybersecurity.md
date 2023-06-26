# Perguntas

## Quais são os três pilares da segurança da informação? Qual a importância de cada um? Seja detalhista.

- Confidencialidade - garantir que uma determinada informação ou dado seja disponibilizado exclusivamente para quem tem autorização para tal.
Exemplos de quebra de confidencialidade: escalonamento de privilégios e quebra de senhas.

- Integridade - garantir que as informações estejam conforme foram estabelecidas e, caso haja modificação, tenha ocorrido de forma autorizada.
Exemplo de quebra de integridade: técnica Man-in-the-middle onde o atacante intercepta o tráfego de rede, ficando no meio da comunicação e monitorando tudo o que está acontecendo.

- Disponibilidade - garantir acesso confiável à informação sempre que necessário
Exemplo de quebra de disponibilidade: ataque DDoS (Negação de Serviço), onde ocorre um bombardeamento em um sistema com uma quantidade esmagadora de tráfego fazendo com que o mesmo fique indisponível.

## O que é não repúdio? Qual sua importância para segurança da informação?

Incapacidade de alguém negar a realização de uma ação verdadeira, confirmada por registros, como por exemplo assinatura digital ou logs. Importante pois previne que alguma das partes negue ou conteste uma transação após ela ser realizada, sendo uma evidência suficiente para ser utilizada perante a autoridade legal.

## O que é MFA? Qual sua utilidade para segurança da informação?

Autenticação Multifator. Garantir a autenticação de uma tentativa de acesso utilizando-se mais de um fator em conjunto, que pode ser algo que o usuário conheça (ex: senha), algo que o usuário tenha (ex: token) ou algo que o usuário seja (ex: biometria). Porém, dois métodos iguais não garantem a MFA.

![autenticação](https://github.com/brunoesm07/Cybersecurity_notes_and_summaries/blob/c5bf8bb638c5f50591837163b24910de94af2045/assets/autentica%C3%A7%C3%A3o.png)

## O que é um ataque DDoS? Cite um exemplo real.

O ataque de negação de serviço distribuído (DDoS) é executado a partir de diversas fontes coordenadas que resulta em algum tipo de interrupção de serviço aos usuários, dispositivos ou aplicações.

Um exemplo real foi o ataque sofrido pela AWS em fevereiro de 2020 onde em seu ápice, o ataque disparou um tráfego de entrada a uma taxa de 2,3 terabits por segundo (Tbps). A AWS não divulgou a qual cliente o ataque foi direcionado.

## O que é uma vulnerabilidade zero-day? Qual seu impacto na segurança da informação?

São vulnerabilidades até então desconhecidas pelos fornecedores e, portanto, sem proteção adequada. Durante o tempo que os fornecedores de software demoram para desenvolver e liberar um patch, a rede está vulnerável a essas explorações. 

## Aponte a principal característica ou a diferença de:  
  
- **Malware**  - termo usado para descrever o software desenvolvido para interromper as operações do computador ou obter acesso a sistemas informatizados, sem o conhecimento ou permissão do usuário.
- **Ransomware**  - aprisiona um sistema de computador ou os dados nele encontrados até que a vítima faça um pagamento. Funciona criptografando os dados no computador com uma chave desconhecida ao usuário.
- **Vírus**  - é um código malicioso executável que está anexado a outro arquivo executável, como um programa legítimo. A maioria dos vírus necessitam de inicialização do usuário final.
- **Worm**  - semelhantes ao vírus, podem ser executados de modo autônomo. Exceto pela infecção inicial, os worms não necessitam mais da participação do usuário.
- **Spyware** - é o software que permite que um criminoso obtenha informações sobre as atividades do computador do usuário.
- **Key logger** - registro de pressionamento de teclas em um teclado, geralmente sem a permissão ou o conhecimento do usuário.

## O que é engenharia social? Cite 03 técnicas de engenharia social.

Engenharia social é um meio totalmente não técnico de um criminoso coletar informações sobre a vítima. Engenharia social é um ataque que tenta manipular indivíduos para realizar ações ou divulgar informações confidenciais.

**Pretexting** - Ocorre quando um invasor chama uma pessoa e mente para ela na tentativa de obter acesso a dados confidenciais. Um exemplo envolve um invasor que finge precisar de dados pessoais ou financeiros para confirmar a identidade do destinatário.

**Something for Something (Quid pro quo)** - Ocorre quando um invasor solicita informações pessoais de uma pessoa em troca de algo, como um presente.

**Baiting** - Se utiliza da curiosidade humana ao deixar algum dispositivo externo infectado em uma mesa ou até mesmo distribuí-lo gratuitamente, o criminoso espera que os curiosos de plantão abram o dispositivo e executem arquivos, podendo infectar máquinas e possivelmente a rede corporativa.


## Qual a diferença entre um spam, um phishing e um spear phishing?

Spam é um email indesejado, não solicitado, mas sem carga maliciosa, enquanto que um phishing ocorre quando uma parte mal-intencionada envia um e-mail fraudulento disfarçado de uma fonte legítima e confiável. Já o Spear phishing é um ataque de phishing altamente direcionado, personalizado para uma pessoa específica.

## Descreva como um atacante poderia levantar informações para lançar um spear phishing em uma grande empresa listada na bolsa de valores.

Toda informação sobre uma vítima é relevante para a elaboração de um ataque, inclusive seus gostos pessoais e rotina. Essas informações podem ser levantadas visitando locais habituais que a vitima frequente, observando os comportamentos da vitima e seus familiares e amigos nas redes sociais e até mesmo indo nas empresas e levantando informações em bate papos informais com funcionários. 

## Explique brevemente as seguintes normas:  
-  BACEN 4658/4893
- LGPD/GDPR  
- PCI:DSS  
- SOX  
- ISO 27001

**BACEN 4658/4893**

A Resolução **BACEN 4658** entrou em vigor no dia 26 de abril de 2018, por decisão do Banco Central do Brasil. Ela estabelece as exigências para as instituições financeiras e quaisquer outras empresas autorizadas a funcionar pelo Bacen quanto a seus ambientes de tecnologia contra ataques cibernéticos.

E não são apenas as instituições financeiras que devem seguir a 4658 — ela também vale para quaisquer prestadores de serviços que manipulem dados, informações sensíveis ou informações relevantes para o andamento das atividades operacionais das empresas regulamentadas pelo Banco Central.

A Resolução **BACEN 4893/2021**, publicada em 26 de fevereiro de 2021, define sobre a Política de Segurança Cibernética e sobre os requisitos para a contratação de serviços de processamento e armazenamento de dados e de computação em nuvem a serem observados pelas instituições autorizadas a funcionar pelo Banco Central do Brasil. As Empresas cadastradas como Instituições Financeiras junto ao Bacen devem estabelecer plano de ação e de resposta a incidentes

**PCI DSS**

O padrão de segurança de dados do setor de cartões de pagamento (PCI DSS) é um conjunto de regras contratuais que regem como proteger dados de cartão de crédito, à medida que comerciantes e bancos fazem a transação. O PCI DSS é um padrão voluntário (em teoria) e comerciantes/fornecedores podem escolher se desejam cumprir o padrão. No entanto, a não conformidade do fornecedor pode resultar em taxas de transações significativamente maiores, multas de até US $500.000 e, possivelmente, até mesmo na perda da capacidade de processar cartões de crédito.

Governado pelo Conselho de Padrões de Segurança da Indústria de Cartões de Pagamento (PCI SSC), o esquema de conformidade visa proteger transações de cartão de crédito e débito contra roubo de dados e fraude.

A certificação PCI garante a segurança dos dados dos cartões de sua empresa por meio de um conjunto de requisitos estabelecidos pelo PCI SSC. Isso inclui várias práticas recomendadas comumente conhecidas, como:

-   Instalação de firewall
-   Criptografia de transmissões de dados
-   Uso de software antivírus

Além disso, as empresas devem restringir o acesso aos dados do titular do cartão e monitorar o acesso aos recursos da rede.

A conformidade com o PCI  é dividida em quatro níveis, com base no número anual de transações de cartão de crédito ou débito que uma empresa processa. O nível de classificação determina o que uma empresa precisa fazer para permanecer em conformidade.

![](https://github.com/brunoesm07/Cybersecurity_notes_and_summaries/blob/65f8e23a12a43c0f558b9403dd86df6c9afc7b23/assets/PCI%20DSS.png)

**Sarbanes-Oxley Act (SOX)**

Depois de vários escândalos de contabilidade nos EUA, o congresso aprovou a Lei Sarbanes-Oxley (SOX). A finalidade da SOX foi para reformular os padrões de contabilidade financeira e empresarial e foi direcionada especificamente aos padrões das empresas de capital aberto nos Estados Unidos.

**ISO 27001**

Os padrões ISO 27000 descrevem a implementação de um sistema de gerenciamento de segurança da informação abrangente (ISMS). Um ISMS consiste em todos os controles administrativos, técnicos e operacionais para manter a informação segura dentro de uma empresa.

ISO 27001 define objetivos do controle de gerenciamento de segurança da informação, em doze domínios.  Esses doze domínios servem para organizar, em alto nível, as vastas áreas de informações cobertas pela segurança da informação.

## Quais são as fases do ciclo de resposta a incidentes de acordo com o NIST 800-61 REV 2?

- Fase 1: Preparação

- Fase 2: Detecção e Análise

A detecção começa quando é descoberto o incidente. A detecção adequada inclui como o incidente ocorreu, quais dados estavam envolvidos e quais sistemas estavam envolvidos. A análise de incidente ajuda a identificar a origem, extensão, impacto e detalhes de uma violação de dados.

- Fase 3: Contenção, erradicação e recuperação

Os esforços de contenção incluem ações imediatas realizadas, como desconectar um sistema da rede para parar o vazamento de informações.

Depois de identificar a violação, a empresa precisa contê-la e erradicá-la. Isso pode exigir período de inatividade adicional para os sistemas. A fase de recuperação inclui as medidas que a empresa precisa tomar para resolver a violação e restaurar os sistemas envolvidos. Depois da solução, a empresa precisa restaurar todos os sistemas ao seu estado original, antes da violação.

- Fase 4: Atividade pós incidente

Depois de restaurar todas as operações a um estado normal, a empresa deve examinar a causa do incidente. Um exame das lições aprendidas pode ajudar a empresa a se preparar melhor, melhorando o plano de resposta a incidente.

Para mais informações: https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-61r2.pdf

## Descreva o que é o CIS Controls v8.

Os CIS Critical Security Controls (CIS Controls) são um conjunto prescritivo, priorizado e simplificado de práticas recomendadas utilizadas para fortalecer a postura de segurança cibernética da empresa.

v8. significa que é a oitava versão elaborada. (atual)

## Explique o que é o NIST CSF.

É um framework de cybersegurança, ou seja, é uma estrutura baseada em padrões, diretrizes e práticas existentes para que as organizações gerenciem e reduzam melhor os riscos de segurança cibernética. 

## Explique o que é o PMBOK e cite quais são os macroprocessos de gerenciamento de projetos.

É um guia para o gerenciamento de projetos de todos os tipos, independentemente do nicho, da dimensão, do pessoal envolvido, dos prazos e dos orçamentos.

Os macroprocessos são: iniciação, planejamento, execução, monitoramento e controle e, encerramento.

## Explique o que é um ativo, uma vulnerabilidade e uma ameaça. Relacione os três em um exemplo.

Vulnerabilidade é uma fraqueza que torna um alvo suscetível ao ataque, ameaça é qualquer circunstância ou evento com potencial para impactar de maneira prejudicial e, ativo é algo de valor que necessita de proteção. 

Exemplos:

1. Um sistema operacional desatualizado (vulnerabilidade) instalado em um computador da empresa contendo dados sigilosos (ativo) que pode ser explorado em um ataque (ameaça) exploit.

2. Acesso em rede pública (vulnerabilidade) com telefone celular, sem medidas de proteção podendo ser interceptado por um man-in-the-mobile (ameaça) e ter dados (ativo) vazados.

## Explique o que é um APT e cite um exemplo real.

Ameaça ou ataque persistente avançado (APT) usa técnicas de invasão contínuas, clandestinas e sofisticadas para obter acesso a um sistema e permanecer dentro dele por um período prolongado, com consequências potencialmente destrutivas.

O principal perigo de APTs é que, mesmo quando eles são descobertos e a ameaça imediata parece ter sido controlada, os atacantes podem ter deixado várias brechas abertas que lhes permitem retornar quando quiserem.

Exemplo real: APT29, o grupo russo de ameaças persistentes avançadas também conhecido como Cozy Bear, foi associado a uma série de ataques, incluindo um ataque de spear phishing de 2015 no Pentágono, bem como os ataques de 2016 no Comitê Nacional Democrata.

## Quais são os fatores de autenticação? Cite exemplos reais de sua utilização.

Algo que você **sabe** - ex: senha
Algo que você **tem** - ex: token
Algo que você **é** - ex: biometria

## Aponte as diferenças entre os protocolos TCP e UDP.  Depois aponte 02 casos de uso para cada um dos protocolos.

O Transmission Control Protocol (TCP) é responsável pela entrega de dados através de uma conexão confiável, garantindo a entrega integra e na ordem correta. Realiza o handshake de conexão.

O UDP é um protocolo que não é voltado à conexão e preza pela velocidade porém com confiabilidade baixa.

Casos de uso:
TCP - transferência de arquivos e emails
UDP - jogos online e streams de vídeos

## Cite um exemplo de um ator de ameaça sofisticado e um simples. Explique a natureza da sofisticação.

Simples - Script Kiddies
Sofisticado - "Hackers de Estado"

Os atores estatais são suportados pelos governos para objetivos tradicionais de espionagem ou vigilância e visam comprometer ou obter acesso aos dados de inteligência dos governos adversários. Possuem investimento, conhecimento e tempo em grande quantidade.

## O que é o OWASP TOP 10? Cite pelo menos 02 itens presentes no OWASP TOP 10.

É um documento de conscientização, elaborado por uma organização sem fins lucrativos, direcionado a desenvolvedores, que representa um consenso sobre os riscos de segurança mais críticos, naquele período analisado, para aplicações WEB, API e Mobile.

Brocken Access Control e Cryptographic Failures

## O que é um SGSI? Aponte qual norma exige sua elaboração.

Um Sistema de Gestão que inclui toda a abordagem organizacional usada para proteger a informação empresarial e seus critérios de Confidencialidade, Integridade e Disponibilidade. 

Fazem parte da estrutura as estratégias, planos, políticas, medidas, controles, e diversos instrumentos usados para estabelecer, implementar, operar, monitorar, analisar criticamente, manter e melhorar a segurança da informação. 

Exigido pela ISO 27001

## O que são NIST e SANS? Qual relevância para comunidade de segurança da informação? Cite pelo menos um exemplo de trabalho de cada um.

São comunidades de inteligência em segurança cibernética que promovem a inovação por meio do avanço da ciência, padrões e tecnologia.

NIST - Cybersecurity Framework, ajuda as organizações a aprimorarem sua postura em relação à segurança cibernética. 
SANS - Internet Storm Center | Cursos e Certificações

## **O que é um SOC? E um CSIRT?

SOC - O Centro de Operação de Segurança é um local dedicado que monitora, avalia e defende os sistemas de informação da empresa, como sites, aplicações, bancos de dados, data centers, redes, servidores e sistemas de usuários. Um SOC é composto por equipes de analistas de segurança que detectam, analisam, respondem, relatam e previnem incidentes de segurança cibernética.

CSIRT - Computer Security Incident Response Team é um time responsável por receber, analisar e responder a notificações e atividades relacionadas a incidentes de segurança em computadores.

## O que é um plano de resposta a incidentes? Descreva sua importância para uma organização bem como seus principais elementos.

É a documentação de um conjunto predeterminado de instruções ou procedimentos para detectar, responder e limitar as consequências de um ataque cibernético mal-intencionado contra os sistemas de informação de uma organização.

## Explique a necessidade e utilidade do protocolo NAT. Demonstre com um exemplo.

Responsável pela tradução de endereços de rede, convertendo endereços IPv4 de uma rede privada em endereços IPv4 públicos globalmente exclusivos. Permitindo que máquinas de dentro de uma rede se comuniquem com outra rede como se estivessem saindo de um mesmo IP. 

## O que é um plano de recuperação de desastres? Descreva sua importância para uma organização bem como seus principais elementos.

Os processos, políticas e procedimentos relacionados à preparação para a recuperação ou continuação das funções críticas de negócios, infraestrutura de tecnologia, sistemas e aplicativos de uma organização após a organização passar por um desastre.

Refere-se especificamente à restauração dos serviços e sistemas de tecnologia da informação e comunicações necessários para uma organização, tanto durante o período de interrupção causada por qualquer evento quanto durante a restauração dos serviços normais.

## **O que é um pentest? Quais são suas principais modalidades? Qual sua importância em uma estratégia de segurança?

Teste de penetração é a atividade de buscar acesso através de ferramentas e técnicas em sistemas, explorando vulnerabilidades encontradas.

Infraestrutura de rede, Web, aplicativos móveis e Wifi

Ao realizar testes, o pentest contribui para que problemas relacionados à eficácia dos mecanismos de segurança cibernética sejam identificados e corrigidos, elevando os níveis de proteção.

## **Descreva um processo de gestão de vulnerabilidades ideal.

Segundo um artigo da Gartner, os programas de gestão de vulnerabilidades bem-sucedidos utilizam técnicas avançadas de priorização e ferramentas automatizadas de fluxo de trabalho para otimizar a entrega à equipe responsável pela correção.

A gestão de vulnerabilidades deve ser um ciclo do processo para encontrar, avaliar, remediar e mitigar os pontos fracos da segurança nos sistemas de informação. Como partes desse processo, são necessárias definições de política e escopo, avaliação, correção, mitigação e monitoramento.

## Você assumiu como líder de cibersegurança em uma empresa de tecnologia emergente, quais seriam as principais medidas que você tomaria nos primeiros 100 dias de trabalho?

Avaliar o nível de comprometimento e entendimento dos funcionários de todos os setores com as ações para mitigação das ameaças internas à segurança da informação; avaliar a infraestrutura de segurança que visa a proteção às ameaças externas e; avaliar as políticas de segurança adotadas pela empresa.

## **O que é Cyber Kill Chain? Qual sua utilidade? Ela se aplica principalmente a qual tipo de adversário?

Modelo desenvolvido pela Lockheed Martin para identificação e prevenção de atividades de invasões cibernéticas. Ele identifica as etapas que os atacantes devem concluir para atingir seu objetivo.

O Cyber kill chain também pode ser usado como uma ferramenta de gerenciamento para ajudar a melhorar continuamente a defesa.

## **O que é MITRE ATT&CK? Qual sua importância para a comunidade de segurança da informação?

É uma base de conhecimento de táticas e técnicas de ataques cibernéticos baseadas em observações reais. 

As matrizes permitem que as organizações obtenham uma melhor conscientização sobre sua postura geral de segurança, identifiquem e testem vulnerabilidades nos métodos de defesa e priorizem possíveis falhas de segurança com base no risco que elas apresentam para a organização.

## Explique com detalhes o que é, onde e como é utilizado o "Three-way handshake".

- **Etapa 1. SYN** - O cliente iniciador requisita uma sessão de comunicação cliente-servidor com o servidor.
- **Etapa 2. ACK e SYN** - O servidor confirma a sessão de comunicação cliente-servidor e requisita uma sessão de comunicação de servidor-cliente.
- **Etapa 3. ACK** - O cliente iniciador confirma a sessão de comunicação de servidor-cliente.

![](https://github.com/brunoesm07/Cybersecurity_notes_and_summaries/blob/05d24f0db2e0006fecd5a59f416cc4cf4ac376cb/assets/Three-way%20handshake.png)

## O que é CTI? Cite uma aplicação em cada nível, estratégico, tático e operacional.

O Cyber Threat Intelligence é uma área de segurança cibernética que consiste no processo de coletar, analisar e compartilhar informações sobre ameaças digitais. Ela ganha valor quando é mesclada com informações relevantes da organização para fornecer um perfil do risco e de ameaça.

Fornece informações valiosas para a tomada de decisões estratégicas sobre segurança cibernética; identifica tendências e previne ameaças cibernéticas antes que elas causem danos; Monitoramento de redes e sistemas para identificar atividades suspeitas.

## Descreva de maneira detalhada como você iniciaria um ataque a um website.


## Descreva de maneira detalhada como você iniciaria um ataque a uma empresa prestes a fazer um IPO e aponte o que você buscaria nesse ataque.


## O que é um WAF? Qual sua principal função?

O Web Application Firewall é uma ferramenta que ajuda a proteger os aplicativos web, formando uma camada de proteção, que atua na camada 7 (camada de aplicação) do modelo OSI, ou seja, ele fica **localizado entre a aplicação e a internet**. Seu principal objetivo é fornecer segurança garantindo que determinadas ações de chamadas, sejam elas de entradas ou saídas, sejam barradas de acordo com as regras pré-definidas. 

O WAF funciona como um _proxy_ reverso que protege o servidor contra exposição, garantindo que nenhum cliente se comunique diretamente com esse, gerando os logs, realizando o balanceamento de carga e fazendo uma proteção a mais da rede. Ou seja, ele  **monitorara, filtra e bloqueia automaticamente o tráfego de dados maliciosos**

Os WAFs protegem as aplicações voltadas para a Internet contra ataques como resultado da inteligência integrada contra ameaças que agrega várias fontes e regras de detecção do Open Web Application Security Project (OWASP)

![](../assets/WAF.png)
(Fonte: CloudFlare)

Um WAF pode operar com uma lista de bloqueio protegendo contra ataques conhecidos. Chamamos essa forma de Modelo de Segurança Negativo. Em contrapartida há o Modelo de Segurança Positivo que opera com uma lista de permissões.

Existem 3 tipos de WAF:
- WAFs de rede -> Geralmente é um hardware instalado localmente.
- WAFs de host -> Baseado em hospedagem que pode ser integrado ao software e traz como vantagem uma maior possibilidade de personalização com um custo baixo.
- WAFs na nuvem -> Os WAFs hospedados na nuvem geralmente são administrados pelos provedores do serviço.

## O que é um SIEM? Qual sua principal função?

O Gerenciamento e Correlação de Eventos de Segurança - SIEM ( em inglês Security Information and Event Management) é a junção do gerenciamento de informações de segurança (SIM) com gerenciamento de eventos de segurança (SEM), formando em um software, um centro de gerenciamento de inteligência de ameaças, no qual coleta informações de várias fontes e em seguida identifica as anomalias de segurança usando protocolos baseados em regras para detectar e responder a atividades suspeitas.

Sua principal função é oferecer às organizações a visibilidade das atividades nas redes próprias de forma centralizada, para que possam responder rapidamente a possíveis ataques cibernéticos e atender aos requisitos de conformidade.

![](https://github.com/brunoesm07/Cybersecurity_notes_and_summaries/blob/88325b2ce4c324368f4c759b06bf8f3b29bdd5ca/assets/SIEM.png)
![](https://github.com/brunoesm07/Cybersecurity_notes_and_summaries/blob/88325b2ce4c324368f4c759b06bf8f3b29bdd5ca/assets/SIEM2.png)

Abaixo listo 5 dos principais SIEMs disponíveis no mercado:

1.  [Splunk](https://www.splunk.com/)
2.  IBM QRadar
3.  [Microsoft Sentinel](https://azure.microsoft.com/pt-br/products/microsoft-sentinel/?culture=pt-br&country=BR#overview)
4.  WAZUH
5.  Elastic Security

Onde buscar treinamento?

✅ Splunk 

- What is Splunk?: https://lnkd.in/g5RhvQJa
- Intro to Splunk: https://lnkd.in/gUBWviaa

>Há vários treinamentos na plataforma Splunk Education.

✅ QRadar

- **QRadar Learn Hub** - https://www.ibm.com/qradar/learn

✅ Microsoft Sentinel

- **Microsoft Learn: Introdução ao Microsoft Sentinel** - https://learn.microsoft.com/pt-br/training/modules/intro-to-azure-sentinel/

✅ WAZUH

- **Documentação** - https://documentation.wazuh.com/current/index.html


## Explique para que serve e como funciona uma DMZ.
 
Zona desmilitarizada ou DMZ é uma área intermediária entre a rede interna (confiável) e externa (não confiável). Sua função é manter os serviços que possuem acesso externo separados da rede local.

Uma rede DMZ fornece um buffer entre a Internet e a rede privada de uma organização. A DMZ é isolada por um gateway de segurança, como um firewall, que filtra o tráfego entre a DMZ e uma LAN. O servidor DMZ padrão é protegido por outro gateway de segurança que filtra o tráfego proveniente de redes externas.

Se um invasor conseguir penetrar no firewall externo e comprometer um sistema na DMZ, ele também terá que passar por um firewall interno antes de obter acesso a dados corporativos confidenciais.

##  O que é um purple team?
 
O Purple Team é uma abordagem de cibersegurança que integra as práticas e habilidades de ataque do Red Team com práticas e habilidades de defesa do Blue Team,  com o objetivo de melhorar a segurança de uma organização.

## Qual importância da conscientização de riscos cibernéticos para estratégia de segurança de uma organização?

A conscientização foca no principal e mais fraco elo da segurança da informação. De nada adianta investir grandes quantias de dinheiro e tempo em equipamentos de proteção se o funcionário que tem acesso "livre" dentro da empresa não tiver conhecimento sobre os riscos de certos comportamentos e ações.

Investir muito dinheiro em tecnologia não fará diferença se as pessoas dentro da empresa forem o elo mais fraco da segurança cibernética.

A conscientização de segurança deve ser um processo contínuo, já que novas ameaças e técnicas estão sempre surgindo.

## O que é DevSecOps? Qual sua importância para estratégia de segurança e negócio de uma organização?

Os conceitos DevOps e DevSecOps são sobre cultura, mudança de comportamento e visão de negócio, que visam eliminar as barreiras e aproximar as equipes de desenvolvimento de software. 

Com os avanços tecnológicos, as preocupações com segurança aumentaram devido ao crescimento de violações de segurança, forçando a indústria a valorizar mais os processos de desenvolvimento seguro, neste contexto surge a necessidade de incorporar na cultura DevOps o processo de segurança de aplicações, assim surge o termo DevSecOps.

No mercado existem diversas ferramentas que podem facilitar a implementação e manutenção de um processo de desenvolvimento seguro, porém as ferramentas sozinhas não são suficientes para garantir uma aplicação segura.


## O que é o Common Vulnerability Scoring System (CVSS)? Qual sua função?

O Common Vulnerability Scoring System (CVSS) é um método usado para fornecer uma medida qualitativa de gravidade. É adequado como um sistema de medição padrão para setores, organizações e governos que precisam de pontuações de gravidade de vulnerabilidade.

## O que são indicadores de comprometimento (IoC)? Cite exemplos reais

Indicadores de comprometimento (IOC) são evidências que indicam, com alta probabilidade, um acesso não autorizado a um sistema operacional(SO) ou elemento de rede (Host). Pode-se dizer que os IOC são evidências em um computador que sugere que a segurança da rede foi comprometida.

Endereços IPs, Domínios e Arquivos não habituais; atividades incomuns no tráfego de saída de rede;  processos incomuns consumindo muitos recursos em um host.


## O que é STRIDE? Qual sua utilidade?

A modelagem STRIDE é um acrônimo para seis categorias de ameaças: falsificação de identidade, adulteração de dados, ameaças de repúdio, divulgação de informações, negação de serviço e elevação de privilégios.

É utilizada para mapear um aplicativo em desenvolvimento com base em seus casos de uso exclusivos e lógica de negócios, auxiliando na identificação e eliminação de possíveis vulnerabilidades antes que uma única linha de código seja escrita.

## O que é CVE?

É uma lista de falhas de segurança de computador mantida pela MITRE e divulgadas publicamente. Quando alguém se refere a um CVE, significa uma falha de segurança à qual foi atribuído um número de ID CVE.

## O que é Zero Trust?

Zero Trust é uma estratégia de segurança de rede baseada na filosofia de que nenhuma pessoa ou dispositivo dentro ou fora da rede de uma organização é confiável e deve ter acesso para se conectar a sistemas de TI ou cargas de trabalho, a menos que seja explicitamente considerado necessário.

O modelo Zero Trust depende de autenticação e autorização fortes para cada dispositivo e pessoa antes que qualquer acesso ou transferência de dados ocorra em uma rede privada, independentemente de estarem dentro ou fora do perímetro da rede. 

## O que é NVD e CNNVD?

Banco de Dados Nacional de Vulnerabilidade (NVD) e Banco de Dados Nacional de Vulnerabilidade da China de Segurança da Informação (CNNVD)

São repositórios de dados de gerenciamento de vulnerabilidade e avaliação de risco baseados em padrões. O primeiro mantido pelos os EUA e o segundo pela China.

## O que é Service Level Agreement (SLA)?

Um contrato que estabelece os direitos e as obrigações entre contratado e contratante, visando alinhar expectativas e garantir o cumprimento da qualidade, da quantidade, dos prazos e de outros aspectos relevantes de um acordo.

## O que são TTPs?

Táticas, Técnicas e Procedimentos do Atacante

Os TTPs descrevem como os atacantes orquestram, executam e gerenciam seus ataques. Assim, são definidos como padrões de atividades ou métodos associados a um ator de ameaça específico ou grupo de atores de ameaça, focando no estilo e comportamento, e não nas ferramentas.

## O que é DLP e para que serve?

O Data Loss Prevention (DLP) é uma estratégia que visa garantir que as informações confidenciais permaneçam com segurança na rede corporativa.

Enquanto os sistemas tradicionais de cibersegurança são projetados para agir como uma barreira contra o acesso externo a dados confidenciais, a DLP está mais preocupada com as ameaças internas.

## O que é CI/CD?

CI/CD significa Integração Contínua/Entrega Contínua. É uma prática de desenvolvimento de software que visa automatizar e acelerar o processo de entrega de software. Ele enfatiza a criação de um pipeline de entrega automatizado, que permite que o código seja testado, construído e implantado rapidamente e com confiança.

## O que é SAST?

O SAST analisa o código-fonte do programa para identificar vulnerabilidades de segurança. Ele orienta os desenvolvedores a começarem a testar seus aplicativos nos estágios iniciais de desenvolvimento sem executar um componente funcional. Essa abordagem descobre as falhas de segurança do código-fonte do aplicativo antecipadamente e evita deixar os problemas de segurança para as fases de desenvolvimento posteriores.
