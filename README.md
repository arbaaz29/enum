# OpenSSHD User Enumeration
A simple script that takes advantage of OpenSSHD 7.2p2 - User Enumeration: CVE 2016-6210.

Can take a list of usernames and try them against a server -- looks to find users in the system. Built from the sample code specified at https://www.exploit-db.com/exploits/40113/

Usage:
```bash
pip3 install -r requirements.txt

pyhton3 en.py [options] [host]
options:
-U - user lists
-h - help
-u - user
-e - show enumerated
-s -silent
```

