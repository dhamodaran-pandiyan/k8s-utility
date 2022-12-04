# netshoot

#####netshoot: a Docker + Kubernetes network trouble-shooting swiss-army container

Reference: https://github.com/nicolaka/netshoot
```
   $ kubectl exec -it nginx-netshoot-7f9c6957f8-kr8q6 -c netshoot -- /bin/zsh
                       dP            dP                           dP
                       88            88                           88
   88d888b. .d8888b. d8888P .d8888b. 88d888b. .d8888b. .d8888b. d8888P
   88'  `88 88ooood8   88   Y8ooooo. 88'  `88 88'  `88 88'  `88   88
   88    88 88.  ...   88         88 88    88 88.  .88 88.  .88   88
   dP    dP `88888P'   dP   `88888P' dP    dP `88888P' `88888P'   dP

   Welcome to Netshoot! (github.com/nicolaka/netshoot)


   nginx-netshoot-7f9c6957f8-kr8q6 $ 
```

Included Packages: The following packages are included in netshoot. We'll go over some with some sample use-cases.


```
apache2-utils
bash
bind-tools
bird
bridge-utils
busybox-extras
calicoctl
conntrack-tools
ctop
curl
dhcping
drill
ethtool
file
fping
httpie
iftop
iperf
iproute2
ipset
iptables
iptraf-ng
iputils
ipvsadm
jq
libc6-compat
liboping
mtr
net-snmp-tools
netcat-openbsd
netgen
nftables
ngrep
nmap
nmap-nping
openssl
py-crypto
py2-virtualenv
python2
scapy
socat
strace
swaks
tcpdump
tcptraceroute
termshark
tshark
util-linux
vim
websocat
```

