# Hosts

O termo *hosts*, também conhecido como dispositivos finais (*endpoints*), refere-se especificamente a dispositivos na rede que participam diretamente da comunicação. Estes recebem um número chamado de endereço IP (Internet Protocol) que os identificam. 

Desktop, tablet, celular, laptop, impressora


## Dispositivos intermediários

Dispositivos intermediários (roteador, switch, firewall) conectam os dispositivos finais individuais à rede.   * *Interconecta dispositivos finais.

Também são funções de um dispositivo intermediário os seguintes:

- Regenerar e retransmitir sinais de dados;
- Manter informações sobre quais caminhos existem na rede;
- Notificar outros dispositivos sobre erros e falhas de comunicação.

## Meios de rede

As redes modernas usam principalmente três tipos de mídia para interconectar dispositivos:

- **Fios de metal dentro de cabos** - Os dados são codificados em impulsos elétricos.
- **Fibras de vidro ou plástico nos cabos (cabo de fibra óptica)** - Os dados são codificados em pulsos de luz.
- **Transmissão sem fio** - Os dados são codificados através da modulação de frequências específicas de ondas eletromagnéticas.

# Diagramas de Topologia

Os diagramas de topologia são documentação obrigatória para qualquer pessoa que trabalhe com uma rede. Eles fornecem um mapa visual de como a rede está conectada. Existem dois tipos de diagramas de topologia: físicos e lógicos.

**Topologia Física** - permite que você veja a localização real dos dispositivos intermediários e da instalação de cabos. Você pode ver quais as salas em que esses dispositivos estão localizados.

**Topologia Lógica** - permite que você veja quais dispositivos finais estão conectados a quais dispositivos intermediários e que mídia está sendo usada. Diagramas de topologia lógica ilustram dispositivos, portas e o esquema de endereçamento da rede.


# Tipos Comuns de Redes

## LANs e WANs

Os dois tipos mais comuns de infraestruturas de rede são as redes locais (LANs) e as redes de longa distância (WANs). Uma LAN é uma infraestrutura de rede que fornece acesso a usuários e dispositivos finais em uma pequena área geográfica. Normalmente, uma LAN é usada em um departamento dentro de uma empresa, uma casa ou uma rede de pequenas empresas. Uma WAN é uma infraestrutura de rede que fornece acesso a outras redes em uma ampla área geográfica, que normalmente pertence e é gerenciada por uma corporação maior ou por um provedor de serviços de telecomunicações.

## Intranets e Extranets

Intranet é um termo frequentemente usado para se referir a uma conexão privada de LANs e WANs que pertence a uma organização. Uma intranet é projetada para ser acessada apenas por membros da organização, funcionários ou outras pessoas autorizadas.

Uma organização pode usar uma extranet para fornecer acesso seguro e protegido a indivíduos que trabalham para uma organização diferente, mas exigem acesso aos dados da organização. Aqui estão alguns exemplos de extranets:

-   Uma empresa que fornece acesso a fornecedores e contratados externos;
-   Um hospital que fornece um sistema de reservas aos médicos para que eles possam marcar consultas para seus pacientes;
-   Um escritório local de educação que está fornecendo informações sobre orçamento e pessoal às escolas de seu distrito.


# Arquitetura de Redes

Quatro características básicas:

1) **Tolerância a falhas**

Uma rede tolerante a falhas é aquela que limita o número de dispositivos afetados durante uma falha e que foi desenvolvida para permitir uma recuperação rápida após uma falha. Essas redes dependem de vários caminhos entre a origem e o destino de uma mensagem. **Se um caminho falhar, as mensagens serão instantaneamente enviadas por um link diferente**. Ter vários caminhos para um destino é conhecido como redundância.

2) Escalabilidade

Uma rede escalável se expande rapidamente para oferecer suporte a novos usuários e aplicativos. Ele faz isso sem degradar o desempenho dos serviços que estão sendo acessados por usuários existentes. **Essas redes são escaláveis porque os projetistas seguem padrões e protocolos aceitos.**

3) Qualidade do Serviço (QoS)

A qualidade do serviço (QoS) é um requisito crescente das redes atualmente. Novos aplicativos disponíveis para usuários em redes, como transmissões de voz e vídeo ao vivo, criam expectativas mais altas em relação à qualidade dos serviços entregues.

4) Segurança

A infraestrutura da rede, os serviços e os dados contidos nos dispositivos conectados à rede são recursos pessoais e comerciais críticos. Os administradores de rede devem abordar dois tipos de preocupações de segurança de rede: segurança da infraestrutura de rede e segurança da informação.

Proteger a infraestrutura de rede inclui proteger fisicamente os dispositivos que fornecem conectividade de rede e impedir o acesso não autorizado ao software de gerenciamento que reside neles.


# Soluções de Segurança

Nenhuma solução única pode proteger a rede da variedade de ameaças existentes. Por esse motivo, a segurança deve ser implementada em várias camadas, com uso de mais de uma solução. Se um componente de segurança falhar na identificação e proteção da rede, outros poderão ter êxito.

Estes são os componentes básicos de segurança para uma rede doméstica ou de pequeno escritório:

- **Antivirus e antispyware** - Esses aplicativos ajudam a proteger os dispositivos finais contra a infecção por software malicioso.
- **Filtragem por firewall** - A filtragem por firewall bloqueia o acesso não autorizado dentro e fora da rede. Isso pode incluir um sistema de firewall baseado em host que impede o acesso não autorizado ao dispositivo final ou um serviço básico de filtragem no roteador doméstico para impedir o acesso não autorizado do mundo externo à rede.

Em contrapartida, a implementação de segurança para uma rede corporativa geralmente consiste em vários componentes incorporados à rede para monitorar e filtrar o tráfego. Idealmente, todos os componentes trabalham juntos, o que minimiza a manutenção e melhora a segurança. Redes maiores e redes corporativas usam antivírus, antispyware e filtragem por firewall, mas também têm outros requisitos de segurança:

- **Sistemas de firewall dedicados** - Eles fornecem recursos de firewall mais avançados que podem filtrar grandes quantidades de tráfego com mais granularidade.
- **Listas de controle de acesso (ACL)** - Eles filtram ainda mais o acesso e o encaminhamento de tráfego com base em endereços e aplicativos IP.
- **Sistemas de prevenção de intrusões (IPS)** - Identificam ameaças de rápida disseminação, como ataques de dia zero ou hora zero.
- **Redes privadas virtuais (VPN)** - fornecem acesso seguro a uma organização para trabalhadores remotos.

# Sistemas Operacionais

A parte do sistema operacional que interage diretamente com o hardware e o software do computador é conhecida como **kernel**. Ele gerencia como os recursos de hardware são usados para atender aos requisitos do software.

A parte que tem interface com aplicações e o usuário é conhecida como **shell**. O usuário pode interagir com a **shell** por meio de uma **interface de linha de comando CLI (*Command Line Interface*)** ou uma **interface gráfica de usuário GUI (*Graphical User Interface*)**.

**SECURE SHELL PROTOCOL (SSH)** - O SSH é um método dentro da banda e recomendado para estabelecer remotamente uma conexão CLI segura, através de uma interface virtual, através de uma rede. Ao contrário de uma conexão de console, as conexões SSH requerem serviços de rede ativos no dispositivo, incluindo uma interface ativa configurada com um endereço.

**TELNET** - O Telnet é um método inseguro em banda para estabelecer remotamente uma sessão de CLI, por meio de uma interface virtual, por uma rede. Ao contrário do SSH, o Telnet não fornece uma conexão segura e criptografada e só deve ser usado em um ambiente de laboratório. A autenticação de usuário, as senhas e os comandos são enviados pela rede como texto simples.


## Navegação no Cisco IOS

Abaixo estão os dois modos e os prompts da CLI padrão de um switch e roteador Cisco. Para mudar de usuário para privilegiado digita-se o comando `enable` e para retornar `disable`.

| Modo de Comando | Descrição | Aviso padrão do dispositivo |
|           ----                 |   ----  |  ----  |
| **Modo Exec usuário** |  -   O modo permite acesso a apenas um número limitado de comandos de monitoramento básico. | Switch> ou Router> |
| **Modo EXEC privilegiado** | -   O modo permite acesso a todos os comandos e recursos, pode usar qualquer comando de monitoramento e executar a configuração e comandos de gerenciamento. | Switch# ou Router#

O modo de configuração global é identificado por um prompt que termina com (config)#após após o nome do dispositivo, como **Switch(config)#**. Para acessá-lo digite `configure terminal` e para sair digite `exit`.

Esse modo é acessado antes de outros modos de configuração específicos. No modo de configuração global, o usuário pode inserir diferentes modos de subconfiguração. Cada um desses modos permite a configuração de uma parte particular ou função do dispositivo IOS. Dois modos comuns de subconfiguração incluem:

-   **Modo de configuração de linha -** Usado para configurar o acesso ao console, SSH, Telnet ou AUX.
-   **Modo de configuração da interface -** Usado para configurar uma porta de switch ou interface de rede do roteador.

O prompt padrão para o modo de configuração de linha é **Switch(config-line)#** e o prompt padrão para o modo de configuração da interface é **Switch(config-if)#**.

Os comandos `CTRL+Z` e `end` retornam ao prompt EXEC privilegiado, independentemente do modo de configuração em que você está.

O `?` exibe uma lista de comandos disponíveis em cada modo de comando, como também quais argumentos e palavras-chave estão disponíveis para comandos específicos.

# Protocolos

Os protocolos de rede definem um formato comum e um conjunto de regras para a troca de mensagens entre dispositivos. Os protocolos são implementados por dispositivos finais e dispositivos intermediários em software, hardware ou ambos. Cada protocolo de rede tem sua própria função, formato e regras para comunicações.

| **Tipo de Protocolo** | **Descrição** | 
| -------------------- | ------------| 
| **Protocolos de comunicação em rede** | Os protocolos permitem que dois ou mais dispositivos se comuniquem através de um ou mais redes. A família de tecnologias Ethernet envolve uma variedade de protocolos como IP, Transmission Control Protocol (TCP), HyperText Protocolo de transferência (HTTP) e muito mais. |
| **Protocolos de segurança de rede** | Protocolos protegem os dados para fornecer autenticação, integridade dos dados e criptografia de dados. Exemplos de protocolos seguros incluem o Secure Shell (SSH), SSL (Secure Sockets Layer) e TLS (Transport Layer Security). |
| **Protocolos de roteamento** | Protocolos permitem que os roteadores troquem informações de rota, compare caminho e, em seguida, selecionar o melhor caminho para o destino remota. Exemplos de protocolos de roteamento incluem Open Shortest Path First (OSPF) e Border Gateway Protocol (BGP). | 
| **Protocolos de descoberta de serviço** | Protocolos são usados para a detecção automática de dispositivos ou serviços. Exemplos de protocolos de detecção de serviços incluem Host dinâmico Protocolo de Configuração (DHCP) que detecta serviços para endereço IP alocação e Sistema de Nomes de Domínio (DNS) que é usado para executar conversão de nome para endereço IP. |

* Suites de Protocolos são grupos de regras que funcionam em conjunto para ajudar a resolver um problema.

 O TCP/IP é o conjunto de protocolos usado pela internet e as redes de hoje. 

- **Conjunto de protocolos de padrão aberto** - isso significa que está disponível gratuitamente ao público e pode ser usado por qualquer fornecedor em seu hardware ou software.
- **Conjunto de protocolos com base em padrões** - isso significa que foi endossado pela industria de rede e aprovaddo por uma organização de padrões. Isso garante que produtos de diferentes fabricantes possam interoperar com êxito.

## Modelos de Camadas

![[Modelos de Camadas.png]]

### Modelo de Referência OSI

O modelo de referência OSI fornece uma extensa lista de funções e serviços que podem ocorrer em cada camada. Esse tipo de modelo fornece consistência em todos os tipos de protocolos e serviços de rede, descrevendo o que deve ser feito em uma camada específica, mas não prescrevendo como deve ser realizado.

### Modelo de Protocolo TCP/IP

O modelo TCP/IP é um modelo de protocolo porque descreve as funções que ocorrem em cada camada de protocolos dentro da suíte TCP/IP. O TCP/IP também é usado como um modelo de referência.

### Comparação de modelos OSI e TCP / IP

Os protocolos que compõem a suíte de protocolos TCP/IP também podem ser descritos em termos do modelo de referência OSI. No modelo OSI, a camada de acesso à rede e a camada de aplicação do modelo TCP/IP são, divididas para descrever funções discretas que devem ocorrer nessas camadas.

## Protocolo TCP/IP

![[padroes.png]]

### Camada de aplicação

Sistema de nomes

-   **DNS** - Sistema de nomes de domínio. Converte nomes de domínio, como cisco.com, em endereços IP.

Configuração de hosts

-   **DHCPv4** - Protocolo de configuração de host dinâmico para IPv4. Um servidor DHCPv4 atribui dinamicamente informações de endereçamento IPv4 aos clientes DHCPv4 na inicialização e permite que os endereços sejam reutilizados quando não forem mais necessários.
-   **DHCPv6** - Protocolo de Configuração do Host Dinâmico para IPv6. DHCPv6 é semelhante ao DHCPv4. Um servidor DHCPv6 atribui dinamicamente informações de endereçamento IPv6 aos clientes DHCPv6 na inicialização.
-   **SLAAC** - Configuração automática de endereço sem estado. Um método que permite que um dispositivo obtenha suas informações de endereçamento IPv6 sem usar um servidor DHCPv6.

E-mail

-   **SMTP** -Protocolo de transferência de correio simples. Permite que os clientes enviem e-mails para um servidor de e-mail e permite que os servidores enviem e-mails para outros servidores.
-   **POP3** - Post Office Protocol versão 3. Permite que os clientes recuperem e-mails de um servidor de e-mail e baixem o e-mail para o aplicativo de e-mail local do cliente.
-   **IMAP** - Protocolo de Acesso à Mensagem na Internet. Permite que os clientes acessem o e-mail armazenado em um servidor de e-mail e também mantenham o e-mail no servidor.

Transferência de arquivos

-   **FTP** - Protocolo de transferência de arquivos. Define as regras que permitem que um usuário em um host acesse e transfira arquivos para e de outro host em uma rede. O FTP é um protocolo de entrega de arquivos confiável, orientado a conexão e reconhecido.
-   **SFTP** - Protocolo de transferência de arquivos SSH. Como uma extensão do protocolo Secure Shell (SSH), o SFTP pode ser usado para estabelecer uma sessão segura de transferência de arquivos na qual a transferência é criptografada. SSH é um método para login remoto seguro que normalmente é usado para acessar a linha de comando de um dispositivo.
-   **TFTP** - Protocolo de Transferência de Arquivos Trivial. Um protocolo de transferência de arquivos simples e sem conexão com entrega de arquivos não confirmada e de melhor esforço. Ele usa menos sobrecarga que o FTP.

Web e serviço Web

-   **HTTP** - Protocolo de transferência de hipertexto. Um conjunto de regras para a troca de texto, imagens gráficas, som, vídeo e outros arquivos multimídia na World Wide Web.
-   **HTTPS** - HTTP seguro. Uma forma segura de HTTP que criptografa os dados que são trocados pela World Wide Web.
-   **REST** - Representational State Transfer. Um serviço Web que utiliza interfaces de programação de aplicações (APIs) e pedidos HTTP para criar aplicações Web.

### Camada de transporte

Conexão orientada

-   **TCP** - Protocolo de controle de transmissão. Permite a comunicação confiável entre processos executados em hosts separados e fornece transmissões confiáveis e reconhecidas que confirmam a entrega bem-sucedida.

Sem Conexão

-   **UDP** - Protocolo de datagrama do usuário. Permite que um processo em execução em um host envie pacotes para um processo em execução em outro host. No entanto, o UDP não confirma a transmissão bem-sucedida do datagrama.

### Camada de Internet

Protocolo IP (Internet Protocol)

-   **IPv4** - Protocolo da Internet versão 4. Recebe segmentos de mensagem da camada de transporte, empacota mensagens em pacotes e endereça pacotes para entrega de ponta a ponta através de uma rede. O IPv4 usa um endereço de 32 bits.
-   **IPv6** - IP versão 6. Semelhante ao IPv4, mas usa um endereço de 128 bits.
-   **NAT** - Tradução de endereços de rede. Converte endereços IPv4 de uma rede privada em endereços IPv4 públicos globalmente exclusivos.

Mensagens

-   **ICMPv4** - Protocolo de mensagens de controle da Internet para IPv4. Fornece feedback de um host de destino para um host de origem sobre erros na entrega de pacotes.
-   **ICMPv6** - ICMP para IPv6. Funcionalidade semelhante ao ICMPv4, mas é usada para pacotes IPv6.
-   **ICMPv6 ND** - descoberta de vizinho ICMPv6. Inclui quatro mensagens de protocolo que são usadas para resolução de endereço e detecção de endereço duplicado.

Protocolos de roteamento

-   **OSPF** - Abrir o caminho mais curto primeiro. Protocolo de roteamento de estado de link que usa um experimento hierárquico baseado em áreas. OSPF é um protocolo de roteamento interno padrão aberto.
-   **EIGRP** - Protocolo de roteamento de gateway interno aprimorado. Um protocolo de roteamento de padrão aberto desenvolvido pela Cisco que usa uma métrica composta com base na largura de banda, atraso, carga e confiabilidade.
-   **BGP** - Protocolo de gateway de fronteira. Um protocolo de roteamento de gateway externo padrão aberto usado entre os Internet Service Providers (ISPs). O BGP também é comumente usado entre os ISPs e seus grandes clientes particulares para trocar informações de roteamento.

### Camada de acesso à rede

Resolução de endereços

-   **ARP** - Protocolo de Resolução de Endereço. Fornece mapeamento de endereço dinâmico entre um endereço IPv4 e um endereço de hardware.
    
    **Observação**: Você pode ver outro estado de documentação que o ARP opera na Camada da Internet (Camada OSI 3). No entanto, neste curso, afirmamos que o ARP opera na camada de Acesso à Rede (OSI Camada 2) porque seu objetivo principal é descobrir o endereço MAC do destino. Um endereço MAC é um endereço da camada 2.

Protocolos de link de dados

-   **Ethernet** - define as regras para os padrões de fiação e sinalização da camada de acesso à rede.
-   **WLAN** - Rede local sem fio. Define as regras para sinalização sem fio nas frequências de rádio de 2,4 GHz e 5 GHz.

## Organizações padronizadoras da internet

Existem organizações que visam promover e criar padrões para a Internet e o protocolo TCP / IP.

- **Internet Society (ISOC)** - Responsável por promover o desenvolvimento aberto e a evolução do uso da internet em todo o mundo.
- **Corporação da Internet para Nomes e Números Atribuídos (ICANN)** - coordena a alocação de endereços IP, o gerenciamento de nomes de domínio e a atribuição de outras informações usadas nos protocolos TCP/IP.
- **Autoridade para Atribuição de Números da Internet (IANA)** - Responsável pra supervisão e gerenciamento da alocação de endereços IP, gerenciamento de nomes de domínio e identificadores de protocolo da ICANN.

## Encapsulamento de dados

À medida que os dados da aplicação são passados pela pilha de protocolos em seu caminho para serem transmitidos pelo meio físico de rede, várias informações de protocolos são adicionadas em cada nível.

> O formato que uma parte de dados assume em qualquer camada é chamado de **unidade de dados de protocolo (PDU)**.

- Dados - termo generico para a PDU usada na camada de aplicação
- Segmento - PDU da camada de transporte
- Pacote - PDU da camada de rede
- Quadro - PDU da camada de enlace de dados
- Bits - PDU da camada física usada ao transmitir dados fisicamente pela mídia.

# Sistema de numeração binário

## Numeração decimal

Os endereços IPv4 começam como binários, uma série de apenas 1s e 0s. Eles são difíceis de gerenciar, portanto, os administradores de rede devem convertê-los em decimal. É importante compreender o binário porque hosts, servidores e dispositivos de rede usam esse tipo de endereçamento.

![](https://i4us.com.br/wp-content/uploads/2021/03/DEC-BIN-Posicional-01.jpg)

## Numeração hexadecimal

Para entender endereços IPv6 e endereços MAC Ethernet, você deve ser capaz de converter hexadecimal para decimal e vice-versa. Assim como decimal é um sistema numérico de base dez, hexadecimal é um sistema de dezesseis bases.

![[hexadecimal.png]]

# Modelo OSI

### Camada Física (Camada 1)

Seja na conexão com uma impressora local em casa ou em um site em outro país, antes que ocorra qualquer comunicação em rede, é necessário estabelecer uma conexão física com uma rede local. Uma conexão física pode ser uma conexão com fio usando um cabo ou uma conexão sem fio usando ondas de rádio.

As placas de interface de rede (NICs) conectam um dispositivo à rede. As NICs Ethernet são usadas para uma conexão com fio, como mostrado na figura, enquanto as NICs da rede local sem fio (WLAN) são usadas para a conexão sem fio.

Os padrões da camada física abordam três áreas funcionais:

- Componentes Físicos;
- Codificação;
- Sinalização.

> **Largura de Banda** - Largura de banda é a capacidade na qual um meio pode transportar dados e é normalmente medida em kilobits por segundo (kbps), megabits por segundo (Mbps) ou gigabits por segundo (Gbps).

Os termos usados para medir a qualidade da **largura de banda** incluem:

**Latência** - O termo latência se refere ao tempo necessário para os dados viajarem de um ponto a outro, incluindo atrasos.

**Taxa de transferência** - Taxa de transferência é a medida da transferência de bits através da mídia durante um determinado período. A taxa de transferência geralmente é menor que a largura de banda. Existem muitos fatores que influenciam a taxa de transferência:

-   A quantidade de tráfego;
-   O tipo de tráfego;
-   A latência criada pelo número de dispositivos de rede encontrados entre a origem e o destino.

**Dados úteis** - Há uma terceira medida para avaliar a transferência de dados utilizáveis; é conhecido como goodput. Goodput é a medida de dados usáveis transferidos em um determinado período. Goodput é a taxa de transferência menos a sobrecarga de tráfego para estabelecer sessões, reconhecimentos, encapsulamento e bits retransmitidos. O goodput é sempre menor que a taxa de transferência, que geralmente é menor do que a largura de banda.

### Camada de Enlace de Dados (Camada 2) - Data Link

A camada de enlace de dados é responsável pela placa de interface de rede (NIC) para comunicações de placa de interface de rede. **A camada de enlace de dados prepara os dados de rede para a rede física.**

A camada de enlace de dados é responsável pela troca de quadros entre os nós em uma mídia de rede física. A camada de enlace de dados executa dois serviços básicos:

-   Ele aceita pacotes da camada 3 e os encapsula em quadros.
-   Ele fornece controle de acesso à mídia e realiza a detecção de erros.

As organizações de engenharia que definem padrões e protocolos abertos que se aplicam à camada de acesso à rede incluem: IEEE, ITU, ISO e ANSI.

Os padrões IEEE 802 LAN/MAN são específicos para LANs Ethernet, LANs sem fio (WLAN), redes pessoais sem fio (WPAN) e outros tipos de redes locais e metropolitanas. A camada de link de dados LAN/MAN IEEE 802 consiste nas seguintes duas subcamadas:

-   **Logical Link Control (LLC)** - Esta subcamada IEEE 802.2 comunica entre o software de rede nas camadas superiores e o hardware do dispositivo nas camadas inferiores. Ela coloca a informação no quadro que identifica qual protocolo de camada de rede está sendo usado para o quadro. Essas informações permitem que vários protocolos da camada 3, como IPv4 e IPv6, usem a mesma interface de rede e mídia.
-   **Controle de Acesso a Mídia (MAC)** — Implementa esta subcamada (IEEE 802.3, 802.11 ou 802.15) no hardware. É responsável pelo encapsulamento de dados e ***controle de acesso à mídia***. Ele fornece endereçamento de camada de link de dados e é integrado com várias tecnologias de camada física.

**São também funções da subcamada MAC: verificar se há erros em bits recebidos; usar CSMA/CD ou CSMA/CA para oferecer suporte à tecnologia Ethernet.**

O padrão Ethernet 802.3 especifica que uma rede implementa o método de controle de acesso CSMA/CD.
 
A camada de link de dados prepara os dados encapsulados (geralmente um pacote IPv4 ou IPv6) para o transporte pela mídia local, encapsulando-o com um cabeçalho e um trailer para criar um quadro.

O protocolo de link de dados é responsável pelas comunicações NIC para NIC dentro da mesma rede. Embora existam muitos protocolos de camada de enlace de dados diferentes que descrevem os quadros de camada de enlace de dados, cada tipo de quadro tem três partes básicas:

-   Cabeçalho;
-   Dados;
-   Trailer.

Quadros Ethernet são identificados na camada de link de dados por seus endereços MAC, que são exclusivos de cada NIC.

Topologias físicas mostram a interconexão física de dispositivos. As topologias lógicas mostram a maneira como a rede transfere os dados entre os nós conectados.

Os dados transmitidos pela rede podem fluir usando um dos três modos:

- **Simplex** — Os dados só podem fluir em uma direção. 
- **Half-duplex** - Os dados fluem em uma direção de cada vez. 
- **Full-duplex** - Os dados fluem em ambas as direções ao mesmo tempo.

**ENCAPSULAMENTO ETHERNET**

A Ethernet é uma das duas tecnologias de LAN usadas atualmente, sendo a outra LANs sem fio (WLANs). A Ethernet utiliza comunicações **com fios**, incluindo par trançado, ligações de fibra óptica e cabos coaxiais.

Ela opera na camada de enlace de dados e na camada física. Os padrões Ethernet definem os protocolos da camada 2 e as tecnologias da camada 1.

O tamanho mínimo de quadro Ethernet é 64 bytes e o máximo é 1518 bytes. Isso inclui todos os bytes do campo de endereço MAC de destino através do campo FCS (Frame Check Sequence). Se o tamanho de um quadro transmitido for menor que o mínimo ou maior que o máximo, o dispositivo receptor descarta o quadro.

![[quadro ethernet.png]]

Quando os protocolos da camada superior se comunicam uns com os outros, os dados fluem para baixo pelas camadas OSI (Open Systems Interconnection) e são encapsulados dentro de um quadro da Camada 2. A composição do quadro depende do tipo de acesso ao meio. Por exemplo, se os protocolos de camada superior forem TCP/IP e o acesso ao meio for Ethernet, o encapsulamento do quadro da Camada 2 será Ethernet II. Isso é comum em um ambiente de LAN.

**ENDEREÇO MAC**

Um endereço MAC Ethernet é um endereço de 48 bits expresso usando 12 dígitos hexadecimais, Quando um fornecedor atribui um endereço MAC a um dispositivo ou interface Ethernet, o fornecedor deve fazer o seguinte:

-   Use sua OUI atribuída como os primeiros 6 dígitos hexadecimais.
-   Atribua um valor exclusivo nos últimos 6 dígitos hexadecimais.

Por exemplo, suponha que a Cisco precisa atribuir um endereço MAC exclusivo a um novo dispositivo. O IEEE atribuiu à Cisco um OUI de **00-60-2F**. A Cisco configuraria o dispositivo com um código de fornecedor exclusivo, como **3A-07-BC**. Portanto, o endereço MAC Ethernet desse dispositivo seria **00-60-2F-3A-07-BC.**

Quando uma NIC recebe um quadro Ethernet, examina o endereço MAC de destino para verificar se corresponde ao endereço MAC físico armazenado na RAM. Se não houver correspondência, o dispositivo descartará o quadro. Caso haja, ele passará o quadro para cima nas camadas OSI, onde o processo de desencapsulamento ocorre.

As NICs Ethernet também aceitarão quadros se o endereço MAC de destino for uma transmissão ou um grupo multicast do qual o host é membro.

O processo que um host de origem usa para determinar o endereço MAC de destino associado a um endereço IPv4 é conhecido como ARP (Address Resolution Protocol). O processo que um host de origem usa para determinar o endereço MAC de destino associado a um endereço IPv6 é conhecido como ND (Neighbour Discovery Discovery).

> endereço MAC de broadcast FF-FF-FF-FF-FF-FF
> endereço MAC multicast 01-00-5E (primeiros 24 bits) - Ele permite que um dispositivo de origem envie um pacote para um grupo de dispositivos.

Um switch cria uma tabela de endereços MAC inspecionando os quadros da camada 2 recebidos e registrando o endereço MAC origem encontrado no cabeçalho do quadro. O endereço MAC detectado e registrado é então associado à porta usada para receber o quadro.

### Camada de Rede (camada 3)

A camada de rede, ou Camada OSI 3, fornece serviços para permitir que dispositivos finais troquem dados entre redes.

> Os pacotes IP podem trafegar por diferentes meios físicos. - sinais elétricos, sinais ópticos ou sinais de rádio

Para realizar comunicações de ponta a ponta através dos limites da rede, os protocolos de camada de rede executam quatro operações básicas:

-   **Endereçamento de dispositivos finais** - Os dispositivos finais devem ser configurados com um endereço IP exclusivo para identificação na rede.
-   **Encapsulamento -** A camada de rede encapsula a unidade de dados de protocolo (PDU) da camada de transporte em um pacote. O processo de encapsulamento adiciona informações de cabeçalho IP, como os endereços IP dos hosts origem (emissor) e destino (receptor). O processo de encapsulamento é executado pela origem do pacote IP.
-   **Roteamento -** A camada de rede fornece serviços para direcionar os pacotes para um host de destino em outra rede. Para trafegar para outras redes, o pacote deve ser processado por um roteador. A função do roteador é escolher o melhor caminho e direcionar os pacotes para o host de destino em um processo conhecido como roteamento. Um pacote pode atravessar muitos roteadores antes de chegar ao host de destino. Cada roteador que um pacote atravessa para chegar ao host de destino é chamado de salto.
-   **Desencapsulamento -** Quando o pacote chega na camada de rede do host de destino, o host verifica o cabeçalho IP do pacote. Se o endereço IP de destino no cabeçalho corresponder ao seu próprio endereço IP, o cabeçalho IP será removido do pacote. Depois que o pacote é desencapsulado pela camada de rede, a PDU resultante da Camada 4 é transferida para o serviço apropriado na camada de transporte. O processo de desencapsulamento é executado pelo host de destino do pacote IP.