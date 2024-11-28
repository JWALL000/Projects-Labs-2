## Project Overview

In this project, I analyzed packet captures using Wireshark on Ubuntu Linux. I identified malicious IP addresses with VirusTotal, calculated the total data transferred between IP addresses, and utilized the MITRE ATT&CK framework to determine attack techniques. 

![Security Operations 1](https://github.com/user-attachments/assets/d4e3a332-11e2-4638-9633-1f30cd111fa2) 



## Steps:

## Step 1:
I opened the packet capture in Wireshark to examine the network traffic details.
![Security Operations 2](https://github.com/user-attachments/assets/dcb4ac85-1f45-4d5c-8fe6-89ad1368e8c7)



## Step 2:
I noted the suspicious IP addresses that were transferring data across the network.![Security Operations 2](https://github.com/user-attachments/assets/d1ebaf18-8dc5-4c5e-b2c4-db98be1deeb0)





## Step 3:
I analyzed the IP addresses in VirusTotal to gather more information about their origins and confirm whether they were malicious.
![Security Operations 3(malicious IP](https://github.com/user-attachments/assets/ae194d0c-617f-41d7-b22c-26ae6cd2aa0f)



## Step 4: 
After confirming that the IPs were malicious, I used the conversation filter in Wireshark to measure the amount of data transferred from the malicious IPs during the specified time period.
![Security Operations 3(total data transfered](https://github.com/user-attachments/assets/e86f26dd-a275-4536-807c-756b4afc41e1)



## Step 5: 
I retrieved the ASN numbers of the two IP addresses. Using OSINT tools, I identified the cybercrimes historically associated with the IPs (cryptomining) and mapped them to the corresponding MITRE ATT&CK technique.
![Security Operations 8(](https://github.com/user-attachments/assets/044875cd-eaa1-4bcf-8df5-ba1d6447270c)



## Step 6:
I used Wireshark to determine the timestamp for the first TXT record query since the beginning of the capture. 
![Security Operations 4(](https://github.com/user-attachments/assets/337c73da-1680-45d6-b28b-1e979d47e211)



## Step 7:
I referred to the MITRE ATT&CK website to find the technique number for the next observed attack type.
![Security Operations 6(](https://github.com/user-attachments/assets/ec33a683-db7a-4d82-9c0d-7a22c63dbbb3)



## Step 8:
I successfully completed the BTLO lab "Piggy."


