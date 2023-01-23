
# CERTIFIED IN CYBERSECURITY (CC) - (ISC)²

Tags: #certificação #cybersecurity #ISC²


Todos os dados precisam de alguma forma de segurança; mesmo os dados que não são confidenciais (como dados destinados à exibição pública) precisam de proteção para garantir a disponibilidade.



## CIA Triad

**Confidentiality** (confidencialidade) - A característica dos dados ou informações quando não são disponibilizados ou divulgados a pessoas ou processos não autorizados. Exemplos de quebra de confidencialidade: escalonamento de privilégios e quebra de senhas.

**Integrity** (integridade) - A propriedade da informação pela qual ela é registrada, usada e mantida de forma a garantir sua integridade, precisão, consistência interna e utilidade para um propósito declarado. Um exemplo de quebra de integridade seria quando um funcionário tenta alterar a planilha de pagamentos sem permissão para tal.

**Availability** (disponibilidade) - Garantir acesso oportuno e confiável e uso de informações por usuários autorizados. Um exemplo de quebra de disponibilidade é o ataque DoS (Negação de Serviço).



**Privacy** (privacidade) -O direito de um indivíduo de controlar a distribuição de informações sobre si mesmo.

**Non-repudiation** - A incapacidade de negar a realização de uma ação, como criar informações, aprovar informações e enviar ou receber uma mensagem.
*  O não-repúdio  é um termo legal e é definido como a proteção contra um indivíduo que nega falsamente ter realizado uma determinada ação.
* As metodologias de não repúdio garantem que as pessoas sejam responsabilizadas pelas transações que conduziram. 

**Criticality** (criticidade)  - Uma medida do grau em que uma organização depende da informação ou sistema de informação para o sucesso de uma missão ou de uma função de negócios.

**Autenticidade** - A informação está sendo enviada por uma fonte legítima e segura, e não foi interceptada e alterada por atacantes. Quando interceptada e alterada, afeta a integridade.

**Authorization** - O direito ou uma permissão concedida a uma entidade do sistema para acessar um recurso do sistema.  NIST 800-82 Rev.2

## Autenticação (Authentication)

Processo de controle de acesso que compara um ou mais fatores de identificação para validar que a identidade reivindicada por um usuário ou entidade é conhecida pelo sistema.

Existem 3 métodos comuns de autenticação:
- Algo que você conhece (ex: senha)
- Algo que você tem (ex: tokens)
- Algo que você é (ex: biometria)

Existem dois tipos de autenticação. O uso de apenas um dos métodos é conhecido como **Autenticação de Fator Único (SFA)**. A concessão de acesso após a demonstração ou exibição bem sucedida de dois ou mais  métodos é conhecida como **Autenticação Multifator (MFA)**.



## Risco

#### Gerenciamento de Risco

- Um **ativo** é algo que precisa de proteção.

-  Uma **vulnerabilidade** é uma lacuna ou fraqueza nesses esforços de proteção. É uma fraqueza ou falha inerente em um sistema ou componente que, se desencadeada ou atuada, pode causar a ocorrência de um evento de risco.

-  Uma **ameaça** é uma pessoa ou coisa que toma medidas para explorar (ou fazer uso de) as vulnerabilidades do sistema de uma organização-alvo, como parte de atingir ou promover sua meta ou objetivos.
		* Vetor de Ameaça: O meio pelo qual um ator de ameaça realiza seus objetivos.
		* Agente de ameaça: Um indivíduo ou grupo que tenta explorar vulnerabilidades para causar ou forçar a ocorrência de uma ameaça.

-   **Probabilidade de ocorrência** é um fator ponderado com base em uma análise subjetiva da probabilidade de uma determinada ameaça ser capaz de explorar uma determinada vulnerabilidade ou conjunto de vulnerabilidades.

#### Avaliação de risco (Risk Assessment)

A avaliação de riscos  é definida como o processo de identificação, estimativa e priorização de riscos para as operações de uma organização (incluindo sua missão, funções, imagem e reputação), ativos, indivíduos, outras organizações e até mesmo a nação.

#### Tratamento de risco (Risk Treatment)

Risk Transference - A transferência de risco é a prática de transferir o risco para outra parte, que aceitará o impacto financeiro do dano resultante da realização de um risco em troca de pagamento. Normalmente, esta é uma apólice de seguro.

Risk Avoidance - A prevenção do risco é a decisão de tentar eliminar totalmente o risco. 
	
Risk Acceptance - Aceitação de risco é não tomar nenhuma ação para reduzir a probabilidade de ocorrência de um risco.
	
Risk Mitigation - A mitigação de riscos é o tipo mais comum de gerenciamento de riscos e inclui a tomada de ações para prevenir ou reduzir a possibilidade de um evento de risco ou seu impacto. 

#### Risk Priorities

Quando os riscos forem identificados, é hora de priorizar e analisar os principais riscos por meio da análise de risco qualitativa e/ou análise de risco quantitativa. 
	- Um método eficaz para priorizar o risco é usar uma matriz de risco, que ajuda a identificar a prioridade como a interseção da probabilidade de ocorrência e impacto.
	- Ao tomar decisões com base nas prioridades de risco, as organizações devem avaliar a probabilidade e o impacto do risco, bem como sua tolerância a diferentes tipos de risco. 

#### Tolerância ao risco (Risk Tolerance)

O nível de tolerância ao risco varia entre as organizações e até internamente: departamentos diferentes podem ter atitudes diferentes em relação ao risco aceitável ou inaceitável.



## Controles de Segurança

Os controles de segurança referem-se aos mecanismos físicos, técnicos e administrativos que atuam como salvaguardas ou contramedidas prescritas para um sistema de informação para proteger a confidencialidade, integridade e disponibilidade do sistema e de suas informações. 

#### Controles físicos (physical controls)

Os controles físicos atendem às necessidades de segurança baseadas em processos usando dispositivos físicos de hardware, como leitores de crachás, características arquitetônicas de prédios e instalações e ações de segurança específicas a serem tomadas pelas pessoas. 

Muitos tipos de mecanismos de controle de acesso físico podem ser implantados em um ambiente para controlar, monitorar e gerenciar o acesso a uma instalação.

#### Controles técnicos

Controles técnicos(também chamados de controles lógicos) são controles de segurança que sistemas de computador e redes implementam diretamente.
	- Os controles técnicos podem ser definições de configuração ou parâmetros armazenados como dados, gerenciados por meio de uma interface gráfica do usuário (GUI) de software, ou podem ser configurações de hardware feitas com interruptores, plugues de jumper ou outros meios. 

#### Controles administrativos (administrative controls)

Os controles administrativos (também conhecidos como controles gerenciais) são diretrizes, guias ou conselhos dirigidos às pessoas dentro da organização. Eles fornecem estruturas, restrições e padrões para o comportamento humano e devem cobrir todo o escopo das atividades da organização e suas interações com partes externas e partes interessadas.



## Governança

#### Regulamentos e leis

Os regulamentos e leis (regulations and laws) são comumente emitidos na forma de leis, geralmente do governo (não confundir com governança) e geralmente acarretam penalidades financeiras por descumprimento.
	- Ex: Regulamento Geral de Proteção de Dados (GDPR); 

#### Políticas
As políticas (policies) são implementadas pela governança organizacional, como a gestão executiva, para fornecer orientação em todas as atividades para garantir que a organização suporte os padrões e regulamentos do setor.

#### Padrões

Os padrões (standards) são frequentemente usados ​​pelas equipes de governança para fornecer uma estrutura para introduzir políticas e procedimentos em apoio aos regulamentos.
	- Ex1: Organização Internacional de Padronização (ISO);
	- Ex2: Internet Engineering Task Force (IETF) , existem padrões em protocolos de comunicação que garantem que todos os computadores possam se conectar entre si através das fronteiras

#### Procedimentos

Os procedimentos (procedures) são as etapas detalhadas para concluir uma tarefa que oferece suporte às políticas departamentais ou organizacionais. Os procedimentos definem as atividades explícitas e repetíveis necessárias para realizar uma tarefa específica ou um conjunto de tarefas. 