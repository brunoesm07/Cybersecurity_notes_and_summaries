
## CIA

A **confidencialidade** garante que os dados sejam visualizados apenas por usuários autorizados. A melhor maneira de proteger a confidencialidade dos dados é criptografá-los. Isso inclui qualquer tipo de dados, como PII, dados em bancos de dados e dados em dispositivos móveis. Os controles de acesso ajudam a proteger a confidencialidade ao restringir o acesso.

A **integridade** verifica se os dados não foram modificados. A perda de integridade pode ocorrer por meio de alterações não autorizadas ou não intencionais. Algoritmos de hash, como SHA, calculam hashes para verificar a integridade. Um hash é simplesmente um número criado pela aplicação do algoritmo a um arquivo ou mensagem em momentos diferentes. Ao comparar os hashes, você pode verificar se a integridade foi mantida.

A **disponibilidade** garante que os sistemas estejam ativos e operacionais quando necessário e geralmente aborda pontos únicos de falha. Você pode aumentar a disponibilidade adicionando tolerância a falhas e redundâncias, como RAID, clusters de failover, backups e geradores.


#### Escalabilidade (Scalability)

A escalabilidade é a capacidade de um sistema de lidar com o aumento da carga de trabalho, escalando (scaling up) ou expandindo (scaling out). Refere-se à adição ou remoção manual de recursos de um sistema para aumentá-lo ou escalá-lo.

#### Elasticidade (Elasticity)

Elasticidade é a capacidade de um sistema de lidar com uma carga de trabalho aumentada. A facilidade e velocidade de fazer essa mudança de escala, tanto para aumentar, quanto para diminuir determinará se o sistema é elástico. 

#### Redundância
 
Métodos de redundância e tolerância a falhas aumentam a disponibilidade de sistemas e dados.

#### Risco

Risco é a probabilidade de uma ameaça explorar uma vulnerabilidade. A mitigação de riscos reduz as chances de uma ameaça explorar uma vulnerabilidade ou reduz o impacto do risco implementando controles de segurança.


## Controles de Segurança

Os controles de segurança são categorizados como gerenciais (documentados em políticas escritas), operacionais (executados nas operações do dia-a-dia) ou técnicos (implementados com tecnologia).


Os **controles gerenciais** são administrativos em função e documentados em políticas de segurança. 

Os **controles operacionais** são implementados por pessoas que executam as operações diárias para cumprir o plano geral de segurança de uma organização.

Os **controles técnicos** usam a tecnologia para reduzir as vulnerabilidades. Alguns exemplos incluem criptografia, software antivírus, IDSs, IPSs, firewalls e o princípio do privilégio mínimo. A segurança física e os controles ambientais incluem detectores de movimento e sistemas de supressão de incêndio.






Preventative controls attempt to prevent security incidents. Hardening systems modifies the basic configuration to increase security. Security guards can prevent unauthorized personnel from entering a secure area. Change management processes help prevent outages from configuration changes. An account disablement policy ensures that accounts are disabled when a user leaves the organization.


Detective controls attempt to detect when vulnerabilities have been exploited. Some examples include log monitoring, trend analysis, security audits, and CCTV systems.


Administrators use ping to check the connectivity of remote systems and verify name resolution is working. They also use ping to check systems and networks’ security posture by verifying that routers, firewalls, and IPSs block ICMP traffic when configured to do so.


Windows systems use ipconfig to view network interfaces. Linux systems use ifconfig, and ifconfig can also manipulate the settings on the network interfaces. You can enable promiscuous mode on a NIC with ifconfig.

The ip command is recommended in place of ifconfig in many situations, such as viewing and manipulating NIC settings.


Comparing Identification and AAA Authentication, authorization, and accounting (AAA) work together with identification to provide a comprehensive access management system. If you understand identification (claiming an identity, such as with a username) and authentication (proving the identity, such as with a password), it’s easier to add in the other two elements of AAA—authorization and accounting.


Identification occurs when a user claims an identity, such as with a username or email address. Authentication occurs when the user proves the claimed identity (such as with a password) and the credentials are verified (such as with a password). Access control systems provide authorization by granting access to resources based on
permissions granted to the proven identity. Logging provides accounting.


Complex passwords use a mix of character types. Strong passwords use a mix of character types and have a minimum password length of at least eight characters. A password expiration identifies when a password must be changed.


Account lockout policies thwart some password attacks, such as brute force and dictionary attackers. Many applications and devices have default passwords. These should be changed before putting the application or device into service.



Smart cards are often used with dual-factor authentication where users have something (the smart card) and know something (such as a password or PIN). Smart cards include embedded certificates used with digital signatures and encryption. They are used to gain access to secure locations and to log on to computer systems.



HOTP and TOTP are open source standards used to create one-time-use passwords. HOTP creates a one-time- use password that does not expire until it is used, and TOTP creates a one-time password that expires after 30 seconds. Both can be used as software tokens for authentication.


Two-step verification methods typically use a PIN retrieved from a user’s smartphone. They can be sent via SMS, a phone call, a push notification, or retrieved from an authentication application.


The third factor of authentication (something you are, defined with biometrics) is the strongest individual authentication factor. Biometric methods include fingerprints, palm veins, retina scans, iris scans, voice recognition, facial recognition, and gait analysis.


Iris and retina scans are the strongest biometric methods mentioned in this section, though iris scans are used instead of retina scans because retina scans are intrusive and reveal private medical issues. Facial recognition and gait analysis can bypass the enrollment process when done for identification instead of authorization.


Using two or more methods in the same factor of authentication (such as a PIN and a password) is single-factor authentication. Dual-factor (or two-factor) authentication uses two different authentication factors, such as using a hardware token and a PIN. Multifactor authentication uses two or more factors.


An important concept to remember when creating accounts is to give users only the account permissions they need to perform their job, and no more.


Privileged access management (PAM) systems implement stringent security controls over accounts with elevated privileges such as administrator or root-level accounts. Some capabilities include allowing authorized users to access the administrator account without knowing the password, logging all elevated privileges usage, and automatically changing the administrator account password.


Requiring administrators to use two accounts, one with administrator privileges and another with regular user privileges, helps prevent privilege escalation attacks. Users should not use shared accounts.


Requiring administrators to use two accounts, one with administrator privileges and another with regular user privileges, helps prevent privilege escalation attacks. Users should not use shared accounts.



An account disablement policy identifies what to do with accounts for employees who leave permanently or are on a leave of absence. Most policies require administrators to disable the account as soon as possible so that ex-employees cannot use the account. Disabling the account ensures that data associated with it remains available. Security keys associated with an account remain available when the account is disabled, but the security keys (and data they encrypted) are no longer accessible if it is deleted. Time-based login restrictions prevent users from logging on or accessing network resources during specific hours.


Usage auditing records user activity in logs. A usage auditing review looks at the logs to see what users are doing and it can be used to re-create an audit trail. Permission auditing reviews help ensure that users have only the access they need and no more and can detect privilege creep issues.



Usage auditing records user activity in logs. A usage auditing review looks at the logs to see what users are doing and it can be used to re-create an audit trail. Permission auditing reviews help ensure that users have only the access they need and no more and can detect privilege creep issues.



Kerberos is a network authentication protocol within a Microsoft Windows Active Directory domain or a Unix realm. It uses a database of objects such as Active Directory and a KDC (or TGT server) to issue timestamped tickets that expire after a certain time period.

SAML is an XML-based standard used to exchange authentication and authorization information between different parties. SAML provides SSO for web-based applications.


OAuth OAuth is an open standard for authorization many companies use to provide secure access to protected resources. Instead of creating a different account for each website you access, you can often use the same account you’ve created with Google, Facebook, PayPal, Microsoft, or Twitter. You can think of OAuth as open authorization.


"Comparing Access Control Schemes Access control ensures that only authenticated and authorized entities can access resources.


Subjects. 
Subjects are typically users or groups that access an object. Occasionally, the subject may be a service that is using a service account to access an object.  

Objects. 
Objects are items such as files, folders, shares, and printers that subjects access. The access control helps determine how a system grants authorization to objects. Or, said another way, the access control scheme determines how a system grants users access to files and other resources.


Role-Based Access Control Role-based access control (role-BAC) uses roles to manage rights and permissions for users. This is useful for users within a specific department who perform the same job functions.

A role-based access control scheme uses roles based on jobs and functions. A matrix is a planning document that matches the roles with the required privileges.

Establishing Access with Group-Based Privileges Administrators commonly grant access in the role-BAC scheme using roles, and they often implement roles as groups.


Group-based privileges reduce the administrative workload of access management. Administrators put user accounts into security groups and assign privileges to the groups. Users within a group automatically inherit the privileges assigned to the group.


Rule-based access control is based on a set of approved instructions, such as an access control list. Some rule-BAC systems use rules that trigger in response to an event, such as modifying ACLs after detecting an attack or granting additional permissions to a user in certain situations.


Discretionary Access Control In the discretionary access control (DAC) scheme, objects (such as files and folders) have an owner, and the owner establishes access for the objects.


Mandatory Access Control The mandatory access control (MAC) scheme uses labels (sometimes referred to as sensitivity labels or security labels) to determine access.


The MAC scheme uses sensitivity labels for users and data. It is commonly used when access needs to be restricted based on a need to know. Sensitivity labels often reflect classification levels of data and clearances granted to individuals.