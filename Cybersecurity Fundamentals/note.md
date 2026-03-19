Module 01:

CyberSecurity Layer :- People,Process,Technology

Hacked Email:

1.Spam(Phising,Ad)
2.Hervesting(Contacts,Onedrive,Dropbox)
3.Employment
4.FInancial(Bank Acc,Billing Details)
5.Retail Resale(Amazon,eBay,Netflix)
6.Privacy(message,CHat,photo,location)

Hacked PC:

1.Web Server(Phising WebSite,Virus,Malware)
2.Bot Activity(Spam Relay , DDoS botnet,Anonymous Proxy)
3.Account Credentials(eBay,Paypal,Password Managers)
4.Financial Credentials(Personal Bank,Corporate bank)
5.Hostage Attacks(Fake Antivirus, DNS CHanger , Ransomware,Email Account Ransom)
6.Reputation Hijacking(Fb, twitter, LinkedIn,Insta)
7.Virtual Goods(OS lisence key, Gaemes lisence key)

Hacked Company:

1.Partners(Business Mail Compromised,Vpn Credentials,Phising)
2.Physical(Desktop,Server,Backups,PABX,VoIP)
3.Intellectual Property(Trade Secrets,R&D,Customer List,Stategic Plan)
4.HR Data(Employ Tax,Salary Data)
5.FInancial(Credit card data,Employee Bank Details, COrporate Bank Details,Corporate Earnings)
6.Virtual(Cloud Services,Software Licences,Website)

CyberSec Role:
1.Analyst: ensure incident response and disaster recovery plans are current and sufficient.like soc

2.Engineer: Investing new tech. to build or improve security solution within the organisation

3.Architect: Design new Security systems 

4. Auditor: works in Governence Risk and Complaince(GRC)

5. CISO(Chief Information Security Officer): Responsible for information security
develop org vision and stragity 


Module 02:

CIA Triad

Confidentiality: Prevent unauthorized people or processes from accessing data.
Integrity: Maintain and assure the accuracy and completeness of data
Availablility: Ensure info is available when needed

Asset:
What are you try to protect
Virtual asset like cloud , software
physical asset like server, pc, router


Threat: A event that apply negetive impact in asset

3 type of Threat:
1.Intentional : Hacking, Malware, DDoS
2.Accidental: Malfunctional, user error
3.Natural: Earthquakes,flood..

Vulnerability : It is a weakness in assets design or implementation

- Software Bugs

- Protocol Bugs

- Insecure Auth.

- Misconfig

- Poor Physical Security

Risk = Threat x Vuln.

Risk = Asset x Threat x Vuln.

if ASSET = Impact & (Threat x Vuln) = Likelihood
then
Risk = Impact x Likelihood

Mitigate:
The process is to reduce the seriousness or severity


Module 03: Security Controls

Layers of Security Controls

Type of Controls
- Physical: secure physical objects(like cctv, biometric etc)
-Technical: Hardware and Software( like firewalls , intrusion prevention system, anti virus or anti malware security, SIEM)
-Administrative:human factors of security (like policies, guideline , employee hiring, data classification and security trainning)

Based on Timeline layer of controls:
-Preventative: Stop Unauthorized activities
-Detective: security measures to detect and alert of unauthoried activity that are in progress or occured.
-Corrective: implement after attack. main goal is to repair damage and restore resources.


<img width="1883" height="1014" alt="image" src="https://github.com/user-attachments/assets/2e2cc99a-fa05-489f-843b-1b9de9f64af2" />


3 x 3 matrix with 9 combined scenario


Frameworks and Standards for Security Controls:

NIST CSF - voluntary guidance,based on exiting standards,guidelines and practices

5 function of NIST :

<img width="320" height="250" alt="image" src="https://github.com/user-attachments/assets/d63ee315-7cb3-4565-a0e7-9d9f1ea10884" />


ISO/IEC 27000 - series of standards is a collection of international standards focusing on information security and the related management system.

ISO/IEC 27001 - provides the requirments for an information security management system.(ISMS)

PCI DSS - Payment Card Industry Data security standard - created by a collection of mejor credit card companies

CIS Controls - Center for Internet Security or CIS 
Created by the Center for Internet Security (CIS)
Version 8 was released in May 2021
Is a prioritised list of 18 controls and actions that aim to mitigate common attacks
These controls map against other standards and guidelines, such a NIST CSF, PCI DSS, and ISO 27002
Not formally audited and certified against


**Module 4: Security Principles**
<img width="676" height="201" alt="image" src="https://github.com/user-attachments/assets/86f727da-ca08-4a0f-a417-ca60d9f66de8" />

**Fail Secure :** In the event of a failure the system responds in a way that access or data is denied. 

**Fail Safe :** In the event of failure , there is no(or minimal) harm to other systems or personnel.

Least privilege
-Minimum access and time
-old unix systems services required root privilege
-Restrict admin access and admin password
-Mobile application permission

**Compartmentalisation :**
Compartmentalisation breaks a system up into isolated units
A web server can be compartmentalised by separating out the web, application, database, and logging into separate servers.
Segregation involves the creation and enforcement of rules to control communication between compartments, such as hosts, services, or networks.
Segregation is usually performed by firewalls or access control lists.


**Principle of Simplicity**


<img width="680" height="324" alt="image" src="https://github.com/user-attachments/assets/920e0ac1-4fc5-434b-851a-679823b42416" />

**Privacy**
-Users: Only collect the Pll you need, for your published purposes
Secure the PII you collect/store
Delete the PII once the purpose is finished
-Systems:Configure systems to only expose the services and information needed
Examples:
For a public web server, allow connections to HTTPS, but not to the SQL server

**Kerckhoffs's Principle**


<img width="652" height="325" alt="image" src="https://github.com/user-attachments/assets/c0ba9174-7eca-4968-b09d-2e9826d81d0e" />


**Proportionality**

It is all about balance

<img width="611" height="184" alt="image" src="https://github.com/user-attachments/assets/608be47a-c5e0-4465-8813-dd81b46d24f8" />


**Module 05: Technical Terminology**


**Firewall:** A tool that monitor and filter network traffic based on different security rules. it can be software or hardware
Host based Firewall -

Implemented as software on servers and workstations
Allows for micro-segmentation by protecting hosts from each other
Used as an additional layer of protection from network firewalls

Network based Firewall-

Filters traffic between network boundaries
Allows for multiple high bandwidth interfaces
Software firewalls for use in VMs and cloud environments
Can function as a router

IDS(Intrution Detection System)- monitor or alert suspecious activuty

signature based - relies upon a list of attack behaviour

behaviour based- anomaly based detection

IPS(Intrution prevention System)- similar to IDS with an active response capability

like block/close TCP, Drop packets, kill processes

Network Based IDS or IPS detect network based suspecious traffic.

Host based IDS or IPS monitor local devices .

**Malware**

Virus- self replicating program that can infact other files on local computer

Worm - Spreading other computer

Trojan - intruduce as legitimate software. Tricking the user into downloading and executing it. used to install a virus or other malware


Spyware - gather info about a person or org. and sends back to attacker. violence user privacy

Ransomeware - type of malware that block access of computer until ransom is paid usually by cryptocurrency.


**Botnets:** Combination of robot and network.

malware that are remotely control . A bot is controled by a melicious attacker called bot master. bot master communicate with a large collection of bots via C2 server to perform DDos attack,Spam mail etc.

**DDoS:**
A Denial of Service is an attack aganist availability of a service.

DoS- Denial of Service. usually from only one source.Can be caused by resource exhaustion or targeted exploitation of vulnerabilities.


DDoS- Distributed Denial of Service.Same goal but utilize with many computer at a same time to overwhelm the target.commonly done using botnets.

**SOcial Engineering** is where people phychologically manipulated by clicking a link , open attachment etc.
It is Caused for 
-Authority : Attacker present himself as authority to force employee for action
-Intimidation : Attacker shows negetive impacts if not give action like exposed private pic to public.
-Urgency : Acts urgent. like limited time of discount for sales.


phishing: Type of Social engineering 
Spear Phising
Whaling
Viishing(voice phising) : VoIP
Smishing

Business Email COmpromise: Spear phising Technique

Criminal takes over an email account that is then used to:
Send fake invoices
Request updates to bank account details
Intercept and alter inbound payment details
Compromise a computer to send real invoices with attacker's bank details


**Module 6: Cryptography**

Encryption -> Chipertext

Decryption -> plaintext

Symmetric Encryption

<img width="697" height="372" alt="image" src="https://github.com/user-attachments/assets/605c44cf-b813-4da3-b386-8d13e5f44f44" />

ASymmetric Encryption

<img width="1903" height="1016" alt="image" src="https://github.com/user-attachments/assets/4aab8a53-4485-4853-9399-509ae62dce99" />


Hash Function(Hashing)

One way funtion(Cannot reversed)


<img width="679" height="282" alt="image" src="https://github.com/user-attachments/assets/78a1902d-d9cd-418d-b147-a54004a09baa" />




<img width="681" height="289" alt="image" src="https://github.com/user-attachments/assets/b5a704da-baed-4c1f-b947-b5ac62923fe4" />

