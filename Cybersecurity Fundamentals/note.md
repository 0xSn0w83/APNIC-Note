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





