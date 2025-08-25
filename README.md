# Ex-02 InformationGathering
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

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois

<img width="911" height="738" alt="479586245-5738181c-dce0-458c-8b42-afe9500d3663" src="https://github.com/user-attachments/assets/fe99e781-1069-4d7b-8749-99403be36a55" />


### Finding Hosting Company :

<img width="1617" height="847" alt="479586075-785c5332-534a-4754-85d0-645e2ecb075e" src="https://github.com/user-attachments/assets/01d8e774-bd31-4734-81fb-1cd5874a1ec4" />


### History of the website :


<img width="1919" height="922" alt="479588035-3fd65f7b-6a24-41dc-b8b5-f1aee477132a" src="https://github.com/user-attachments/assets/4eb829af-f17b-4a05-8b4c-7eb091731d13" />

### ping command :

<img width="735" height="694" alt="479587484-354b4935-5a03-4c5f-8637-b7b749d157a4" src="https://github.com/user-attachments/assets/4518d245-d3a8-450e-92ab-4462de3abd44" />


### whois :

<img width="760" height="742" alt="479588652-79694cd4-c12c-4d63-b313-913e1506a733" src="https://github.com/user-attachments/assets/3e7bda48-03ff-491a-a39a-c201b15886b7" />


### netcat :

<img width="665" height="108" alt="479590058-bb93be15-acb6-4473-bc3b-590e015f712c" src="https://github.com/user-attachments/assets/98978bed-5e70-4893-9586-8d07724cd4dd" />


### nmap :

<img width="637" height="261" alt="479590448-37659d82-c9f5-47c1-a5bc-4baff004e2db" src="https://github.com/user-attachments/assets/c9d54235-8a73-4493-8747-f2c786a8ca2a" />


### whatweb :

<img width="745" height="197" alt="479590853-928a6c89-b160-421c-add3-4dd7bd400aa0" src="https://github.com/user-attachments/assets/f9fb124d-8517-43ec-9302-2f0cf22547ed" />


### httprint :

<img width="630" height="208" alt="479598583-25d1d98e-6ccd-4459-957f-c91ac4edd97e" src="https://github.com/user-attachments/assets/5619525c-6adf-489a-88ef-a2c19e1bcdc0" />


### TCP traceroute :

<img width="747" height="394" alt="479599153-c957bd67-1b5e-42ba-baee-1fa5332cbb47" src="https://github.com/user-attachments/assets/f2b8187f-492e-4b69-8d66-0e50baae9f2b" />


### UDP traceroute :

<img width="731" height="527" alt="479599727-7478e1f6-9ed0-4a13-8629-fed1faa85635" src="https://github.com/user-attachments/assets/6498a9e5-6e41-4ecc-a8a6-e6340ce20eda" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
