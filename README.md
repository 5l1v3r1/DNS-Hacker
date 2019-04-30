# F.A.Q
DNS Resolver Hack

# DNS Resolver Hack Machines
1. Windows/*nix/mac running custom DNS softwares via MIRC/IRC or sometimes outside IRC/MIRC Network
2. Even if they are behind LAN/NAT you will still get access
3. This does not work on websites/web systems

# DNS Resolver Hack Attack Method
DNS Resolver is a software service running on any computer, in this case MIRC/IRC Network. DNS Resolver service forwards DNS 
Queries to the DNS Server, in this case MIRC/IRC DNS Server for Name Resolution, on behalf of Operating System using DNS
Resolver (a DNS Client) and other applications, this is where DNS Resolver ask DNS Name Server to provide information and
resolve specific IP to Address. This will cause our DNS query to resolve for DNS Server going from MIRC/IRC Server to
victim DNS, once resolve, we can access victim pc shares or null shares remotly, as if we are into victim local network.

# Types of Access
1. There would be read access
2. There would be write access
3. There would be read/write access
4. If you see hard disk, your in luck, if you hack VHOST, you will see many hard disks in network
5. If you are connected to null shares, you will see something like routers, printers, scanners, remote machines
6. If you see $, it means that is unix
7. If you are stuck at access, you will still know victim exact username or list of usernames available

# Network Share Scanner
1. SMB and other share hack software works the same way, right? Wrong!
1. This is quite different, pc's that don't show up in network share scanners, you can still acccess them with
their $IPC/Null Shares or get a exact list of usernames, if you see $, it means that is unix

# How to Use it?
1. Load the script into IRC/MIRC Client
2. Find any victim in IRC/MIRC channel or real life victim (you know victim IP)
3. Enter /dns Victim_IP (this will using DNS and use DNS Resolving Script)
4. Once resolved, goto start menu then run enter \\VICTIM_IP that is resolve
5. In Linux enter: Smbclient //VICTIM_IP (with or without other parameters, if neccessary)

# Fun Things To Do
1. If your in luck, have full read/write access, do this:
2. Change victim hosts file 
3. You can even edit regedit if system is windows (confirm it)
4. If your into *nix based system, try to change obtain /etc/shadow /etc/passwd /etc/services
