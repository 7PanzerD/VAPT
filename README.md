# VAPT
VAPT

# netdiscover
Command | Explanation
sudo netdiscover | Auto-scans your current subnet to find live hosts.
sudo netdiscover -r 192.168.1.0/24 | Scans a specific subnet range manually.
sudo netdiscover -f | Performs a fast scan with less accuracy.
sudo netdiscover -i eth0 | Uses a specific network interface (e.g., eth0 or wlan0).
sudo netdiscover -r 192.168.1.0/24 > output.txt | Saves scan results to a text file.
sudo netdiscover -s | Continuously scans and updates live devices in real-time.
sudo netdiscover -p | Passive mode: silently listens to ARP traffic without sending packets.
