
## Network Fundamentals

### Tipos de Redes

As redes de computadores são geograficamente divididas em muitos grupos de acordo com seu tamanho. Pode haver grandes redes com milhões de dispositivos nelas e pequenas redes compostas por 2-3 dispositivos.

##### Personal Area Network (PAN)

Rede de área pessoal (PAN) refere-se a redes com um número mínimo e pequeno de dispositivos que cobrem distâncias muito curtas (por exemplo, até 10 metros). Por exemplo, um dispositivo móvel e um fone de ouvido sem fio conectado via Bluetooth são exemplos desse tipo de rede. 

##### Local Area Network (LAN)

O fato de suportar muito mais do que 2 dispositivos em termos de capacidade e estar geograficamente espalhado por uma área mais ampla indica que é uma rede do tipo LAN.  É o tipo de rede mais comumente usado e encontrado.

Ex: Redes domésticas

##### Metropolitan Area Network (MAN)

A Metropolitan Area Network (MAN) é uma rede de computadores geograficamente dimensionada para uma cidade na qual muitas redes de computadores LAN estão interconectadas.

##### Wide Area Network (WAN)

Wide Area Network (WAN) é a rede de computadores com a maior área geográfica entre as redes de computadores. Essa rede de computadores é tão grande que pode conter até mesmo continentes. Ele hospeda todas as outras redes de computadores dentro dele. Um exemplo dessa rede de computadores é a "Internet".


### Modelo de Referência OSI

O modelo de referência Open Systems Interconnection (OSI) foi desenvolvido pela ISO (International Organization of Standardization) em 1978. O modelo OSI é um modelo com arquitetura em camadas criado para possibilitar a comunicação entre diferentes sistemas operacionais.

##### Camada Física

Nesta camada, os dados são transmitidos em bits ao longo dos canais de comunicação. Como a camada física é responsável apenas pela transmissão dos dados, ela não possui nenhuma informação sobre o tipo de dados que transmite e quais são. 

##### Camada de enlace

Essa camada processa os bits da camada física e os prepara para serem enviados à próxima camada. A operação básica nesta camada é o endereçamento físico.  

##### Camada de rede

A camada de rede é responsável por entregar os dados ao endereço lógico de destino (Endereço IP).   

##### Camada de Transporte

A camada de transporte é responsável pela segurança da transmissão. Essa camada fornece muitos controles adicionais para transmissão de dados sem erros e, graças a esses controles, a transmissão de dados é realizada com sucesso.  

##### Camada de Sessão

A camada de sessão é responsável por fornecer os serviços necessários para o funcionamento da camada de apresentação. A principal operação nesta camada é o gerenciamento de sessões.  

##### Camada de Apresentação

A camada de apresentação é a camada onde os dados são exibidos. Dois nós comunicantes devem usar uma linguagem comum para representação de dados. Graças a esta camada, o acordo é feito no idioma utilizado.  

##### Camada de Aplicação

A camada de aplicação é a camada mais próxima do usuário e fornece acesso às estruturas encontradas no modelo OSI em nível de usuário. 


### Dispositivos de rede

##### Switch

O switch é o dispositivo de interconexão e é usado para conectar os nós que desejam se conectar à rede. Opera na camada de enlace ou na camada de rede (quando possuem recursos mais gerenciáveis).

##### Router (roteador)

É um equipamento de rede utilizado colocando-o entre duas redes de computadores e tem como tarefa básica o roteamento de pacotes, sendo frequentemente usado, por exemplo, em conexões WAN-LAN. Opera na camada de rede.

##### Hub

O dispositivo hub possui uma estrutura bastante simples e é um dos dispositivos utilizados para conectar computadores que desejam se conectar à rede. Camada física

##### Repetidor

Existem apenas 2 portas no dispositivo repetidor. Essas portas transformam o sinal de entrada em um sinal de saída e o transmitem ao destino. Opera na camada física.

##### Bridge

A bridge realiza o roteamento de pacotes conectando duas redes de computadores. Embora tenha uma função semelhante a um roteador, é um dispositivo muito simples com menos portas que um roteador. Camada de enlace

##### Modem

Os modems geralmente são equipamentos de rede de pequeno porte, nos quais as características de alguns dispositivos, como switches, são reunidas.

##### Firewall

Um firewall é vital para o hardware de rede localizado entre a internet, que é considerada uma rede insegura, e a rede existente. A tarefa do firewall, que é um dos equipamentos básicos de rede necessários para garantir a segurança da rede, é bloquear ou permitir o tráfego de acordo com determinadas regras. Opera na camada de transporte.


### TCP/IP

Com este modelo, determinou-se como deveria ser a comunicação da rede com base na internet. O modelo TCP/IP tem uma arquitetura em camadas e consiste em 4 camadas:  
  
-   Camada de aplicação
-   Camada de transporte
-   Camada de Internet
-   Camada de acesso à rede

##### Camada de acesso à rede

Corresponde às camadas física e de enlace no modelo de referência OSI. Esta camada inclui acessos físicos e controles de hardware.  

##### Camada de Internet

A camada Internet tem funções semelhantes à camada de rede no modelo de referência OSI. Nesta camada, as funções de comunicação de rede são executadas por endereçamento lógico.  

##### Camada de transporte

A camada de transporte tem funções semelhantes à camada de transporte no modelo de referência OSI. Nesta camada, a transmissão de dados é feita e a confiabilidade da comunicação é garantida. 

##### Camada de aplicação

A camada de Aplicação cobre todas as operações realizadas nas camadas sessão, apresentação e aplicação do modelo de referência OSI. Os controles e operações no nível do aplicativo são executados nessa camada.


### Modelo OSI vs. Modelo TCP/IP

Embora o modelo de referência OSI e o modelo TCP/IP sejam modelos muito semelhantes, eles diferem entre si em alguns pontos. Quando o modelo TCP/IP surgiu pela primeira vez, surgiu por necessidade, não com o objetivo de ser um padrão. O modelo de referência OSI, por outro lado, visava projetar a rede de comunicação ideal. 


### Pratique

Você poderá realizar as atividades práticas [clicando aqui](https://app.letsdefend.io/training/lessons/network-fundamentals)

![[Pasted image 20230112105826.png]]