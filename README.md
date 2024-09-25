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
![Screenshot (101)](https://github.com/user-attachments/assets/0c7a892b-9abf-4593-afac-b962e607acc2)

## Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

ping training.saveetha.in

## Output:
![Screenshot (109)](https://github.com/user-attachments/assets/86aad831-b76c-4f79-af34-cdf3e40143f6)

## Finding Hosting Company:
get further detail by using ip2location.com website.

## Output:
![Screenshot (102)](https://github.com/user-attachments/assets/bd9812a1-c453-4f03-8f6c-80b9f6237db9)

## History of the wbsite:
## Output:
https://web.archive.org/
![image](https://github.com/gokul-sureshkumar/InformationGathering/assets/121148715/f5166239-895a-4e51-924a-1771ccea3ec8)
## Web server Fingerprint:

## nmap:

nmap -p 21 -sV --script=banner ftp.vim.org

## Output:

![Screenshot (107)](https://github.com/user-attachments/assets/95195721-a1ff-4d7f-9567-1e7b7bafa39c)

## Whatweb:

whatweb training.saveetha.in

## Output:
![Screenshot (108)](https://github.com/user-attachments/assets/65de4a52-9d3a-4dcb-b949-e0872d166243)


## Tracing the Location:
## TCP Traceroute:

sudo traceroute -T www.google.com

## Output:
![Screenshot (105)](https://github.com/user-attachments/assets/4b192906-3975-4d56-a130-12e810aaa2c6)

## UDP Traceroute:

sudo traceroute -U www.google.com

## Output:
![Screenshot (110)](https://github.com/user-attachments/assets/f938bbe2-c4e2-4f23-a3d9-042509ab2e95)

## ICMP Traceroute:

sudo traceroute  www.google.com

## Output:

![Screenshot (106)](https://github.com/user-attachments/assets/7ff961f7-a420-4b78-ba6d-22de3e127e48)





## RESULT:
The information gathering techniques tools/procedure were  identified successfully
