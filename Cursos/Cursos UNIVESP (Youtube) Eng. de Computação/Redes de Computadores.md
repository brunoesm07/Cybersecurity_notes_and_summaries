Tags: #network #rede #protocolo #osi #tcp/ip 


## Rede

Sistema constituido pela interligação de dois ou mais computadores e seus periféricos, com o objetivo de comunicação, compartilhamento e intercâmbio de dados.


## Perdas e Atrasos

Se a taxa de chegada de pacotes ao link ultrapassa a capacidade do link de sáida gerará a perda de pacotes. Uma fila de pacotes esperam por sua vez, o que pode gerar um atraso. caso haja excesso de pacotes ou lentidão no processamento.

##### Fontes de Atraso de Pacotes

1. Processamento nos nós:
- Verifica erros de bit
- Determina link de saída

2. Enfileiramento
- Tempo de espera no link de saída para transmissão
- Depende do nível de congestionamento do roteador

3. Atraso na transmissão
- Tempo para empurrar todo o pacote no enlace de transmissão
- Depende do tamanho do pacote (bits) e da largura de banda (bps)

4. Atraso de propagação
- Tempo para transmitir (transportar) o pacote ao longo do enlace



## Protocolo

Conjunto de regras que definem os formatos e ordem das mensagens, assim como as ações a serem tomadas na transmissão e recepção das mensagens.

##### TCP
Serviço de rede orientado à conexão, ou seja, uma conexão deve ser criada antes de comunicar. Aplicações que usam TCP na borda da rede: HTTP (web), FTP (transferência de arquivo), SMTP (e-mail)

##### UDP
Não há necessidade de estabelecer uma conexão. Aplicações que usam UDP na borda da rede: estreaming, teleconferência, telefonia IP


## Camadas de Protocolos

Rede de computadores **modularizada** em um conjunto de camadas, onde cada uma vai desempenhar uma determinada função. Cada etapa depende da anterior, mas não é necessário saber como a etapa anterior foi realizada.

### Modelo OSI (Open Systems Interconnection) - 7 camadas

- Camada de Aplicação
- Camada de Apresentação
- Camada de Sessão
- Camada de Transporte
- Camada de Rede
- Camada de Enlace
- Camada Física

### Modelo TCP/IP - 4 camadas

- Camada de Aplicação
- Camada de Transporte
- Camada de Internet
- Camada de Acesso a Rede



