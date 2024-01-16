# ba5ic_L1nux_3num
 This repo contains resources to perform enumeration on Linux OS. *For educational purposes only and should be used ethically.

 # Information Gathering 

- uname -a
- ps aux | root
- ps aux | "user"

# User Enumeration 

- whoami
- id (for user id)
- sudo -l
- cat /etc/passwd
- cat /etc/shadow
- history (Maybe some juicy information)

# Network Enumeration

- ifconfig
- ip a (old)
- ip route
- netstat -ano (Active Internet Connections)

# Password Hunting 

- grep --color=auto -rnw '/' -ie "PASSWORD" --color=always 2> /dev/null
- grep --color=auto -rnw '/' -ie "PASSWORD=" --color=always 2> /dev/null
- grep --color=auto -rnw '/' -ie <"Anything that will help you maybe get password"> --color=always 2> /dev/null
- locate password | more
- find / -name id_rsa 2> /dev/null

