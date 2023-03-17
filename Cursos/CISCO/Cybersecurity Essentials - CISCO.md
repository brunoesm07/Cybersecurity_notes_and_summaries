# Criptografia

A criptografia é a técnica de armazenar e transmitir dados, de modo que somente o destinatário pretendido possa ler ou processá-los. Ela converte a mensagem legível de texto claro em texto codificado, que é a mensagem ilegível disfarçada. A descriptografia reverte o processo.

Um algoritmo de criptografia é tão bom quanto a chave usada. Quanto mais complexidade envolvida, mais seguro é o algoritmo.

Há duas classes de algoritmos de criptografia:

**Algoritmos simétricos** - Esses algoritmos usam a mesma chave pré-compartilhada, às vezes chamada de par de chaves secretas, para criptografar e descriptografar dados. Os algoritmos de criptografia que usam uma chave comum são mais simples e precisam de menos potência computacional.

Alguns dos padrões de criptografia comuns que usam criptografia simétrica são:

- 3DES (triplo DES): Digital Encryption Standard (DES) é uma cifra de blocos simétrica de 64 bits, que usa uma chave de 56 bits.
- IDEA: O Algoritmo de Criptografia de Dados (IDEA) usa blocos de 64 bits e chaves de 128 bits.
- AES: O Advanced Encryption Standard (AES) tem um tamanho de bloco fixo de 128 bits, com um tamanho de chave de 128, 192 ou 256 bits. O AES é mais rápido do que DES e 3DES, portanto, oferece uma solução tanto para aplicações de software quanto para uso de hardware em firewalls e roteadores.

**Algoritmos assimétricos** - A criptografia assimétrica usa uma chave para criptografar (pública) os dados e uma chave diferente (privada) para descriptografá-los. Em um sistema de criptografia de chave pública, qualquer pessoa pode codificar uma mensagem utilizando a chave pública do destinatário e o destinatário é o único que pode decifrá-la usando sua chave privada.

Os algoritmos assimétricos incluem:

- RSA (Rivest-Shamir-Adleman) - Usa o produto de dois números primos muito grandes, com um tamanho igual de 100 a 200 dígitos. Os navegadores usam RSA para estabelecer uma conexão segura.
- Diffie-Hellman - Fornece um método de troca eletrônica para compartilhar a chave secreta. Os protocolos seguros, como Secure Sockets Layer (SSL), Transport Layer Security (TLS), Secure Shell (SSH) e Internet Protocol Security (IPsec) usam Diffie-Hellman.
- Criptografia de curva elíptica (ECC) - Usa curvas elípticas como parte do algoritmo. Nos Estados Unidos, a Agência Nacional de Segurança usa ECC para geração de assinatura digital e troca de chave.

Vídeo: [How asymmetric (public key) encryption works](https://www.youtube.com/watch?v=E5FEqGYLL0o)

# Estenografia

A estenografia esconde dados (a mensagem) em outro arquivo, como um gráfico, áudio, foto ou outro arquivo de texto. A vantagem da estenografia em relação à criptografia é que a mensagem secreta não atrai atenção especial, pois ao visualizar o arquivo ninguém saberá que na realidade contém uma mensagem secreta.

### Bits Menos Significativos (LSB)

Esse método usa os bits de cada pixel na imagem. O olho humano não consegue reconhecer as alterações efetuadas nos bits menos significativos.

### Estenografia Social

A estenografia social oculta informações de visão simples, criando uma mensagem que pode ser entendida de certa forma pela pessoa que receber a mensagem (público específico), porém as outras pessoas que visualizarem a mensagem de modo normal não a entenderão. Criminosos utilizam essa técnica para conversar por telefone ou troca de mensagens.

Por exemplo, a frase "comprar a bengala" pode significar "comprar o fuzil".

# Ofuscação

A ofuscação de dados é o uso e a prática de técnicas de estenografia e mascaramento de dados na profissão de segurança digital e inteligência cibernética. A ofuscação é a arte de tornar uma mensagem confusa, ambígua ou mais difícil de entender. Um sistema pode embaralhar propositalmente as mensagens para evitar o acesso não autorizado a informações confidenciais.

# Controle de Acesso

### MAC (Mandatory Access Control)

O controle de acesso obrigatório (MAC) restringe as ações que um indivíduo pode executar em um objeto, através de regras de autorização. Um sistema MAC restringe um indivíduo com base na classificação de segurança do objeto e na etiqueta anexada ao usuário.

### DAC (Discretionary Access Control)

O DAC concede ou restringe o acesso ao objeto determinado pelo respectivo responsável. Nos sistemas que usam controles de acesso discricionários, o responsável por um objeto pode decidir quais indivíduos podem acessar esse objeto e qual acesso específico podem ter.

### RBAC (Role-based Access Control)

O controle de acesso por função (RBAC) varia de acordo com a função de trabalho do indivíduo em uma empresa. Funções específicas necessitam de permissões para realizar determinadas operações.

# Hash

Hash é uma ferramenta que assegura, através de uma função criptográfica de hash, a integridade de dados através da captura de dados binários (a mensagem) para produzir representação de tamanho fixo denominada valor de hash ou message digest.

Cada vez que os dados são modificados ou alterados, o valor de hash também muda, sendo muitas vezes chamados de impressões digitais. Podem detectar arquivos de dados duplicados, alterações na versão do arquivo e aplicações similares. Esses valores protegem contra alterações de dados acidentais ou intencionais e corrupção de dados acidental.

A função hash tem as seguintes propriedades:

- A entrada pode ser de qualquer comprimento.
- A saída tem um comprimento fixo.
- A função hash é unidirecional e não é reversível.
- Dois valores de entrada distintos quase nunca resultarão em valores de hash idênticos.

Aplicações:

- Fornecer a comprovação da autenticidade quando usada com uma chave de autenticação secreta simétrica, como IP Security (IPsec) ou autenticação de protocolo de roteamento
- Fornecer autenticação gerando respostas unidirecionais únicas para desafios em protocolos de autenticação
- Fornecer a comprovação da verificação de integridade da mensagem, como as que são usadas em contratos assinados digitalmente, e certificados de infraestrutura de chave pública (PKI), como os que são aceitos ao acessar um site seguro com um navegador

### Salting

O salting torna o hash de senhas mais seguro. Se dois usuários têm a mesma senha, eles também terão os mesmos hashes de senha. Um SALT, que é uma cadeia de caracteres aleatória, é uma entrada adicional à senha antes do hash. Isso cria um resultado de hash diferente para as duas senhas.

```
Hash ("senha" + QxLUF1bIAdeQX) = b3bad1e5324f057753a4b8d7cef293e4
Hash ("senha" + R9PelC7sxQXb8) = 713c7beb54841a26a7c81eb06d6cf066
```
O salting impede que um invasor use um ataque de dicionário para tentar adivinhar senhas. Como também torna impossível o uso de tabelas de pesquisa e rainbow tables para decifrar um hash.

# Assinatura Digital

Uma assinatura digital é um método matemático usado para verificar a autenticidade e a integridade de uma mensagem, documento digital ou software. Elal assegura que o remetente assinou eletronicamente a mensagem ou documento. e como é exclusiva para a pessoa que a criou, essa pessoa não pode posteriormente negar que forneceu a assinatura (não repúdio).

A criptografia assimétrica é a base das assinaturas digitais.

# Certificado Digital

Um certificado digital é equivalente a um passaporte eletrônico que permite aos usuários, hosts e empresas a troca de informações de forma segura através da Internet. Qualquer entidade pode ler e entender o certificado digital, independentemente do emissor, contanto que o certificado digital siga uma estrutura padrão.

Os navegadores e aplicativos realizam uma verificação de validação, antes de assegurar que um certificado seja válido. Os três processos incluem o seguinte:

- A descoberta do certificado valida o caminho de certificação, verificando cada certificado desde o início com o certificado da CA raiz
- A validação do caminho escolhe um certificado da CA emissora para cada certificado na cadeia
- A revogação determina se o certificado foi revogado e por que

# Resposta a Incidente

Resposta a incidente são procedimentos que uma empresa segue, depois da ocorrência de um evento fora dos limites de normalidade.  

### Detecção e análise

A detecção começa quando é descoberto o incidente. A detecção adequada inclui como o incidente ocorreu, quais dados estavam envolvidos e quais sistemas estavam envolvidos.

A análise de incidente ajuda a identificar a origem, extensão, impacto e detalhes de uma violação de dados.

### Contenção, erradicação e recuperação

Os esforços de contenção incluem ações imediatas realizadas, como desconectar um sistema da rede para parar o vazamento de informações.

Depois de identificar a violação, a empresa precisa contê-la e erradicá-la. Isso pode exigir período de inatividade adicional para os sistemas. A fase de recuperação inclui as medidas que a empresa precisa tomar para resolver a violação e restaurar os sistemas envolvidos. Depois da solução, a empresa precisa restaurar todos os sistemas ao seu estado original, antes da violação.

### Acompanhamento pós-incidente

Depois de restaurar todas as operações a um estado normal, a empresa deve examinar a causa do incidente. Um exame das lições aprendidas pode ajudar a empresa a se preparar melhor, melhorando o plano de resposta a incidente.

## Tecnologias de Resposta a Incidente

### Network Admission Control

A finalidade do Network Admission Control (NAC) é permitir que usuários, autorizados em sistemas em conformidade, acessem a rede.

Uma estrutura NAC pode usar a infraestrutura de rede existente e software de terceiros para aplicar a conformidade com as políticas de segurança para todos os dispositivos finais. Alternativamente, um dispositivo NAC controla o acesso à rede, avalia a conformidade e aplica a política de segurança. Verificações de sistemas NAC comuns incluem:

1. Detecção de vírus atualizada

2. Patches e atualizações do sistema operacional

3. Aplicação de senhas complexas

### Sistema de detecção de invasão

Os IDSs (Intrusion Detection System, Sistemas de detecção de invasão) são mecanismos capazes de identificar ou detectar a presença de atividades intrusivas, .monitorando passivamente o tráfego em uma rede.

### Sistema de prevenção de invasão

Um IPS se baseia na tecnologia IDS. Entretanto, um dispositivo IPS é implementado no modo InLine. Isso significa que todo o tráfego de entrada e de saída deve fluir através dele para ser processado.

![[IDS vs IPS.png]]

A maior diferença entre o IDS e o IPS é que um IPS responde imediatamente e não permite que nenhum tráfego malicioso passe, enquanto um IDS permite que tráfego malicioso passe, antes de abordar o problema.

# Plano de Recuperação de Desastres

O Disaster Recovery Plan (DRP)  inclui as atividades que a empresa realiza para avaliar, recuperar, reparar e restaurar instalações ou ativos danificados. Um DRP precisa identificar quais processos da empresa são os mais essenciais. Durante o processo de recuperação, a empresa restaura seus sistemas de missão crítica, primeiro.

# Proteção de Sistemas e Dispositivos

### Microsoft Baseline Security Analyzer (MBSA)

Avalia as atualizações de segurança ausentes e problemas de configuração de segurança no Microsoft Windows. Verifica senhas em branco, simples ou inexistentes, configurações de firewall, status de conta de convidado, detalhes da conta de administrador, a auditoria de eventos de segurança, serviços desnecessários, compartilhamentos de rede e configurações do registro.

### Antimalware

É importante proteger os computadores e dispositivos móveis com software antimalware de qualidade. Alguns tipos de programas antimalware conhecidos são:

- Proteção antivírus
- Proteção contra adware
- Proteção contra phishing - bloqueia endereços IP de sites de phishing conhecidos na web e avisa o usuário sobre sites suspeitos.
- Proteção contra spyware - varre o computador em busca de keyloggers e ouros tipos de spyware.

Várias empresas de segurança confiáveis, como McAfee, Symantec e Kaspersky, oferecem proteção completa contra malware para computadores e dispositivos móveis.

### Gerenciamento de patches

Os patches são atualizações de código que os fabricantes fornecem para evitar que um vírus ou um worm recém-descoberto façam um ataque bem-sucedido.

### Firewalls baseados em host e sistemas de detecção de invasão

Um firewall de software é um programa que é executado em um computador para permitir ou negar tráfego entre o computador e outros computadores conectados. O firewall por software aplica um conjunto de regras a transmissões de dados por meio da inspeção e filtragem de pacotes de dados.

Um sistema de detecção de invasão do host (HIDS) é um software que é executado em um computador que monitora atividades suspeitas. O HIDS monitora chamadas do sistema e o acesso ao sistema de arquivos para garantir que as solicitações não sejam o resultado de uma atividade maliciosa.

### VPN

A VPN é uma rede privada que conecta usuários ou sites remotos por uma rede pública, como a Internet. A VPN usa conexões seguras dedicadas, roteadas pela Internet, da rede corporativa privada para o usuário remoto. Quando conectados à rede privada corporativa, os usuários se tornam parte dela e têm acesso a todos os serviços e recursos, como se estivessem fisicamente conectados à LAN corporativa.

# Centros de Operações

O **NOC (Network Operation Center, Centro de operação de rede)** é um ou mais locais que contêm as ferramentas que fornecem aos administradores um status detalhado da rede da empresa. O NOC é a base da solução de problemas de rede, monitoramento de desempenho, distribuição e atualizações de software e gerenciamento de dispositivo.

O **SOC (Security Operation Center, Centro de operação de segurança)** é um local dedicado que monitora, avalia e defende os sistemas de informação da empresa, como sites, aplicações, bancos de dados, data centers, redes, servidores e sistemas de usuários. Um SOC é composto por equipes de analistas de segurança que detectam, analisam, respondem, relatam e previnem incidentes de segurança cibernética.