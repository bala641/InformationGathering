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

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
<img width="1919" height="997" alt="Screenshot 2026-01-30 210148" src="https://github.com/user-attachments/assets/aa3b9d9c-6a88-4dad-97cd-5649b1fa54b6" />


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of cyberdb.co .
##output

<img width="819" height="334" alt="Screenshot 2026-01-30 210414" src="https://github.com/user-attachments/assets/f3e9381c-ecee-4d45-807a-0da7a1753a7a" />


## Finding Hosting Company
get further detail by using ip2location.com website.
##output

<img width="955" height="755" alt="Screenshot 2026-01-30 201516" src="https://github.com/user-attachments/assets/71779476-71e3-45d9-a4d8-acbca89f1a7b" />


## History of the website:
## output
https://cyberdb.co/
<img width="939" height="1041" alt="Screenshot 2026-01-30 211127" src="https://github.com/user-attachments/assets/b955f604-bf53-490a-8ba0-383613960bbe" />


# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
## output:

<img width="897" height="117" alt="Screenshot 2026-01-30 201705" src="https://github.com/user-attachments/assets/3a48abab-2699-42ec-8b56-ecc70e356692" />


## nmap:
###output
<img width="925" height="341" alt="Screenshot 2026-01-30 201959" src="https://github.com/user-attachments/assets/2dc908cb-b307-4c92-b657-567d1ff10520" />


## Whatweb
### output
<img width="1908" height="409" alt="Screenshot 2026-01-30 210826" src="https://github.com/user-attachments/assets/29e9d196-3032-432c-afdf-ba99ee4fa8cf" />


## httprint
### output
<img width="1033" height="969" alt="Screenshot 2026-01-30 210709" src="https://github.com/user-attachments/assets/48fa3d25-dc80-4ed6-9a9f-4aeeaa99c864" />




# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.cyberdb.co 
## output:
<img width="966" height="125" alt="Screenshot 2026-01-30 211034" src="https://github.com/user-attachments/assets/c55ac142-d44d-4e26-ad8d-3f69c8f0883d" />



## UDP Traceroute:
sudo traceroute -U www.cyberdb.co 
## output:

<img width="892" height="517" alt="Screenshot 2026-01-30 205914" src="https://github.com/user-attachments/assets/bb7dad0d-3b26-4cb2-b374-7b072416064d" />


## ICMP Traceroute:
sudo traceroute  www.cyberdb.co 
## output:


<img width="886" height="429" alt="Screenshot 2026-01-30 210008" src="https://github.com/user-attachments/assets/a635fb2b-b0e1-43ad-93df-9af10182c499" />




## RESULT:
The information gathering techniques tools/procedure were  identified successfully
