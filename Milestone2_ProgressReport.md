# Progress Report (26 March 2018)
## Overview
To this point, efforts have been made to complete set up of the lab environment for replicating the practice guide. Methodology for calculating the individual metrics was finalized. Calculating the readability metric has begun.

## Outcomes

* Obtained readable.io subscription
* Obtained readability score from readable.io
* Obtained Grammarly error report
* Developed questions for Practice Guide Usability Scale (PGUS)
* Developed questions for Consistency survey
* Obtained a domain name (capstone-unomaha.com)
* Obtained public IP via cloud hosting
* Developed base lab environment

## Hinderances
A hinderance that has occured in creating a readability score is that the current method of using Grammarly and Readable.io are more accurate when using Word documents, and not PDFs. Grammarly has had an extreme problem with finding errors when using the PDF's text as it will sometimes point out errors that aren't errors because of how the text became formatted. A solution to this would be to see if we could get the original documents used to create the PDFs from our contact at MITRE.

During the creation of the lab environment, multiple hinderences have occured. In an attempt to prevent the cost of paying for Public IPs, Cody tried routing some of the traffic via an IPSec VPN into an environment with access to multiple public IPs. However, due to multiple issues like routing and limited vSTEAL access, traffic would not back flow properly. After it became too much of a hassle to get it functioning, it was decided to just pay the $5 to set up our own server in Linode. Additionally, due to limitations in vSTEAL, we were unable to upload our own ISOs into vSTEAL. Because of this, we could not create any VMs using CentOS, the OS used in the guide. However, Ubuntu/Debian were both listed as viable alternative options and seem to work, minus a couple of hiccups when compiling BIND.

Another minor hinderance was waiting on a domain name. Eventually, one was obtained via GoDaddy which allows DNSSec.

## Ongoing Risks
|Risk Name (Value)      |Impact |Likelihood |Changes from Milestone 1 |
|-----------------------|-------|-----------|------------|
|Limited Breadth of Testing (28)| 4 | 7 | This issue hasn't changed from the original as it will still be a problem going forward. With only 4 testers for our scale, the lack of data could end up giving incorrect results about our finished grading scale. |
|Limited Understanding (20)| 5 | 4 | A lack of understand is still a possible risk as we approach reproducing the guide. While we now have more experience with the topic, we still could still not understand entirely what was done and our scale will be inaccurate. |
|Failed Replication of Chosen Guide (14)| 7 | 2 | The replication of the guide still hasn't occured, but a majority of the setup has been completed. The risk for it failing stays the same, but it shouldn't end up being a major problem. |
|Lack of Time (12)| 6 | 2 | We have done a lot of work in creating the grading scale, so a lack of time should be less likely with what we have done.|
|Loss of Group Member (10) | 10 | 1 | Currently no group members have left and it is assumed that it will stay this way for the remaining month |

## Process Models
![high level process](https://www.lucidchart.com/publicSegments/view/d0fc3e21-85ff-4061-9ac5-3595a727c7bd/image.png)
![accuracy and usability scoring](https://www.lucidchart.com/publicSegments/view/2ba47a44-c7ce-48e0-bac1-b39a6b126714/image.png)

## Environment Layout
<img src="./Environment/NetworkDiagram.PNG" />
