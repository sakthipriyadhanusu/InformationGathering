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

## DETAILED INFO:
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
![image](https://github.com/sakthipriyadhanusu/InformationGathering/assets/119393194/1a69f4d3-1a39-4d0a-93d0-60a1dcdd79c0)
## Finding IP address:
ping facebook.com.

## OUTPUT:
![image](https://github.com/sakthipriyadhanusu/InformationGathering/assets/119393194/aa869135-d49f-4682-9287-28b9d968f278)

## Finding Hosting Company
ip2location.com website.

## OUTPUT:
![image](https://github.com/sakthipriyadhanusu/InformationGathering/assets/119393194/f8fad054-384b-4d13-99c3-a13ecbe4fe04)

## HISTORY OF WEBSITE:
## OUTPUT:
![image](https://github.com/sakthipriyadhanusu/InformationGathering/assets/119393194/4dce0baf-662e-4dc6-a541-8b50b9a31f77)

## Webserver Fingerprinting:
Netcat: sudo nc example.com 80 GET / HTTP/1.1 Host: example.com

## OUTPUT:
![image](https://github.com/sakthipriyadhanusu/InformationGathering/assets/119393194/ea0d4066-785e-498d-83e8-87cddad0a01e)

## nmap
## OUTPUT:
![image](https://github.com/sakthipriyadhanusu/InformationGathering/assets/119393194/042505ff-608f-4bb0-b7e3-0f565935eb0f)

## whatweb
## OUTPUT:
![image](https://github.com/sakthipriyadhanusu/InformationGathering/assets/119393194/ca8a09e0-77ce-47a9-8b38-8273e36fdefe)

## OUTPUT:
![image](https://github.com/sakthipriyadhanusu/InformationGathering/assets/119393194/9813de26-6e13-4b8e-9a67-5c5e9455d25a)

## Tracing the location
TCP Traceroute- sudo traceroute -T www.google.com
## OUTPUT:
![image](https://github.com/sakthipriyadhanusu/InformationGathering/assets/119393194/9ed5b693-90e9-40be-ab90-7aa443e83ba4)
UDP Traceroute: sudo traceroute -U www.google.com

## OUTPUT:
![image](https://github.com/sakthipriyadhanusu/InformationGathering/assets/119393194/45e62045-712e-4f9a-9d88-360163025bf8)

ICMP Traceroute: sudo traceroute www.google.com
## OUTPUT:
![image](https://github.com/sakthipriyadhanusu/InformationGathering/assets/119393194/8f0d0e01-13eb-4caf-8231-48b6454e9beb)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
