
Tags: #network #blueteam #tcp/ip #ssh #htto #sniffing #wireshark


## Dispositivos de Rede (Network Devices)

#### Roteador

Um roteador é um dispositivo de rede que encaminha dados com base em um endereço lógico. No caso de redes TCP/IP, o roteador encaminharia os dados com base nos endereços IP dos sistemas. Se você estiver em sua rede doméstica e quiser visitar o Google.com, sua solicitação irá para o roteador (o DNS converterá o nome de domínio Google.com no endereço IP) e sua solicitação será enviada pela Internet para o IP do servidor da web do Google.com.

#### Hub

Um hub é um dispositivo de rede que conecta todos os dispositivos em uma rede local ou LAN. Quando um sistema envia dados para o hub em uma porta, o hub os transmite para todos os outros dispositivos conectados.

Se um invasor estiver conectado a um hub, sempre que qualquer host conectado enviar dados, eles serão enviados para todos os outros hosts, incluindo a máquina do invasor!

#### Switch

Um switch funciona como uma versão inteligente de um hub porque ele realmente entende para onde enviar dados, em vez de enviá-los para todos. Ele consegue isso usando endereços MAC como identificadores exclusivos para destinatários de dados recebidos, para que possa enviá-los ao sistema correto.

- MAC address é um identificador numérico atribuído a uma interface de rede (NIC), dispositivo Wi-Fi ou Bluetooth, usado como endereço físico em uma rede local. Esse número é único, exclusivo. Equipamentos como switches registram todos os endereços MAC dos dispositivos conectados da rede em uma tabela interna, que identifica os remetentes e destinatários, além de endereçar corretamente os pacotes de dados e criar rotas eficientes entre os dispositivos de origem e destino.

#### Bridge

Um dispositivo de ponte de rede conecta redes separadas para transformá-las em uma rede maior. Isso é diferente de um roteador, que permite que as redes sejam conectadas, mas funcionem de forma independente.

#### Firewall

Um firewall é um dispositivo de rede que fornece segurança de rede fundamental, monitorando o tráfego de entrada e saída e determinando se deve ser permitido ou bloqueado com base em regras.



## Portas e Serviços (Ports and Services)

#### **Porta 20, 21 – Protocolo de transferência de arquivos (FTP)**

Este protocolo é usado para **transferir arquivos** entre sistemas, onde os usuários podem se conectar a um produto FTP e podem visualizá-los, carregá-los ou baixá-los.

**pyftpdlib** - O que é?
	[pyftpdlib](https://pypi.org/project/pyftpdlib/) é uma biblioteca Python que implementa um Servidor FTP, fornecendo uma interface de alto nivel para facilmente escrever servidores FTP muito eficientes, escaláveis e assíncronos.


#### **Porta 22 – Secure Shell (SSH)**

O SSH permite que os usuários se conectem a um host remoto, como um servidor, se tiverem o SSH aberto. Este canal é criptografado, portanto, quaisquer dados movidos entre dois sistemas conectados não serão claramente visíveis.


#### **Porta 23 – Telnet**

Este serviço era usado antes do SSH e oferece a mesma funcionalidade, porém o Telnet não usa criptografia, portanto o tráfego pode ser capturado e lido por um invasor. O Telnet não deve ser usado devido a essa fraqueza e o SSH sempre deve ser implementado.


#### **Porta 25 – Protocolo Simples de Transferência de Correio (SMTP)**

Este protocolo é usado para enviar e-mails entre servidores dentro da rede, ou para redes externas, como pela internet. Este é apenas um método de transporte, para realmente baixar e visualizar e-mails você precisa usar um cliente de e-mail e o protocolo POP ou IMAP.


#### **Porta 53 – Sistema de Nome de Domínio (DNS)**

O DNS opera nas portas TCP e UDP 53 e usa bancos de dados relacionais para converter nomes de host e nomes de domínio legíveis por humanos (como Google.com) em seus respectivos endereços IP para que as comunicações possam ser enviadas de e para esses hosts.


#### **Porta 80 – Protocolo de transferência de hipertexto (HTTP)**

O HTTP permite que clientes (navegadores como Chrome e Firefox) se conectem a servidores da Web e solicitem conteúdo, que aparece na forma de downloads de arquivos, páginas da Web e serviços de streaming. 

Portanto, se você quiser visualizar uma página web, seu navegador fará uma solicitação HTTP ao servidor da Web, solicitando o download da página da Web em HTML. O servidor responderá com um código de status 200 (que significa “OK”, foi bem-sucedido) e enviará a página HTML para o cliente, para que você possa visualizá-la em sua tela. 

Como o HTTP não é criptografado, é possível realizar **ataques de sniffing** e ver os dados em texto puro à medida que são transmitidos entre o cliente e o servidor, como senhas.

- Sniffing
	Sniffers são programas usados para monitorar as atividades em uma conexão (ou rede), e o mais famoso deles é o Sniffer, um software de monitoramento criado e mantido pela NetScout.
	E o que é sniffing? Sniffing é o ato de monitorar atividades em uma rede através destes programas.	
	

#### **Porta 443 – Protocolo de Transferência de Hipertexto Seguro (HTTPS)**

HTTPS é uma versão segura do HTTP e tem a mesma funcionalidade de recuperar conteúdo de servidores da web. No entanto, a diferença entre os dois é que o HTTPS usa criptografia para proteger a transferência de dados entre um servidor da web e um cliente.



## Wireshark GUI

O Wireshark é um software extremamente popular e gratuito que é usado por muitos especialistas em segurança em todo o mundo para capturar e analisar o tráfego de rede em grande detalhe. O Wireshark vem com a distribuição oficial do Kali Linux, alternativamente, pode ser baixado gratuitamente em: [https://www.wireshark.org/#download](https://www.wireshark.org/#download) .


**Algumas Ferramentas Úteis:**

Statistics > Protocol Hierarchy
A janela Protocol Hierarchy exibe as porcentagens do número de pacotes ou bytes em uma conversa de protocolo em relação ao tráfego inteiro.

Statistics > Conversations
A janela Conversations também fornece uma riqueza de informações sobre o tráfego, incluindo quais hosts se comunicaram com quais hosts, em quais portas e com um total de quantos bytes e pacotes na conversa. Essa janela é ótima para identificar os diferentes endereços MAC ou IP com os quais um host se comunicou e o volume de tráfego entre eles.

Statistics > Endpoints
A janela Endpoints mostra todos os diferentes hosts que aparecem na captura e a quantidade de pacotes/bytes que eles enviaram e receberam. Essa janela é útil para classificar hosts por sua atividade de rede, por volume de transmissão ou recebimento, ou por ambos.

- TX (enviou)
- RX (recebeu)
