# Governança e Conformidade

A governança da segurança de TI determina quem está autorizado a tomar decisões sobre os riscos à segurança digital em uma empresa. Ela demonstra a responsabilidade e supervisiona para garantir que os riscos sejam adequadamente mitigados e que as estratégias de segurança estejam alinhadas aos objetivos comerciais da empresa e estejam em conformidade com as regulamentações.

## Políticas de segurança cibernética

Uma política de segurança digital é um documento de alto nível que descreve a visão de uma empresa sobre segurança digital, incluindo suas metas, necessidades, escopo e responsabilidades. É necessário estabelecer políticas de segurança claras e detalhadas de que todos os funcionários estejam cientes.

Alguns exemplos de políticas são: 

**Identificação e Autenticação** - Especifica quem deve ter acesso aos recursos de rede e quais procedimentos de verificação estão em vigor para facilitar isso.

**Senhas** - Define os requisitos mínimos de senha, como número e tipo de caracteres usados, e a frequência com que eles precisam ser alterados.

**Utilização aceitável** - Destaca um conjunto de regras que determinam o acesso e o uso dos recursos de rede. Ela também pode definir as consequências das violações de política.

**Tratamento de incidentes** - Fornece orientação sobre como relatar e responder a incidentes relacionados à segurança em uma empresa.

**Dados** - Define regras mensuráveis para o processamento de dados dentro de uma empresa, como especificar onde os dados são armazenados, como os dados são classificados (alto, médio, baixo, confidencial, público ou privado) e como os dados são tratados e descartados.

## Cibercrime

O crime digital se divide em três categorias:

1. **O crime por computador** é onde um computador é alvo de atividades criminosas. Por exemplo, ataques de malware, invasão ou ataques de negação de serviço.
2. **O crime assistido por computador** ocorre quando um computador é usado para cometer um crime, como roubo ou fraude.
3. **O crime incidente no computador** é quando um computador fornece informações que são incidentes a um crime real. Por exemplo, um computador é usado para armazenar vídeos baixados ilegalmente, e não a ferramenta real usada para cometer o crime.

## ISO / IEC 27000

A ISO / IEC 27000 é uma série de padrões de segurança da informação ou melhores práticas para ajudar as empresas a melhorar a segurança da informação. 

Doze domínios independentes representam os componentes do padrão ISO 27000. Esses doze domínios fornecem a base para o desenvolvimento de padrões de segurança e práticas eficazes de gerenciamento de segurança nas empresas, além de ajudar a facilitar a comunicação entre as empresas.

1) Avaliação de riscos
2) Política de segurança
3) Organização de segurança da informação
4) Gerenciamento de ativos
5) Segurança de recursos humanos
6) Segurança física e ambiental
7) Gerenciamento de operações e comunicações
8) Aquisição, desenvolvimento e manutenção de sistemas de informação
9) Controle de acesso
10) Gerenciamento de incidentes de segurança da informação
11) Gerenciamento de continuidade de negócios
12) Conformidade

A estrutura do modelo de segurança cibernética ISO é diferente do modelo OSI, pois usa domínios, e não camadas, para descrever as categorias de segurança. É um modelo não hierárquico, em que cada domínio tem uma relação direta com os outros domínios.

Para usar a estrutura de forma eficiente, a empresa deve limitar quais domínios, objetivos de controle e aplicar a seu ambiente e a suas operações. A maioria das empresas faz isso produzindo uma declaração de aplicabilidade (SOA) que permite adaptar os objetivos e controles de controle disponíveis para melhor atender às prioridades de **confidencialidade**, **integridade** e **disponibilidade.**


### CIS Controls

O Center for Internet Security (CIS) desenvolveu um conjunto de controles de segurança essenciais para ajudar empresas com diferentes níveis de recursos e conhecimentos à disposição a melhorar suas defesas digitais.

**Controles básicos**

As empresas com recursos limitados e especialistas em segurança digital disponíveis devem implementar:

- Inventário e controle de ativos de hardware
- Inventário e controle de ativos de software
- gerenciamento de vulnerabilidade
- Uso controlado de privilégios administrativos
- Configurações seguras para hardware e software
- Manutenção, monitoramento e análise de registros de auditoria

**Controles fundamentais**

As empresas com recursos moderados e experiência em segurança digital disponíveis devem implementar os controles básicos e:

- Proteção de e-mail e navegador da Web
- Defesa contra malware
- Limitação e controle de portas de rede, protocolos e serviços
- Recursos de recuperação de desastres
- Configurações seguras para dispositivos de rede
- Defesa dos limites
- Proteção de dados
- Acesso controlado com base no princípio da "necessidade de saber"
- Configurações de controle de acesso sem fio
- Monitoramento e controle de energia

**Controles organizacionais**

As empresas com recursos significativos e a experiência em segurança digital disponíveis devem implementar os controles básicos e fundamentais, bem como:

- Conscientização e treinamento em segurança
- software de aplicativos
- Gerenciamento e resposta a incidentes
- Testes de penetração e exercícios em equipe vermelhos (exercícios de ataque simulados para avaliar os recursos de segurança de uma empresa)

### Cloud Security Alliance (CSA)

A Cloud Security Alliance (CSA) fornece orientação de segurança para qualquer empresa que usa computação em nuvem ou deseja avaliar o risco de segurança geral de um provedor de nuvem.

A matriz de controles de nuvem (CCM) é uma estrutura de controle de segurança digital que mapeia os controles de segurança específicos da nuvem para atender aos principais padrões, melhores práticas e regulamentações. Ela é composta por 197 objetivos de controle, estruturados em 17 domínios, que abrangem todos os aspectos da tecnologia de nuvem, incluindo governança e gerenciamento de riscos, recursos humanos e segurança móvel. 

O CCM é considerado um padrão de fato para garantia de segurança e conformidade da nuvem.


# Teste de Segurança de Rede

## Scanners de vulnerabilidade

Um scanner de vulnerabilidades avalia computadores, sistemas de computador, redes ou aplicações, em busca de pontos fracos. Procura os seguintes tipos de vulnerabilidades:

- Uso de senhas padrão ou senhas comuns
- Patches não instalados
- Portas abertas
- Erro de configuração de software e de sistemas operacionais
- Endereços IP ativos, incluindo dispositivos inesperados conectados

Os scanners de vulnerabilidade mais usados ​​no mercado incluem Nessus, Retina, Core Impact e GFI LanGuard.

### Utilitários de diagnóstico de linha de comando

Há várias ferramentas de linha de comando que podem ser usadas para avaliar a posição de segurança de uma empresa.

- **ifconfig** exibe as configurações de TCP/IP (endereço IP, máscara de sub-rede, gateway padrão, informações de DNS e MAC.
- **o ping** testa a conectividade de rede enviando uma solicitação de ICMP para um host e determina se uma rota está disponível para um host.
- **O arp** fornece uma tabela que mapeia endereços MAC conhecidos para o endereço IP associado e é uma maneira rápida de encontrar o endereço MAC de um dispositivo final.
- **O traceroute** rastreia a rota que um pacote leva um destino e registra os saltos até ao longo do caminho, ajudando a localizar onde um pacote está sendo desligado.
- **O nslookup** consulta um servidor DNS para ajudar a solucionar um banco de dados DNS ( _dig_ é o equivalente em Mac/Linux).
- **O netstat** exibe todas as portas que um computador está ouvindo e pode determinar as conexões ativas.
- **O nbtstat** ajuda a solucionar problemas de resolução de nomes do NetBIOS em um sistema Windows.
- **O nmap** é usado em auditorias de segurança. Ele localiza hosts de rede, detecta sistemas operacionais e identifica serviços.
- **O netcat** coleta informações de conexões de rede TCP e UDP e pode ser usado para varredura de portas, monitoramento, captura de banner e cópia de arquivos.
- **A hping** monta e analisa pacotes e é usado para varredura de portas, descoberta de caminho, impressão digital do SO e testes de firewall.

### Automação de segurança

**SIEM**

Os Sistemas de Gerenciamento de Informações e Eventos de Segurança (SIEM) usam coletores de log para agregar dados de log de fontes como dispositivos de segurança, dispositivos de rede, servidores e aplicações. O SIEM identifica desvios da norma e, em seguida, executa a ação apropriada.

Os objetivos de um sistema SIEM para monitoramento de segurança são:

- Ameaças internas e externas
- Monitorar a atividade e o uso de recursos
- Realizar relatório de conformidade para auditorias
- Resposta a incidentes

**SOAR** 

As ferramentas de orquestração, automação e resposta de segurança (SOAR) permitem que uma empresa colete dados sobre ameaças à segurança de várias fontes e responda a eventos de nível inferior sem intervenção humana. O SOAR tem três recursos importantes:

- Gerenciamento de ameaças e vulnerabilidades
- Operações de segurança e resposta a incidentes
- Operação de segurança

Uma empresa pode integrar o SOAR em sua solução SIEM.

## Segurança das Operações

A segurança das operações se preocupa com as práticas iniciadas para implantar e depois manter um sistema seguro. Ela começa com o processo de planejamento e implementação de uma rede. Durante essas fases, a equipe de operações analisa projetos, identifica riscos e vulnerabilidades e faz as necessárias. As tarefas operacionais reais começam depois que a rede é configurada e incluem a manutenção contínua do ambiente.

A eficácia de uma solução de segurança de operações pode ser testada sem esperar que uma ameaça real seja provocada. O teste de segurança de rede é executado em uma rede para garantir que todas as implementações de segurança estejam operando conforme o esperado.

**Tipos de testes de rede**

- **Teste de penetração -** Testes de penetração de rede, ou testes de penetração, simulam ataques de fontes maliciosas. O objetivo é determinar a viabilidade de um ataque e as possíveis consequências se um ocorrer. Alguns testes de penetração podem envolver o acesso às instalações de um cliente e o uso de habilidades de engenharia social para testar sua postura geral de segurança.

- **Varredura de rede** - inclui software que pode fazer ping em computadores, verificar portas TCP de escuta e exibir quais tipos de recursos estão disponíveis na rede. Alguns softwares de varredura também podem detectar nomes de usuários, grupos e recursos compartilhados. Os administradores de rede podem usar essas informações para fortalecer suas redes.

- **Varredura de vulnerabilidade** - Inclui software que pode detectar fraquezas potenciais nos sistemas testados. Esses pontos falhos podem incluir configuração incorreta, senhas em branco ou padrão ou alvos potenciais para ataques DoS. 

- **Cracking de senha** - Isso inclui software usado para testar e detectar senhas fracas que devem ser alteradas. As políticas de senha devem incluir diretrizes para evitar senhas fracas.

- **Revisão de log -** os administradores de sistema devem revisar os logs de segurança para identificar ameaças de segurança em potencial. O software de filtragem para varrer arquivos de log longos deve ser usado para ajudar a descobrir atividades anormais a serem investigadas.

- **Verificadores de integridade -** um sistema de verificação de integridade detectado e relatório sobre mudanças no sistema. A maior parte do monitoramento concentra-se no sistema de arquivos. No entanto, alguns sistemas de verificação podem relatar atividades de login e logout.

- **Detecção de vírus** - O software de detecção de vírus ou antimalware deve ser usado para identificar e remover vírus de computador e outros malwares.

**Ferramentas de teste de rede**

- **Nmap / zenmap -** é usado para descobrir computadores e seus serviços em uma rede, criando, portanto, um mapa da rede.
- **SuperScan**- Este software de varredura de porta é projetado para detectar as portas Abrir TCP e UDP, determine quais serviços estão sendo executados nessas portas e execute consultas, como pesquisas Whois, Ping, Traceroute e HostName.
- **Siem (gerenciamento de eventos de informação de segurança)** - Esta é uma tecnologia usada em organizações corporativas para fornecer relatórios em tempo real e análise de longo prazo de eventos de segurança.
- **GFI Languard** - Este é um scanner de rede e segurança que detecta vulnerabilidades.
- **TripWire**- Esta ferramenta avalia e valida configurações de TI contra políticas internas, padrões de conformidade e as melhores práticas de segurança.
- **Nessus** - Este é um software de varredura de vulnerabilidade, com foco em acesso remoto, miscigurações e DOS contra a pilha TCP / IP.
- **L0phtcrack**- Este é um aplicativo de auditoria e recuperação de senha.
- **Metaploit**- Esta ferramenta fornece informações sobre vulnerabilidades e ajuda em testes de penetração e desenvolvimento de assinaturas de IDs.

## Teste de penetração

O teste de penetração (pentesting) é um método de testar áreas de fraquezas em sistemas usando várias técnicas maliciosas. Um teste de penetração simula os métodos que um invasor usaria para obter acesso não autorizado a uma rede e comprometer os sistemas, além de permitir que uma empresa entenda como toleraria um ataque real.

- **O teste** **de caixa preta** - no teste de caixa preta o especialista não tem conhecimento do funcionamento interno do sistema e tenta atacá-lo do ponto de vista de um usuário regular.
- **O teste de caixa cinza** - é uma combinação de caixa preta e teste de caixa branca. O especialista terá algum conhecimento limitado sobre o sistema, então é um ambiente parcialmente conhecido, o que dá alguma vantagem a essas tentativas de invasão.
- **O teste de caixa branca** - é um ambiente conhecido quando eles tentam invadi-lo, emulando um ataque mal-intencionado por alguém de dentro ou por alguém que tenha conseguido obter essas informações antecipadamente, na fase de reconhecimento.

**Fases**

1) Planejamento
2) Descoberta
3) Ataque
4) Geração de relatórios

# Avaliação de vulnerabilidade de endpoint

## Perfil de rede

Para detectar incidentes de segurança graves, é importante compreender, caracterizar e analisar informações sobre o funcionamento normal da rede. A criação de perfis de rede e dispositivo pode fornecer uma linha de base estatística que serve como ponto de referência. Desvios inexplicáveis em relação à linha de base podem indicar um compromisso.

Elementos importantes do perfil de rede incluem duração da sessão, taxa de transferência total, portas usadas e espaço de endereço de ativos críticos.

Ferramentas como NetFlow e Wireshark podem ser usadas para caracterizar características normais de tráfego de rede.

## Sistema de Pontuação de Vulnerabilidade Comum (CVSS)

O Common Vulnerability Scoring System (CVSS) é uma ferramenta de avaliação de risco projetada para transmitir os atributos comuns e a gravidade das vulnerabilidades em sistemas de hardware e software de computador.

O CVSS usa três grupos de métricas para avaliar a vulnerabilidade.

- Grupo de métricas base - características de uma vulnerabilidade que são constantes ao longo do tempo e em contextos.
- Grupo métrico temporal - Isso mede as características de uma vulnerabilidade que pode mudar ao longo do tempo, mas não em ambientes de usuário.
- Grupo métrico ambiental - mede os aspectos de uma vulnerabilidade que estão enraizados no ambiente de uma organização específica.

## Vulnerabilidades e exposições comuns (CVE)

Este é um dicionário de nomes comuns, na forma de identificadores CVE, para vulnerabilidades conhecidas de segurança cibernética. O identificador CVE fornece uma maneira padrão de pesquisar uma referência a vulnerabilidades.

## Gerenciamento seguro de dispositivos

**Gerenciamento de riscos**

Envolve a seleção e especificação de controles de segurança para uma organização. Há quatro maneiras potenciais de responder aos riscos, evitar riscos significa interromper a atividade vulnerável, o sistema ou o serviço porque o risco é muito alto. Redução do risco significa tomar medidas para mitigar o risco, a fim de limitar o seu impacto. Partilha de riscos significa terceirização da responsabilidade pelo risco ou utilização de seguro para cobrir danos causados pelo risco. Retenção de riscos significa aceitar o risco e não tomar nenhuma ação.

**Gestão de Vulnerabilidade**s

De acordo com o NIST, o gerenciamento de vulnerabilidades é uma prática de segurança projetada para impedir proativamente a exploração de vulnerabilidades de TI existentes em uma organização.

O gerenciamento de vulnerabilidades requer um meio robusto de identificar vulnerabilidades com base em boletins de segurança do fornecedor e em outros sistemas de informação, como o CVE.

O ciclo de vida do gerenciamento de vulnerabilidades envolve seis etapas: descobrir, priorizar ativos, avaliar, relatar, corrigir e verificar.

**Gerenciamento de ativos**

O gerenciamento de ativos envolve a implementação de sistemas que controlam a localização e a configuração de dispositivos e software em rede em uma empresa. O gerenciamento de ativos não apenas rastreia ativos corporativos e outros dispositivos autorizados, mas também pode ser usado para identificar dispositivos que não estão autorizados na rede.

**Gerenciamento de configurações**

O gerenciamento de configuração aborda o inventário e o controle das configurações de hardware e software dos sistemas.

Com o advento dos data centers em nuvem e da virtualização, o gerenciamento de vários servidores apresenta desafios especiais. Ferramentas como Puppet, Chef, Ansible e SaltStack permitem o gerenciamento eficiente de servidores usados na computação baseada em nuvem.

# Gerenciamento de riscos e controles de segurança

## Gerenciamento de riscos

Risco é a probabilidade de perda devido a uma ameaça - um ato mal-intencionado ou evento inesperado - que danifica os sistemas de informação ou os ativos da empresa.

O impacto no risco é o dano causado por um evento que causa perda de ativos ou interrupção do (s) serviço (s). O objetivo do gerenciamento de riscos é reduzir essas ameaças a um nível aceitável e implementar controles para manter esse nível.

O gerenciamento de riscos é um processo formal que mede o impacto de uma ameaça e o custo para implementar controles ou contramedidas para atenuar essa ameaça.

O risco não pode ser eliminado completamente, mas ainda pode ser gerenciado para um nível aceitável.

## Tipos de fonte de ameaça

A avaliação de ameaças é a base para a avaliação de riscos. Uma ameaça é o potencial que uma vulnerabilidade será identificada e explorada, enquanto um vetor de ameaças é o caminho que um invasor utiliza para afetar o alvo.

Os tipos de fonte de ameaça são categorizados da seguinte forma e podem ser internos ou externos.

- **Adversarial:**  ameaças de indivíduos, grupos, organizações ou nações.
- **Acidental:**  ações que ocorrem sem uma má intenção.
- **Estrutural:**  falhas de equipamento e software.
- **Ambiental:**  desastres externos que podem ser naturais ou causados pelo homem, como incêndios e inundações.

## Análise de Risco

Análise de risco é o processo de analisar os perigos representados por eventos naturais e provocados por humanos aos ativos de uma empresa. Um usuário realiza uma identificação de ativo para ajudar a determinar quais ativos serão protegidos.

Uma análise de risco tem quatro objetivos:

1. Identificar ativos e seu valor
2. Identificar vulnerabilidades e ameaças
3. Quantificar a probabilidade e o impacto das ameaças identificadas
4. Equilibrar o impacto da ameaça com relação ao custo da contramedida

### Quantitativa

Uma análise quantitativa atribui números para o processo de análise de risco. 

O **valor do ativo** é o custo de reposição do ativo. O valor de um ativo pode ser medido também pela receita adquirida com o uso do ativo.

O **fator de exposição (EF)** é um valor subjetivo expresso como uma porcentagem do servidor de arquivos perdido devido a uma ameaça específica. Se ocorrer uma perda total, o EF é igual a 1.0 (100%).

A **ARO ( annualized rate of occurrence, Taxa anualizada de ocorrência)** é a probabilidade de uma perda ocorrer durante o ano. Uma ARO pode ser maior que 100%, se uma perda puder ocorrer mais de uma vez por ano.

O cálculo da **ALE (annual loss expectancy, expectativa de perda anual)** dá à gerência uma noção de quanto deverá gastar para proteger o ativo.

### Qualitativa

A análise qualitativa de riscos usa opiniões e cenários que descrevem a probabilidade de uma ameaça contra seu impacto.

Uma matriz de riscos é uma ferramenta que ajuda a priorizar riscos para determinar para quais organizações a empresa precisa desenvolver uma resposta. Os resultados podem ser classificados e usados como um guia para determinar se a empresa executa alguma ação.

## Controles de segurança

Os controles de segurança são proteções ou contramedidas que uma empresa implementa para evitar, detectar, neutralizar ou minimizar os riscos de segurança dos ativos da empresa.

**Controles administrativos**

Os controles administrativos consistem em procedimentos e políticas que uma empresa implementa ao lidar com informações confidenciais. Esses controles determinam como as pessoas agem.

**Controles técnicos.**

Os controles técnicos envolvem hardware e / ou software implementado para gerenciar riscos e oferecer proteção.

**Controles físicos**

Os controles físicos são mecanismos como cercas e bloqueios implantados para proteger sistemas, instalações, pessoal e recursos. Os controles físicos separam fisicamente pessoas ou outras ameaças dos sistemas.

### Auditoria de controles e conformidade

O Center for Internet Security (CIS) criou um mapeamento de seus 18 controles de segurança essenciais para algumas das estruturas de conformidade comuns. Isso fornece orientações úteis para profissionais de segurança que estão trabalhando para criar e manter a conformidade com as estruturas necessárias.

# Análise forense digital e análise e resposta a incidentes

## Computação forense digital

A fim de proteger a organização e prevenir o cibercrime, é necessário identificar os atores da ameaça, denunciá-los às autoridades competentes e fornecer provas para apoiar a acusação.

A perícia digital é a recuperação e investigação de informações encontradas em dispositivos digitais no que diz respeito a atividades criminosas. Indicadores de comprometimento são a evidência de que ocorreu um incidente de segurança cibernética.

### Tipos de evidencias

Em processos judiciais, as provas são geralmente classificadas como diretas ou indiretas. **Provas diretas** são provas que estavam indiscutivelmente na posse do acusado, ou são testemunhas oculares de alguém que observou diretamente o comportamento criminoso.

As provas são ainda classificadas como:

- **Melhor evidencia** - Esta é evidência que está em seu estado original. Essas evidências podem ser dispositivos de armazenamento usados por um acusado, ou arquivos de arquivos que podem ser comprovados como inalterados.

- **Provas corroborantes** - Esta é uma evidência que suporta uma afirmação que é desenvolvida a partir da melhor evidência.

- **Provas indiretas** - Esta é a evidência que, em combinação com outros fatos, estabelece uma hipótese. Isso também é conhecido como evidência circunstancial. Por exemplo, a evidência de que um indivíduo cometeu crimes semelhantes pode apoiar a afirmação de que a pessoa cometeu o crime de que é acusado.

### Coleta de evidências

**Prioridade de coleta**

![[coleta de evidencias.png]]

Um exemplo da ordem de coleta de evidências mais volátil a menos volátil é o seguinte:

- Registros de memória, caches
- Tabela de roteamento, cache ARP, tabela de processo, estatísticas de kernel, RAM
- Sistemas de arquivos temporários
- Meios não voláteis, fixos e removíveis
- Dados de registro e monitoramento remotos
- Interconexões físicas e topologias
- Mídia de arquivamento, fita ou outros backups

## Cyber Kill Chain

A Cyber Kill Chain foi desenvolvida pela Lockheed Martin para identificar e prevenir intrusões cibernéticas. Existem sete etapas para o Cyber Kill Chain.

![[cyber kill chain.png]]

### Reconhecimento

Reconhecimento é quando o ator de ameaça realiza pesquisas, coleta inteligência e seleciona alvos. Todas as informações obtidas pelo agente da ameaça são revisadas para determinar sua importância e se revelam possíveis vias adicionais de ataque.

### Armamento

O objetivo desta etapa é usar as informações do reconhecimento para desenvolver uma arma contra sistemas específicos ou indivíduos na organização. O agente de ameaça precisa analisar quais ataques estão disponíveis para as vulnerabilidades que ele descobriu.

### Entrega

Durante esta etapa, a arma é transmitida ao alvo usando um vetor de entrega. Isso pode ser através do uso de um site, mídia USB removível ou um anexo de e-mail. Se a arma não for entregue, o ataque não terá sucesso.

### Exploração

Depois que a arma foi entregue, o ator de ameaça a usa para quebrar a vulnerabilidade e ganhar o controle do alvo.

### Instalação

Esta etapa é onde o ator de ameaça estabelece um backdoor para o sistema para permitir o acesso contínuo ao alvo. Para preservar esse backdoor, é importante que o acesso remoto não alerte analistas ou usuários de segurança cibernética.

### Comando e Controle

Nesta etapa, o objetivo é estabelecer comando e controle (CNC ou C2) com o sistema de destino. Os hosts comprometidos geralmente se sinalizam da rede para um controlador na Internet. Isso ocorre porque a maioria dos malwares requer interação manual para exfiltrar dados da rede. Os canais CNC são usados pelo ator de ameaças para emitir comandos para o software que eles instalaram no destino.

### Ações e Objetivos

O passo final da Cyber Kill Chain é onde o ator de ameaça alcança seu objetivo original. Isso pode ser roubo de dados, realização de um ataque DDoS ou uso da rede comprometida para criar e enviar spam ou minerar Bitcoin. Neste ponto, o ator de ameaça está profundamente enraizado nos sistemas da organização, escondendo seus movimentos e cobrindo seus rastros.

## O Modelo Diamond de análise de intrusão

O Modelo Diamond de Análise de Intrusão é composto por quatro partes. No Modelo Diamond, um evento é uma atividade limitada ao tempo, que é restrita a uma etapa específica em que um adversário usa uma capacidade sobre a infraestrutura para atacar uma vítima e alcançar um resultado específico.

### Adversários

São responsáveis pela intrusão.

### Recursos

Ferramenta ou técnica que o adversário usa para atacar a vítima.

### Infraestrutura

Caminho ou caminhos de rede que os adversários usam para estabelecer e manter o comando e o controle sobre suas capacidades.

### Vítima

Alvo do ataque. No entanto, uma vítima pode ser o alvo inicialmente e, em seguida, usada como parte da infra-estrutura para lançar outros ataques.

## Resposta a incidentes

A resposta a incidentes envolve os métodos, políticas e procedimentos usados por uma organização para responder a um ataque cibernético. Os objetivos da resposta a incidentes são limitar o impacto do ataque, avaliar os danos causados e implementar procedimentos de recuperação.

É  essencial que as organizações criem e mantenham planos detalhados de resposta a incidentes e designem pessoal responsável pela execução de todos os aspectos desse plano.

### Ciclo de vida de resposta a incidentes NIST

**Preparação**

Os membros do CSIRT são treinados para responder a um incidente. Os membros do CSIRT devem desenvolver continuamente o conhecimento das ameaças emergentes.

**Detecção e análise**

Através do monitoramento contínuo, o CSIRT identifica, analisa e valida rapidamente um incidente.

**Contenção, erradicação e recuperação**

O CSIRT implementa procedimentos para conter a ameaça, erradicar o impacto nos ativos organizacionais e usar backups para restaurar dados e software. Esta fase pode voltar à detecção e análise para reunir mais informações, ou para expandir o escopo da investigação.

**Atividades pós-incidente**

O CSIRT então documenta como o incidente foi tratado, recomenda alterações para resposta futura e especifica como evitar uma repetição.

## Recuperação de desastres

### Plano de recuperação de desastres

Uma empresa coloca seu **DRP (Disaster recovery plan, Plano de recuperação de desastres)** em ação enquanto o desastre está em curso e os funcionários estão lutando para garantir que sistemas essenciais estejam on-line.

O DRP inclui as atividades que a empresa realiza para avaliar, recuperar, reparar e restaurar instalações ou ativos danificados.

### Planejamento de Continuidade de Negócios

Um plano de continuidade dos negócios é um plano mais amplo que um DRP, pois inclui levar sistemas essenciais para outro local, enquanto o reparo da instalação original está em andamento.

A criação de um plano de continuidade dos negócios começa com a realização de uma análise de impacto nos negócios (BIA) para identificar processos comerciais importantes, recursos e relacionamentos entre sistemas.

> Os controles de continuidade dos negócios são mais do que apenas backup de dados e fornecimento de hardware redundante. As empresas precisam de funcionários para configurar e operar corretamente os sistemas. Os dados podem ser inúteis, até que forneçam informações.

