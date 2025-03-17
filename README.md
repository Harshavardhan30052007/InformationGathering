# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering
## NAME: HARSHAVARDHAN.K.B
## REG NO: 212224240054
## OUTPUT:
![WhatsApp Image 2025-03-17 at 14 29 03_531c98af](https://github.com/user-attachments/assets/2ba98462-6165-4d86-b926-63ba8a14f286)
Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
ping saveetha.ac.in
## OUTPUT:
![WhatsApp Image 2025-03-17 at 14 29 04_32d61329](https://github.com/user-attachments/assets/e8a6c469-fa5a-4fe9-8e56-343dd5a13a5f)
Finding Hosting Company:
get further detail by using ip2location.com website.
## OUTPUT:
![WhatsApp Image 2025-03-17 at 14 29 06_8bcd4564](https://github.com/user-attachments/assets/d997001b-c3b0-4733-9d39-020466177946)
History of the website:
## Output:
![WhatsApp Image 2025-03-17 at 14 29 08_d6c40e87](https://github.com/user-attachments/assets/68340ebc-66fb-44a7-b431-798c08cc84fa)
Webserver Fingerprinting:
Netcat: nc 172.17.52.118 80
## OUTPUT:
![WhatsApp Image 2025-03-17 at 14 29 09_6f4ee229](https://github.com/user-attachments/assets/07dff701-b6ec-4730-8f29-e6db06cd1aac)
nmap:
nmap -p 21 -sV --script=banner ftp.vim.org
## OUTPUT:
![WhatsApp Image 2025-03-17 at 14 29 10_c38c652c](https://github.com/user-attachments/assets/332e875e-9a3d-4ac7-a0f2-252c399379ab)
Whatweb:
whatweb infosys.com
whatweb zoho.com
whatweb -v -a 3 172.17.52.201
## OUTPUT:
![WhatsApp Image 2025-03-17 at 14 29 11_602fe4fe](https://github.com/user-attachments/assets/32d2bfd0-46fa-43e3-9df0-ad7e59f37ae2)
httprint:
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
## OUTPUT:
![WhatsApp Image 2025-03-17 at 14 29 12_e1befd74](https://github.com/user-attachments/assets/7ce1cfb3-7ec2-4a6b-b0cf-41fc502b11a6)
racing the Location
TCP Traceroute:
sudo traceroute -T www.saveetha.ac.in
## OUTPUT:
![WhatsApp Image 2025-03-17 at 14 29 12_fbd21c99](https://github.com/user-attachments/assets/691af299-5fcb-4b21-8d7d-4cf838aa62a5)
UDP Traceroute:
sudo traceroute -U www.saveetha.ac.in
## OUTPUT:
![WhatsApp Image 2025-03-17 at 14 29 13_dbccdcae](https://github.com/user-attachments/assets/f41fe2d6-f76c-4ca3-9bb8-5073f7808ee5)
ICMP Traceroute:
sudo traceroute www.saveetha.ac.in
## OUTPUT:
![WhatsApp Image 2025-03-17 at 14 29 13_37bf0a60](https://github.com/user-attachments/assets/cb8b4157-5e9e-40eb-a553-85d2bff25fad)
## RESULT:
The information gathering techniques tools/procedure were  identified successfully
