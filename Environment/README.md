# Environment

<img src="./NetworkDiagram.png" />

## Hosting
Naturally, it would have prefered that all of the hosting be done locally. However, due to networking constraints, it became necessary to obtain public IP addresses which were not available to the local environment.

### vSTEAL
vSTEAL, the vCenter cluster owned by UNO, was able to meet the majority of our needs. We are hosting 7 VMs.

### Cloud Providers
After a cost analysis, AWS and Azure became far more expensive for the simple requirements we had. A smaller provider, Linode, provided the necessary resources for the price point we were looking for. For $5 a month, we were able to get a low end Ubuntu 16.04 Server box with a mere 1 vCPU and 1 GB of RAM, along with 20 GB of storage. Additionally, the price for bandwidth, which by default included a full terabyte of bandwidth per month, was plety for our needs. However, the most important aspect was it provided a static, public IP address at no additional cost.

### Domain Registrar
The domain, capstone-unomaha.com, was purchased via GoDaddy. The public DNS for the domain will be pointed towards the public IP of the Linode server.

## Setup
### Linode Server
#### Description
This server serves as the external access point to all the internal VMs. To do so, OpenVPN server was set up on here, and client certificates was created for all of the VMs hosted in vSTEAL. This creates a private link between all the VMs, and utilizing iptables, port forwarding can be done to internal VMs to expose it on the internet.

#### General Info
* Hostname: -
* OS: Ubuntu 16.04 Server
* CPUs: 1 vCPUs
* RAM: 1 GB
* Disk Size: 20 GB

#### Installed Software
* OpenVPN
* Persistent-iptables

### ADDS/ADCA/DNS Server
#### Description
This servers as a certificate authority and DNS server for the Windows portion of our environment. It can be set up with and without ADDS to test Exchange in an AD evironment and non-AD environment.

#### General Info
* Hostname: xyzzy-exchange
* OS: Windows Server 2016
* CPUs: 2 vCPUs
* RAM: 4096 MB
* Disk Size: 80 GB

#### Installed Software
* Exchange
* OpenVPN Client

### Bind DNS Server
#### Description
This servers as one of the Linux public DNS servers. It can natively provide DNSSec functionality.

#### General Info
* Hostname: xyzzy-bind
* OS: Ubuntu 16.04 Server
* CPUs: 2 vCPUs
* RAM: 4096 MB
* Disk Size: 20 GB

#### Installed Software
* Git
* Bind (compiled from source)
* OpenVPN Client

### NSD4/Unbound/DNSSec Server
#### Description
This serves as one the Linux public DNS Servers.

#### General Info
* Hostname: xyzzy-nsd
* OS: Ubuntu 16.04 Server
* CPUs: 2 vCPUs
* RAM: 4096 Kb
* Disk Size: 20 GB

#### Installed Software
* NSD4
* Unbound
* OpenDNSSec
* OpenVPN Client

### Exchange Server
#### Description
This serves as the Windows mail transfer agent.

#### General Info
* Hostname: xyzzy-exchange
* OS: Windows Server 2016
* CPUs: 4 vCPUs
* RAM: 8192 MB
* Disk Size: 80 GB

#### Installed Software
* Exchange
* OpenVPN Client

### Postfix/Dovecot Server
#### Description
This serves as the Linux mail transfer agent

#### General Info
* Hostname: xyzzy-postfix
* OS: Ubuntu 16.04 Server
* CPUs: 2 vCPUs
* RAM: 4096 MB
* Disk Size: 50 GB

#### Installed Software
* Postfix
* Dovecot
* OpenVPN Client

### Outlook/Thunderbird Client
#### Description
This VM is for testing the DNS and mail settings by sending & receiving mail using various clients

#### General Info
* Hostname: xyzzy-win10
* OS: Windows 10 Enterprise
* CPUs: 2 vCPUs
* RAM: 4096 MB
* Disk Size: 60 GB

#### Installed Software
* Thunderbird
* Outlook 2016
* OpenVPN