
## Phishing Email Analysis

O ataque de phishing é um tipo de ataque que visa roubar dados pessoais do usuário. Ocorre a partir de clicks em links maliciosos enviados via e-mail ou executando arquivos maliciosos no computador.

Os ataques de phishing correspondem à fase " Delivery " no modelo **Cyber ​​Kill Chain** criado para analisar ataques cibernéticos. São os vetores de ataque mais comuns para acesso inicial.

### Obtendo Informações

**Spoofing**

Os invasores podem enviar e-mails em nome de outra pessoa usando a técnica chamada falsificação para fazer o usuário acreditar que o e-mail recebido é confiável. Vários protocolos foram criados para evitar a técnica de Email Spoofing.

Com a ajuda dos protocolos SPF, DKIM e DMARC, pode-se entender se o endereço do remetente é falso ou real.

-   Sender Policy Framework (SPF)
-   DomainKeys Identified Mail (DKIM)

Os invasores podem encontrar endereços de e-mail com a ferramenta theHarvester no Kali Linux. Recomenda-se que essas informações não sejam compartilhadas explicitamente, pois manter endereços de e-mail pessoais em sites seria um vetor de ataque potencial para invasores.

### Análise de Tráfego de Email

Muitos parâmetros são necessários ao analisar um ataque de phishing. Podemos saber o tamanho do ataque e o público-alvo nos resultados da pesquisa a ser feita no gateway de correio.

As principais perguntas que precisamos responder ao verificar títulos durante uma análise de phishing:

-   O e-mail foi enviado do servidor SMTP correto?
Podemos verificar no campo "Received" from o IP. A partir dessa informação devemos confirmar se quem está enviando (remetente) o faz do mesmo domínio, consultando os servidores MX usados por este domínio e se há relação com o IP do campo "Received".

-   Os dados "From" e "Return-Path / Reply-To" são os mesmos?
Exceto em casos excepcionais, esperamos que o remetente do e-mail e o destinatário das respostas sejam os mesmos.


**Chave de domínio e assinaturas DKIM**  
  
A chave de domínio e o email identificado por chave de domínio (DKIM) são assinaturas de e-mail que ajudam os provedores de serviços de e-mail a identificar e autenticar seus e-mails, semelhantes às assinaturas SPF.

**Message-ID**  
  
O campo de cabeçalho Message-ID é uma combinação única de letras e números que identifica cada e-mail. Não há dois e-mails com o mesmo ID de mensagem.

**Versão MIME**  
  
Multipurpose Internet Mail Extensions (MIME) é um padrão de codificação da Internet. Ele converte conteúdo não textual como imagens, vídeos e outros anexos em texto para que possam ser anexados a um e-mail e enviados por SMTP (Simple Mail Transfer Protocol).

**Status X-Spam**  
  
O status X-Spam mostra a pontuação de spam de uma mensagem de e-mail.  Primeiro, ele destacará se uma mensagem for classificada como spam.  Em seguida, a pontuação de spam do e-mail é exibida, bem como o limite de spam para o e-mail. Um e-mail pode atingir o limite de spam de uma caixa de entrada ou excedê-lo. Se for muito spam e exceder o limite, será automaticamente classificado como spam e enviado para a pasta de spam.


### Análise Estática

Invasores podem criar e-mails com HTML, escondendo endereços de URL prejudiciais por trás de botões/textos que parecem inofensivos. Para analisar este caso, é possível descobrir se os mecanismos antivírus detectam o endereço da Web como prejudicial pesquisando os endereços da Web no e-mail do VirusTotal.

Porém é necessário verificar a data da última pesquisa e confrontar com a data do email.  Se, apesar da pesquisa indicar "inofensivo", deve-se verificar quando a página foi pesquisada anteriormente no VirusTotal, pois caso haja contemporaniedade pode significar que o invasor queria ver a taxa de detecção do site durante a fase de preparação.

### Análise Dinâmica

Se você deseja verificar rapidamente os endereços web contidos no e-mail, pode ver o conteúdo do site usando ambientes sandbox, navegadores web on-line, como o Browserling . O bom desses serviços é que você não será afetado por uma possível vulnerabilidade de dia zero que afeta os navegadores, já que você não acessa a página da web em seu próprio computador.

Ao examinar os arquivos nesses ambientes, você elimina o risco de infectar seu computador com malware.

O fato de não haver URLs e arquivos no e-mail não significa que isso não seja prejudicial. O invasor também pode enviá-lo como uma imagem para não ser pego nos produtos de análise.


## Ferramentas

[MXToolbox](https://mxtoolbox.com/) - Ajuda mostrando os servidores MX usados ​​pelo domínio que você pesquisou.

[VirusTotal](https://www.virustotal.com/gui/home) - Analise arquivos, domínios, IPs e URLs suspeitos para detectar malware e outras violações, compartilhe-os automaticamente com a comunidade de segurança.

[Browserling](https://www.browserling.com/) - Sandbox para testes em navegadores.

### Pratique

Você poderá realizar as atividades práticas [clicando aqui](https://app.letsdefend.io/training/lessons/phishing-email-analysis)

![](https://github.com/brunoesm07/Cybersecurity_notes_and_summaries/blob/main/Security%20Analyst%20(treinamentos)/badges/Pasted%20image%2020230111161224.png)[](https://github.com/brunoesm07/Cybersecurity_notes_and_summaries/blob/main/Security%20Analyst%20(treinamentos)/badges/Pasted%20image%2020230111161224.png)
