Tags: #criptografia 


## Segurança e Serviços

##### Segurança é um processo

Processo que envolve analisar qual o tipo de ataque o sistema está sujeito, que tipo de informação dentro do seu sistema você quer proteger , analisar o risco e implemntar políticas de controle. 

##### Serviços de Segurança

Há diferentes aspectos que caracterizam a segurança de um sistema de computadores, estes são denominados serviços de segurança.

Serviços básicos de segurança:

- Disponibilidade
- Confidencialidade
- Integridade
- Autenticidade
- Irretratabilidade

**Autenticidade** - garantia de que o originador de uma mensagem seja corretamente identificado pelo seu destinatário.

**Irretratabilidade** - O emissor e o destinatário das informações não podem negar a sua transmissão, recepção ou posse.



## Criptografia

- Não é possivel implementar disponibilidade
- Não há algoritmo criptograffico que proteja contra ataques físicos
- Solução costuma envolver redundância e controle de acesso físico

##### Algoritmos criptográficos

Existem dois tipos básicos de algoritmos criptográficos:

**Simétricos** - usam a mesma chave conhecida apenas por remetente e destinatário, mas não por atacantes.

**Assimétricos** - usam duas chaves distintas, porém relacionadas matematicamente. Uma chave é tornada pública (conhecida inclusive por atacantes) e a outra é conhecida apenas pelo seu dono.


**Ataque de Força-Bruta**
Ataque onde se testam todas as chaves possíveis e verifica-se o resultado, quebrando o sistema criptográfico.



## Esteganografia

Disfarça os dados através de uma **mensagem de cobertura** (ex: imagens).

#### Bit menos significativo (LSB)
- Alteração dos pixels da imagem
- Pouco utilizado devido a pouca capacidade de "armazenamento"

#### Embaralhar os dados: cifras
- Ex: HTTP vs HTTPS
- No HTTP os dados passam em aberto na rede
- Enquanto que no HTTPS os dados são cifrados (túnel TLS)


##### Cifra Simétrica

Transformação matemática reversível: cifração e decifração. Onde os dois processos dependem de uma mesma informação secreta (chave). Se a chave for descoberta, a confidencialidade é perdida.

- **DES (Data Encryption Standad)**
- **3DES (DES triplo): aplicação tripla do DES
- **RC4 (ArcFour)** 
- **AES (Advanced Encryption Standard)**: Padrão atual


