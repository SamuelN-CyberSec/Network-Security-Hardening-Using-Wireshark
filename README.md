# Network-Security-Hardening-Using-Wireshark
In this  project I used Wireshark to analyze network traffic on a  Windows 11 system connected via a network. The goal is to detect insecure communications. Misconfiguration and suspicious behavior to guide system-level hardening.

##Objectives
-Capture and analyze baseline network traffic 
-Identify unencrypted data transmission anomalies, and scanning attempts.
-Recommend and implemented security hardening measures 
-Recapture and compare results 

##Tools Used
-Wireshark
-Windows 11

## Key Findings
- No detected Plaintext HTTP traffic containing local login info
- No DNS queries to suspicious top level domain .xyz
- Low Arp broadcast activity(No potential for DoS or ARP spoofing)

##Hardening Actions
-Crossed checked  HTTPS settings to verify HTTPS is set on browser and service settings
-Blocked suspicious domain via DNS filtering 


## Result
-Significant reduction in insecure traffic 

##Screen shot
-Traffic flow
-Top level domain query
-http
-http contains "password"
-arp
-IP address detection

<img width="960" alt="Normal  Wireshark Traffic Flow" src="https://github.com/user-attachments/assets/7a73d4a8-4737-4b68-b74b-e2c15917093f" />
<img width="960" alt="Top level domain query  xyz" src="https://github.com/user-attachments/assets/2782ba22-b413-486f-94f2-fdfd17edb9c4" />
<img width="960" alt="http " src="https://github.com/user-attachments/assets/3a4f68de-baae-426b-aaeb-f2ba3c8056ce" />
<img width="960" alt="http contains password" src="https://github.com/user-attachments/assets/59078e4d-3b0d-4282-a53c-b8493b9ae70a" />
<img width="960" alt="arp" src="https://github.com/user-attachments/assets/6bd42c99-14ef-41d5-9231-b0fe5bf66c5e" />
<img width="960" alt="IP Adress Source" src="https://github.com/user-attachments/assets/12da5722-ddac-4ebc-a816-05ad0f8028cb" />
<img width="960" alt="IP Address Destination" src="https://github.com/user-attachments/assets/aa4f7640-05e2-44a2-b91b-cf6817ac762c" />








   
