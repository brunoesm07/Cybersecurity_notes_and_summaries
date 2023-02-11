# Introdução à Threat Informed Defense

### Threat Informed Defense. 

A defesa informada contra ameaças se baseia em uma base sólida de segurança cibernética corporativa. É uma estratégia e abordagem que uma organização implementa, além de controlar sua higiene cibernética básica.

Uma Threat Informed Defense é uma abordagem proativa para segurança cibernética que utiliza três elementos para fornecer um ciclo de feedback em evolução para sua equipe de segurança: 

- Análise de inteligência de ameaças cibernéticas => A direção com base no comportamento do adversário no mundo real fornece orientação ideal para prosseguir com sua estratégia de segurança.
- Engajamento defensivo da ameaça => Os defensores que se colocam na mente do adversário têm um entendimento sistemático das táticas, técnicas e procedimentos (TTPs) que o adversário está empregando e, finalmente, um melhor entendimento de como os adversários agem.
- Compartilhamento e colaboração focados => O adversário é global, ágil e evasivo. A maneira mais rápida de superar o adversário é compartilhando conhecimento.

A Threat Intelligence Analysis está pegando dados de inteligência existentes, como TTPs, hashes de malware ou nomes de domínio, e aplicando inteligência humana para fortalecer as defesas cibernéticas. Isso melhora as formas de antecipar, prevenir, detectar e responder a ataques cibernéticos.

#### CRITS

O Collaborative Research Into Threats (CRITS) é um repositório de malware e ameaças de código aberto que utiliza outro software de código aberto para criar uma ferramenta unificada para analistas e especialistas em segurança envolvidos na defesa contra ameaças.

O CRITS faz várias coisas que auxiliam na análise de inteligência, como:

-   Coletar e arquivar artefatos de ataque
-   Associar artefatos com estágios do ciclo de vida do ataque cibernético
-   Realização de engenharia reversa de malware
-   Rastreamento de influências ambientais
-   Conectar tudo isso para moldar e priorizar defesas e reagir a incidentes

#### CTID

Grupos como o  [Center for Threat Informed Defense (CTID)](https://mitre-engenuity.org/center-for-threat-informed-defense/) do MITRE  reúnem equipes de segurança sofisticadas de organizações líderes em todo o mundo para expandir a compreensão global dos comportamentos adversários. Eles conseguem isso criando foco, colaboração e coordenação para acelerar a inovação na defesa informada contra ameaças, com base na estrutura MITRE ATT&CK.

As áreas de pesquisa do CTID incluem:  

- Avanço na compreensão global do tradecraft adversário, por exemplo, expandir ATT&CK em novos domínios de tecnologia, como nuvem.
- Medir o comportamento do adversário em evolução, por exemplo, estabelecer uma lista “mais procurada” de técnicas adversárias.
- Permitir a avaliação contínua de nossas defesas, por exemplo, desenvolver, compartilhar e automatizar manuais de emulação de adversários.
- Identificar, catalisar continuamente o desenvolvimento e/ou pesquisar novas maneiras de impedir as técnicas de ATT&CK em Proteger, Detectar e Responder Todos os resultados de P&D serão disponibilizados globalmente para maximizar o impacto.

# MITRE ATT&CK Básico

Adversarial Tactics, Techniques, and Common Knowledge (ATT&CK)

O MITRE é conhecido em mais do que apenas no mundo cibernético. Eles também trabalham em defesa e inteligência, aviação, sistemas civis, segurança interna, judiciário e saúde. Todos esses recursos, incluindo segurança cibernética, são financiados pelo governo federal americano e trabalham para resolver alguns dos maiores problemas por meio de pesquisa e desenvolvimento independentes.

### Táticas, Técnicas e Procedimentos

-   As táticas são os objetivos técnicos do adversário.
-   As técnicas são como esses objetivos são alcançados.
-   Procedimentos são implementações específicas de técnicas.

O [MITRE ATT&CK Framework](https://attack.mitre.org/) é uma coleção de técnicas usadas pelos invasores durante uma violação. A Matriz ATT&CK divide as técnicas nas seguintes táticas:  

- **Reconhecimento** - O reconhecimento consiste em técnicas que envolvem adversários coletando informações de forma ativa ou passiva que podem ser usadas para dar suporte ao direcionamento.

- **Desenvolvimento de Recursos** - O Desenvolvimento de Recursos consiste em técnicas que envolvem adversários criando, comprando ou comprometendo/roubando recursos que podem ser usados ​​para dar suporte ao direcionamento.

- **Acesso Inicial**  - Técnicas que usam vários vetores de entrada para ganhar uma posição. Os pontos de apoio obtidos por meio do acesso inicial podem permitir acesso contínuo, como contas válidas e uso de serviços remotos externos, ou podem ser de uso limitado devido à alteração de senhas.

- **Execução**  - Técnicas que resultam na execução de código controlado pelo adversário em um sistema local ou remoto. As técnicas que executam códigos maliciosos geralmente são combinadas com técnicas de todas as outras táticas para atingir objetivos mais amplos.

- **Persistência**  - Técnicas que os adversários usam para manter o acesso aos sistemas entre reinicializações, alterações de credenciais e outras interrupções que podem interromper o acesso.  

- **Escalação de privilégios**  - Técnicas que os adversários usam para obter permissões de nível superior em um sistema ou rede. As técnicas geralmente se sobrepõem às técnicas de Persistência.

- **Evasão de defesa**  - Técnicas que os adversários usam para evitar a detecção ao longo de seu comprometimento.

- **Acesso a credenciais**  - Técnicas para roubar credenciais, como nomes de contas e senhas.

- **Descoberta**  - Técnicas que um adversário usa para obter conhecimento sobre o sistema e a rede interna. As ferramentas nativas do sistema operacional são frequentemente usadas para esse objetivo de coleta de informações pós-compromisso.  

- **Movimento Lateral**  - Técnicas que os adversários usam para entrar e controlar sistemas remotos em uma rede.

- **Coleta**  - Técnicas que os adversários usam para coletar informações e as fontes das quais as informações são coletadas que são relevantes para cumprir os objetivos do adversário.

- **Comando e Controle** - Técnicas que os adversários usam para se comunicar com sistemas sob seu controle dentro de uma rede de vítimas.

- **Exfiltração**  - Técnicas que os adversários usam para roubar dados de sua rede.

- **Impacto** - Técnicas que os adversários usam para interromper a disponibilidade ou comprometer a integridade, manipulando os processos de negócios e operações.

# Introdução à Operacionalização do ATT&CK

### Inteligência de Ameaças

Uma das maneiras mais fáceis de operacionalizar a estrutura ATT&CK é escolher um grupo de ameaças com o qual você se preocupa e mapear suas técnicas na Matriz Enterprise ATT&CK. 

##### Grupos de Ameaças

A  [página de grupos de ameaças](https://attack.mitre.org/groups/)  no site MITRE ATT&CK fornece uma lista de todos os grupos de ameaças avançadas que o MITRE rastreou. Para cada grupo de ameaças, clique para obter mais detalhes. Alguns dos detalhes listados para cada agente de ameaça incluem táticas e softwares usados ​​e referências a mais pesquisas.

**Instruções para atividade de laboratório de grupos de ameaças**

1.  Acesse  [https://attack.mitre.org/groups](https://attack.mitre.org/groups) .
2.  Encontre o grupo de ameaças APT29 na página e clique na página APT29.
3.  Leia a descrição do APT29 e as Descrições do Grupo Associado.
4.  Encontre a seção de software da página do grupo APT29 e procure por software que se encaixe na técnica de despejo de credenciais do sistema operacional.
5.  Clique em um dos softwares que corresponde à técnica (em nosso exemplo, usamos o Mimikatz).
6.  Leia a descrição do software que você escolheu.
7.  Abra um ou dois links na seção de recursos da página para entender melhor como o software funciona.

##### ATT&CK Navigator

O MITRE [ATT&CK Navigator](https://mitre-attack.github.io/attack-navigator/) é projetado para fornecer navegação básica e anotação da matriz ATT&CK. A ferramenta é utilizada como uma forma simples de visualizar a matriz ATT&CK e facilitar seu uso. Um dos muitos recursos úteis do ATT&CK Navigator é usar os filtros fornecidos para destacar as técnicas usadas por um determinado grupo de ameaças.

**Instruções de atividade do laboratório ATT&CK Navigator**

1.  Na página do software que você pesquisou no site do MITRE ATT&CK, clique (ou clique duas vezes) no botão  **ATT&CK NAVIGATOR LAYERS**  .
2.  Clique em  _visualizar_ .
3.  Na página do Navegador gerada, passe o mouse sobre as técnicas e subtécnicas destacadas para ler os comentários relacionados ao software.

##### Mapeamento Intel Organizacional para ATT&CK

Se você tiver uma organização mais madura, pode haver analistas de ameaças que revisam regularmente as informações sobre seus adversários. Se você tiver acesso a relatórios de incidentes anteriores, comece a mapear as táticas identificadas no relatório para a matriz MITRE ATT&CK. Blocos de parágrafos podem parecer impossíveis de mapear de volta para ATT&CK, então MITRE ofereceu algumas sugestões para fazer isso.  

1.  Entenda o ATT&CK — Familiarize-se com a estrutura geral do ATT&CK:  
    1.  Táticas - Os objetivos técnicos do adversário
    2.  Técnicas - Como esses objetivos são alcançados
    3.  Procedimentos - Implementações específicas de técnicas

2. Encontre o comportamento—Pense na ação do adversário de uma forma mais ampla do que apenas o indicador atômico (como um endereço IP) usado. Por exemplo, o malware no relatório acima “estabelece uma conexão SOCKS5”. O ato de estabelecer uma conexão é um comportamento do adversário.

3. Pesquise o comportamento — Se você não estiver familiarizado com o comportamento, pode ser necessário fazer mais pesquisas. Em nosso exemplo, um pouco de pesquisa mostraria que SOCKS5 é um protocolo de Camada 5 (camada de sessão).

4. Traduzir o comportamento em uma tática – Considere o objetivo técnico do adversário para aquele comportamento e escolha uma tática que se encaixe. A boa notícia: existem apenas 12 táticas para escolher no Enterprise ATT&CK. Para o exemplo de conexão SOCKS5, estabelecer uma conexão para se comunicar posteriormente cairia na tática de Comando e Controle.

5. Descubra qual técnica se aplica ao comportamento – isso pode ser um pouco complicado, mas com suas habilidades de análise e os exemplos do site da ATT&CK, é possível. Se você pesquisar SOCKS em nosso site, a técnica Standard Non-Application Layer Protocol (T1095) aparecerá. Olhando para a descrição da técnica, você descobrirá que pode ser onde nosso comportamento se encaixa.

6.  Compare seus resultados com outros analistas - Claro, você pode ter uma interpretação diferente de um comportamento de outro analista. Isso é normal e acontece o tempo todo na equipe ATT&CK! Recomendamos comparar seu mapeamento de informações da ATT&CK com o de outro analista e discutir quaisquer diferenças.

### Detecção e Análise

##### Coletar dados

Nenhuma decisão pode ser tomada sem dados e fatos. Às vezes, as decisões são tomadas com dados e fatos incompletos ou imprecisos, mas esses ainda são componentes importantes para o raciocínio crítico.

Antes de começar a coletar dados, é útil entender as fontes das quais você deve coletá-los. MITRE tem algumas recomendações aqui também.

- O monitoramento do processo e da linha de comando do processo pode ser coletado via [Sysmon](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon), Windows Event Logs e muitas plataformas EDR.
- O monitoramento de arquivos e registros também costuma ser coletado pelo Sysmon, logs de eventos do Windows e muitas plataformas de EDR.
- Logs de autenticação coletados do controlador de domínio.
- Captura de pacotes, especialmente captura leste/oeste, como aqueles coletados entre hosts e enclaves em sua rede.

O MITRE criou alguns scripts para auxiliar na descoberta desses dados. Eles os  disponibilizaram abertamente no [Github](https://github.com/mitre-attack/attack-scripts/tree/master/scripts)

##### Analisar dados

**Repositório MITRE Cyber ​​Analytics (CAR)**  

CAR ( [https://car.mitre.org/](https://car.mitre.org/) ) é uma base de conhecimento de análise desenvolvida pela MITRE e é baseada no modelo adversário MITRE ATT&CK. As análises armazenadas no CAR contêm as seguintes informações para cada análise:  

-   Uma hipótese que explica a ideia por trás de uma análise
-   A informação ou o domínio principal no qual a análise foi projetada para operar (pode ser host, rede, processo, externo, etc.)
-   Referências a técnicas e táticas ATT&CK que o analítico detecta
-   O Glossário
-   Uma descrição em pseudocódigo de como a análise pode ser implementada
-   Um teste de unidade que pode ser executado para acionar o analítico

Ao revisar os dados apresentados no MITRE CAR, você pode começar não apenas a analisar os comportamentos que ocorrem em sua empresa, mas também a expandir seus dados de inteligência de ameaças, mapeando esses comportamentos de volta ao MITRE ATT&CK.

**Instruções de exercícios do laboratório CAR**

1.  Acesse  [https://car.mitre.org/analytics](https://car.mitre.org/analytics)
2.  Encontre uma análise que corresponda à técnica do  OS Credential Dumping . Em nosso exemplo, usamos a analítica para Mimikatz.
3.  Clique no analítico e leia a descrição.
4.  Dê uma olhada no código analítico que é apresentado e veja se você consegue entender o que ele está tentando fazer.

### Emulação de Adversário e Red Teaming

A MITRE define a emulação de adversário como “um tipo de engajamento de equipe vermelha que imita uma ameaça conhecida a uma organização, combinando inteligência de ameaças para definir quais ações e comportamentos a equipe vermelha usa”. Em outras palavras, a equipe vermelha adota uma abordagem estruturada usando inteligência de ameaças para planejar um ataque semelhante ao comportamento conhecido do agente de ameaças.


## Links:

[GETTING STARTED WITH AAT&CK ](https://www.mitre.org/sites/default/files/2021-11/getting-started-with-attack-october-2019.pdf)
