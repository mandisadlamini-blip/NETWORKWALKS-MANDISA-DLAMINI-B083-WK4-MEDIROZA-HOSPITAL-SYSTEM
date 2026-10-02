# NETWORKWALKS-MANDISA-DLAMINI-B083-WK4-MEDIROZA-HOSPITAL-SYSTEM
## Mediroza General Hospital — Penetration Testing Project
As part of my penetration-testing internship, I completed a controlled black-box security assessment of the Mediroza General Hospital lab environment.

## 🔎What I Worked On
Performed web reconnaissance and enumeration
Analyzed robots.txt and sitemap.xml
Identified an exposed legacy /old/ directory
Discovered an accessible database backup
Analyzed the SQL backup for sensitive information
Identified exposed staff salary records
Identified exposed shareholder/ownership information
Extracted PDF password hashes using pdf2john
Used John the Ripper to recover passwords for three protected PDF reports
Decrypted the recovered PDF files
Extracted and documented the recovered report contents
Produced a formal penetration-testing report with evidence, impact, and remediation recommendations
<img width="959" height="520" alt="Week4-patientpdffiles" src="https://github.com/user-attachments/assets/e6f544f7-606a-4433-8db2-bcbf81979d77" />
<img width="497" height="139" alt="shareholders" src="https://github.com/user-attachments/assets/2a8bb3f4-6dae-4fe5-8d02-c96685f59b60" />
<img width="497" height="384" alt="Salary tables" src="https://github.com/user-attachments/assets/693c23b9-8bd7-455d-9352-dc1e69804ad8" />
<img width="945" height="518" alt="password-for-pdf3-craacked" src="https://github.com/user-attachments/assets/f849276f-af38-447b-bf04-75927a7e69e4" />
<img width="958" height="522" alt="password-cracked-for-pdf2" src="https://github.com/user-attachments/assets/ecfee0db-69e1-4bb0-b1f2-24ccb6233741" />
<img width="951" height="521" alt="password cracked for pdf1" src="https://github.com/user-attachments/assets/9736e8a9-4e3e-4c76-b06b-1247e962c113" />
<img width="372" height="123" alt="passW pdf3" src="https://github.com/user-attachments/assets/816d52b9-e494-4aa6-a56e-fa3e3e46791e" />
<img width="407" height="161" alt="passW pdf2" src="https://github.com/user-attachments/assets/96e000b5-44ce-4ba3-8edf-95c2c14803cb" />
<img width="357" height="146" alt="passw pdf1" src="https://github.com/user-attachments/assets/70c5c719-c827-4793-8c6e-c767a2e0d0f8" />

## 🛠️ Tools Used
* Kali Linux
* Nmap
* cURL
* wget
* pdf2john
* John the Ripper
* qpdf
* pdftotext
* Linux CLI
  
## Key Finding

One of the major findings was a publicly accessible legacy database backup:

/old/mediroza_db_backup_2019.sql

The backup contained sensitive staff and shareholder information, demonstrating the security risks associated with leaving database backups in web-accessible directories.

## 🎯 Key Learning

This project strengthened my practical understanding of:

* Web enumeration
* Information disclosure
* Password cracking
* PDF security
* Sensitive-data exposure
* Linux command-line investigation
* Evidence collection
* Vulnerability reporting

  

#CyberSecurity #PenetrationTesting #EthicalHacking #KaliLinux #JohnTheRipper #WebSecurity #InfoSec #CyberSecurityStudent #Pentesting #NetworkWalk
