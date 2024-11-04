# EX NO 2 InformationGathering
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
![Screenshot 2024-09-25 152940](https://github.com/user-attachments/assets/03f74665-b36b-4252-b88e-e367e0a5fe1c)


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
![Screenshot 2024-09-25 153419](https://github.com/user-attachments/assets/34e10958-643b-4c15-8035-1227aad51603)


## Whatweb:

whatweb training.saveetha.in

## Output:
![Screenshot 2024-09-25 153557](https://github.com/user-attachments/assets/7e1b945d-e51b-440a-9699-85d31522d912)


## Tracing the Location:
## TCP Traceroute:

sudo traceroute -T www.google.com

## Output:
![Screenshot 2024-09-25 153122](https://github.com/user-attachments/assets/86da6acb-b62a-4867-b320-fcee82875b53)

## UDP Traceroute:

sudo traceroute -U www.google.com

## Output:
![Screenshot 2024-09-25 153655](https://github.com/user-attachments/assets/e62978a5-d7d3-42ba-85c7-fce1933a1b14)

## ICMP Traceroute:

sudo traceroute  www.google.com

## Output:
![Screenshot 2024-09-25 153858](https://github.com/user-attachments/assets/60c6a360-ab5d-4db9-a865-3c4c9c109fb5)






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
