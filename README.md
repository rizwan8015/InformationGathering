# InformationGathering
Information Gathering Techiques
# Namme : Rizwan B 
# Register NO : 212224100051

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

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:

<img width="1920" height="1080" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/68fb7082-0ccb-4ebe-a36d-538920ebf58a" />

## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output

<img width="776" height="408" alt="image" src="https://github.com/user-attachments/assets/02a95b88-aa6a-4df4-917d-0513125eff32" />

## Finding Hosting Company
get further detail by using ip2location.com website.
##output

<img width="1917" height="1028" alt="image" src="https://github.com/user-attachments/assets/b5f15868-8844-456a-afeb-44ec9018edcb" />

## History of the website:
## output
https://web.archive.org/

<img width="1918" height="1025" alt="image" src="https://github.com/user-attachments/assets/2f23fb14-1a38-4ff3-b4d4-b19217a78c06" />

# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: twitter.com

<img width="791" height="165" alt="image" src="https://github.com/user-attachments/assets/bf49cc1b-e159-4a39-bb76-9e4c74331f42" />

## nmap:
# output

<img width="616" height="172" alt="image" src="https://github.com/user-attachments/assets/5fe66590-7b22-4201-a93c-27bc2a5b244d" />

## Whatweb
### output

<img width="765" height="102" alt="Screenshot 2026-01-31 142524" src="https://github.com/user-attachments/assets/f3bffbdf-537e-4f43-9f44-004a0ab4c4a6" />

## httprint
### output

<img width="456" height="119" alt="Screenshot 2026-01-31 142744" src="https://github.com/user-attachments/assets/24f629f0-e17a-4845-9514-d7d613bfb177" />

# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.twitter.com
## output

<img width="630" height="73" alt="Screenshot 2026-01-31 142827" src="https://github.com/user-attachments/assets/2edce6cd-8acf-4be1-9359-9e40bebfb50b" />

## UDP Traceroute:
sudo traceroute -U www.twitter.com
## output

<img width="590" height="91" alt="image" src="https://github.com/user-attachments/assets/92afebd8-1428-4556-a374-25012cc081d1" />


## ICMP Traceroute:
sudo traceroute  www.twitter.com
## output

<img width="583" height="92" alt="image" src="https://github.com/user-attachments/assets/65f9278b-800f-4de3-9ad4-620ded372733" />

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
