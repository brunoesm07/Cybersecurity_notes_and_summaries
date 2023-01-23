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

#### Ferramentas de Hacking Ético

