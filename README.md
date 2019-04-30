# F.A.Q
DNS Hacker

<div align="center">
    <img src="http://oi63.tinypic.com/33dfc4m.jpg" width="400px"</img> 
</div>


# About DNS HACKER
DNS Resolver is a software service running on any computer, in this case MIRC/IRC Network. DNS Resolver service forwards DNS 
Queries to the DNS Server, in this case MIRC/IRC DNS Server for Name Resolution, on behalf of Operating System using DNS
Resolver (a DNS Client) and other applications, this is where DNS Resolver ask DNS Name Server to provide information and
resolve specific IP to Address. This will cause our DNS query to resolve for DNS Server going from MIRC/IRC Server to
victim DNS, once resolve, we can access victim pc shares or null shares remotly, as if we are into victim local network.
- Types of Access
1. Read, write or both
2. Vhost Networks
5. If you are connected to null shares, you will see something like routers, printers, scanners, remote machines
6. If you see $, it means that is unix
7. If you are stuck at access, you will still know victim exact username or list of usernames available

# Things to remember
1. Windows: Change victim hosts files or regedit remotely
2. *nix based system, obtain /etc/shadow /etc/passwd /etc/services
3. Works on Windows/*nix/mac and LAN/WLAN/NAT but not on websites/web systems
4. Do not over due victims, wait 24 hours otherwise you will over load DNS
5. If victim is resolved it can be hacked, if not then no

# How-To Section
1. Load the script and find any victim
2. Command: /dns Victim_IP
3. On Windows: Start menu then run enter \\\VICTIM_IP that is resolved (you will see new window)
4. On Linux: Smbclient //VICTIM_IP (with or without other parameters, if neccessary)
