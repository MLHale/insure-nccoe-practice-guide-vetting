# Resources Needed

Due to wide coverage of the document, the number of resources used is quite extensive. As such, in order to maximize the list readability it is necessary to split up the tables by portion of the project.

[//]: # (open source automated essay scoring?)

## General
| Resources | Dr. Hale needed? | Investigating Team member | Description |
|-------------------|---------|---------------------------|-------------|
| GitHub | No | - | Used to facilitate collaborative efforts |
| Google Drive | No | - | Used to facilitate collaborative efforts |
| Slack | Yes | - | Official form of contact between group members |

## Required to Perform Document Analysis
| Resources | Dr. Hale needed? | Investigating Team member | Description |
|-------------------|---------|---------------------------|-------------|
| readable.io | Yes | Dan | Used to perform text grading analysis |

## Required to recreate the lab
| Resources | Dr. Hale needed? | Investigating Team member | Description |
|-------------------|---------|---------------------------|-------------|
| Rackspace / VM Hosting | Yes | - | Lots of options - vSTEAL, Cody's HomeLab, Cloud Hosted (Azure, AWS), or running locally to host the virtual labs. Most likely Hyper-V or VMWare |
| Public IPs | Depends on above | - | Public IP is needed for hosting |
| Domain Name(s) | Yes | - | Need a domain to purchase with the ability to override the nameservers to ours |
| Secure64 DNS Signer, DNS Cache, DNS Authority, and DNS Manager | Yes | Cody | This was used as the other end of their lab, provided by and configured by Secure64 |
| Windows Server 2016 | No | Cody | Required for the ADDS, ADCS, and Windows-based DNS portion of the lab |
| Microsoft Exchange 2016 | No | Liam | Required for the Windows-based Mail Transfer Agent |
| Postfix with Dovecot | No | - | Required for Linux-based Mail Transfer Agent |
| NSD4 Authoritative Name Server | No | Liam | Open-source DNS Server |
| OpenDNSSEC Domain Name Security Manager | No | - | Used to secure DNS zone data before it is published to an authoritative name server |
| Unbound DNS Resolver | No | - | DNS Resolver with DNSSEC Validation |
| BIND Resolver & Domain Name Authority Server | No | - | DNS Resolver with DNSSEC Validation and DNSSEC in-line signing |
| Outlook, Thunderbird | No | Liam | Mail clients necessary to perform the lab |
