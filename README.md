# InformationGathering
## Information Gathering Techiques

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


## OUTPUT:
## WHOIS

![Screenshot 2024-04-02 030513](https://github.com/sreekarsh/InformationGathering/assets/139841918/bc6c8d7d-e26c-4609-bf75-b803210b998e)

## IP2LOCATION:

![Screenshot 2024-04-02 031127](https://github.com/sreekarsh/InformationGathering/assets/139841918/8ff15223-5334-455c-bf9d-424fbff0acd8)

## WEB ARCHIVE:
![Screenshot 2024-03-26 031533](https://github.com/sreekarsh/InformationGathering/assets/139841918/d58b4cfc-6e92-4b6d-9997-3b2b30b1e699)

## NMAP

![Screenshot from 2024-04-01 23-23-00](https://github.com/sreekarsh/InformationGathering/assets/139841918/00b49077-22c3-4a19-a78d-a44d6c76e4df)

## WHATWEB

![Screenshot from 2024-04-01 23-50-03](https://github.com/sreekarsh/InformationGathering/assets/139841918/15fb7fa6-f106-4ba7-ade0-02092eeb40fb)


## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
### Output:

![eth2 9](https://github.com/Rajeshanbu/InformationGathering/assets/118924713/b7e7f96c-b475-4868-8c6b-46303b8871b1)

## Tracing the Location
### TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:
![eth2 10](https://github.com/Rajeshanbu/InformationGathering/assets/118924713/449f9bc4-1e0e-440d-8383-f4581e79874e)


## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:
![eth 2 11](https://github.com/Rajeshanbu/InformationGathering/assets/118924713/9af636da-8d1c-41e3-be72-598e57a10e57)


## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![eth2 12](https://github.com/Rajeshanbu/InformationGathering/assets/118924713/98f95c5e-46c9-4e03-a395-1d7901d03f74)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
