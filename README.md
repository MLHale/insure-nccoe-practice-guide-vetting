NCCoE Practice Guide Vetting - Project Proposal
===============================================

Executive Project Summary
-------------------------

### Problem Statement
As rising security practitioners, we understand the need for quality guides explaining the how and why for best security practices. The NCCoE publishes the NIST SP 1800 series, which are a series of how-to guides that allow companies to implement various security policies in a step-by-step manner. These guides are designed for use by security professionals but may also be utilized by a general IT practitioner tasked with deploying the security implementation. Therefore, it is critical these guides are accurate and concise. For this project, the deliverable will be a grading scale that can be used to score the accuracy and conciseness of said documents. In particular, we’ll be implementing and focusing on DNS-Based Secure Email NIST SP 1800-6 Practice Guide. But, this grading scale can be used for any of the NIST SP 1800 series.

### Project Goals
<ul>
  <li>Use the how-to guide to implement the security policy.
  <li>Document any errors we find while using the how-to guide.
  <li>Develop a grading scale for use on the entire NIST SP 1800 series based on our use of the DNS-Based Secure Email NIST SP 1800-6 Practice Guide.
  <li>Explain and justify our grading scale criteria
</ul>

### Project Merit
The ability to objectively compare readability, usability, consistency, and accuracy of the different NIST SP 1800 series documents is crucial, because user feedback can be difficult to quantify. Users often possess different technical backgrounds, expertise, and intelligence. This inevitably leads to different opinions on what constitutes a “good” guide. For example, these guides are used by both experienced security technicians and regular IT personnel. Obviously, a security technician would likely be more lenient on their usability scores, as they would likely have the background necessary to comprehend some of the technical jargon that is used in the guides.
Not only is the comparison of the documents important, but grading these documents with greater specificity will allow those tasked with improving the documents to focus their efforts on categories with lower scores. For example, if a certain NIST SP 1800 series document scores poorly in the category of readability, then it wouldn’t make much sense to have a highly technical person try and improve the document. Perhaps, efforts would be better served to have someone who specializes in technical communication work on the document so as not to waste resources.<div>
Finally, poorly scored documents likely will not be used by companies wanting to implement that document’s specific security policy. So, efforts could be focused on improving that document in order to allow the implementation of that security policy to become more widespread. For instance, if the DNS-Based Secure Email NIST SP 1800-6 Practice Guide is scored poorly, then it would make sense to focus on the improvement of that document in order to allow companies to better implement the security policies proposed in the document.

Project Timeline
----------------
<p>
  <img src="./milestone1/GanttChart.png" />
</p>

Risk List
---------

|Risk Name (Value)      |Impact |Likelihood |Description |
|-----------------------|-------|-----------|------------|
|Limited Breadth of Testing (28)| 4 | 7 | For our grading scale we would want to make sure that we get a lot of outside opinion on whether our grading scale is accurate. We will likely not gather a large amount of outside testing. So, most of the opinion on the scale will be done by us. |
|Lack of Time (24)| 6 | 4 | There is a possiblity that we have not given ourselves enough time to complete a grading scale for the NIST guides. If we are low on time, our product will end up being either incomplete or of a worse quality. |
|Limited Understanding (20)| 5 | 4 | The guides that we will be creating a grading scale for will have a lot of technical details that we may not have knowledge of. It could be hard for us to make an accurate scale for the how-to guides if we don't understand the topics behind them. While we may be able to complete all of them, we might not know what we actually did. |
|Failed Replication of Chosen Guide (14)| 7 | 2 | It is very unlikely that this will occur, but if we are unable to actually complete the practice guide chosen to test our grading scale, then we will never know how well our scale will perform. While a how-to guide that we can't complete should scale badly on our scale, we will not be able to tell how well our grading scale will perform on a working how-to guide. |
|Loss of Group Member (10) | 10 | 1 | A group member may have a personal issue appear or have some reason to drop the class or not participate anymore. If this occurs we will be heavily impacted, but the chance of this is low. |

Literature Review
-----------------

The NCCoE produces practice guides (NIST SP 1800 series) in an effort to increase adoption of NIST standards and cybersecurity technologies. Each guide consists of three volumes. Volume A is a high level executive summary. Volume B contains rationale for adopting the method described and functional evaluations. Volume C contains detailed how-to instructions on how to implement the method. Although the guides describe specific technologies, they are designed to be used with other products. There is little to no research into the usability of technical how-to guides. We will look at existing usability scales in user experience design and investigate their usage with the practice guides.

ISO 9241-11 (1998) defines usability as the "Extent to which a product can be used by specified users to achieve specified goals with effectiveness, efficiency and satisfaction in a specified context of use." Effectiveness is defined as "Accuracy and completeness with which users achieve specified goals." According to an article by Justin Mifsud (2015) discussing ISO 9241-11, effectiveness can be calculated by measuring completion rate. Mifsud provided the follolwing formula to calculate effectiveness as a percentage:

<a href="https://www.codecogs.com/eqnedit.php?latex=Effectiveness&space;=&space;\frac{\text{Number&space;of&space;tasks&space;completed&space;successfully}}{\text{Total&space;number&space;of&space;tasks&space;undertaken}}&space;*&space;100\%" target="_blank"><img src="https://latex.codecogs.com/gif.latex?Effectiveness&space;=&space;\frac{\text{Number&space;of&space;tasks&space;completed&space;successfully}}{\text{Total&space;number&space;of&space;tasks&space;undertaken}}&space;*&space;100\%" title="Effectiveness = \frac{\text{Number of tasks completed successfully}}{\text{Total number of tasks undertaken}} * 100\%" /></a>

ISO 9241-11 (1998) defines satisfaction as "Freedom from discomfort, and positive attitudes towards the use of the product." Mifsud (2015) states "User satisfaction is measured through standardized satisfaction questionnaires which can be administered after each task and/or after the usability test session." The article lists several types of questionnaires and the usage of each. The System Usability Scale (SUS) is a proven method for evaluating the usability of systems compared to industry standards (Thomas, 2015). SUS is a 10 question survey utliizing a 5 point likert scale and is administered to a user at the end of the test session. According to Thomas (2015), the average SUS score is 68. 

According to an article posted by the Technical Communication Center (techwriter, 2010), readability "measures how easy to read and understand a document is, assuming the readers are identical in understanding of the subject matter." This artcile suggests three readability formulas to measure a technical documentation.

1. Flesch Reading Ease Index calculates reading ease on a scale of 0 - 100 with 0 being very difficult to read and 100 being very easy to read.

2. Flesch-Kinkaid Readability Index calculates the expected grade level of a reader needed to comfortably understand the text.

3. Gunning-Fog Readability Index calculates the number of years of formal education needed by the reader to underdstand the text.

Interrater reliability measures agreement among data collectors. According to McHugh (2012), interrater reliability is a concern "...due to the fact that multiple people collecting data may experience and interpret the phenomena of interest differently." Reliability of data collection increases overall confidence in the accuracy of a research study (McHugh, 2012). Cohen's kappa, developed by Jacob Cohen in the 1960s, is one measurement of interrater reliability. This measure accounts for random agreement among data collectors. Cohen's kappa calculates a score of 0 to 1 with 0 meaning no agreement and 1 meaning perfect agreement.

Technical Plan
--------------

Utilizing the agile methodology, we will develop a baseline for our scale, replicate the lab solution, and then finalize the scale.

### Developing a Baseline Scale
First, we will need to develop a baseline scale before we actually go through the document. By doing this, we will have a stronger idea of what we are looking for while we go through the document. We will adapt the System Usability Scale from a systems view to a technical document view. We will modify the text of the survey questions while maintaining integrity of the scale. 

Usability effectiveness will be measured against Volume C of the practice guides.

<a href="https://www.codecogs.com/eqnedit.php?latex=Effectiveness&space;=&space;\frac{\text{Number&space;of&space;tasks&space;completed&space;successfully}}{\text{Total&space;number&space;of&space;tasks&space;undertaken}}&space;*&space;100\%" target="_blank"><img src="https://latex.codecogs.com/gif.latex?Effectiveness&space;=&space;\frac{\text{Number&space;of&space;tasks&space;completed&space;successfully}}{\text{Total&space;number&space;of&space;tasks&space;undertaken}}&space;*&space;100\%" title="Effectiveness = \frac{\text{Number of tasks completed successfully}}{\text{Total number of tasks undertaken}} * 100\%" /></a>

Other metrics of interest to apply to the guides are accuracy, readability, understandability, and consistency. Consistency applies to consistent messaging acorss all three volumes of the guide. Areas of inconsistency between volumes will be recorded and reported. Accuracy applies to Volume C. It is important the instructions are correct. To measure the accuracy of the guide as a percentage, the following formula can be used:

<a href="https://www.codecogs.com/eqnedit.php?latex=Accuracy&space;=&space;\frac{\text{Number&space;of&space;tasks&space;containing&space;incorrect&space;information}}{\text{Total&space;number&space;of&space;tasks&space;in&space;guide}}&space;*&space;100\%" target="_blank"><img src="https://latex.codecogs.com/gif.latex?Accuracy&space;=&space;\frac{\text{Number&space;of&space;tasks&space;containing&space;incorrect&space;information}}{\text{Total&space;number&space;of&space;tasks&space;in&space;guide}}&space;*&space;100\%" title="Accuracy = \frac{\text{Number of tasks containing incorrect information}}{\text{Total number of tasks in guide}} * 100\%" /></a>

Many automated tools are available to calculate readability and understandability. Readable.io, Grammarly, and BETSY are examples of automated tools we will employ. To further measure understandability during the replication phase, we will document any areas of the how-to guide that require additional research/knowledge outside of the practice guide. These metrics primarily apply to volumes A and B. 
While replicating the practice guide example, any tasks containing errors will also be recorded. The accuracy of the how-to guide will then be calculated and reported.

### Replicating the Lab Solution
In order to replicate the solution laid out within the lab document, we will first be required to get rack space/hosting for our virtual machines. The University of Nebraska-Omaha's vSTEAL lab environment is a strong contender. Otherwise, we will use a combination of locally hosted and cloud hosting via Azure or AWS. We intend to go through the same combination of lab setups that the NIST document, Volume C, uses and perform all the same tests to ensure we recieve the same results.

### Finalizing the Scale
After we have finished replicating the Volume C example, we will use the baseline scale developed in our first step to grade the NIST document and make an adjustments to the baseline scale. Each member of our group will apply the scale to the guide. After each member grades the document, we will apply Cohen's kappa to measure the interrater reliability of our scale. If we have poor interrater reliability, we will go back and re-evalutate how we measure the metrics of the scale in order to provide a consistent usability scale.

Resources Needed
----------------

Due to wide coverage of the document, the number of resources used is quite extensive. As such, in order to maximize the list readability it is necessary to split up the tables by portion of the project.

### General
| Resources | Non team member help needed? | Investigating Team member | Description |
|-------------------|---------|---------------------------|-------------|
| GitHub | No | - | Used to facilitate collaborative efforts |
| Google Drive | No | - | Used to facilitate collaborative efforts |
| Slack | Yes | - | Official form of contact between group members |

### Required to Perform Document Analysis
| Resources | Non team member help needed? | Investigating Team member | Description |
|-------------------|---------|---------------------------|-------------|
| ISO 9241-11 | Yes | Dan | ISO standard that defines usability and readability |
| readable.io | Yes | Dan | Used to perform text grading analysis |
| BETSY | Yes | Dan | Windows-based program that classifies text based on trained material |

### Required to Recreate the Lab
| Resources | Non team member help needed? | Investigating Team member | Description |
|-------------------|---------|---------------------------|-------------|
| Rackspace / VM Hosting | Yes | Cody | Lots of options - vSTEAL, Team member provided infrastructure/sandbox, Cloud Hosted (Azure, AWS), or running locally to host the virtual labs. Most likely Hyper-V or VMWare |
| Public IPs | Depends on above | Scott | Public IP is needed for hosting |
| Domain Name(s) | Yes | Scott | Need a domain to purchase with the ability to override the nameservers to ours |
| Secure64 DNS Signer, DNS Cache, DNS Authority, and DNS Manager | Yes | Cody | This was used as the other end of their lab, provided by and configured by Secure64 |
| Windows Server 2016 | No | Cody | Required for the ADDS, ADCS, and Windows-based DNS portion of the lab |
| Microsoft Exchange 2016 | No | Cody | Required for the Windows-based Mail Transfer Agent |
| Postfix with Dovecot | No | Liam | Required for Linux-based Mail Transfer Agent |
| NSD4 Authoritative Name Server | No | Liam | Open-source DNS Server |
| OpenDNSSEC Domain Name Security Manager | No | - | Used to secure DNS zone data before it is published to an authoritative name server |
| Unbound DNS Resolver | No | - | DNS Resolver with DNSSEC Validation |
| BIND Resolver & Domain Name Authority Server | No | Cody | DNS Resolver with DNSSEC Validation and DNSSEC in-line signing |
| Outlook, Thunderbird | No | Liam | Mail clients necessary to perform the lab |

Sources
-------

HOW READABLE IS YOUR WRITING? Accessed: February 8, 2018. Available: https://readable.io/

ISO/IEC, (1998). ISO/IEC 9241-11:1998 Ergonomic requirements for office work with visual display terminals (VDTs) -- Part 11: Guidance on usability. Geneva, Switzerland: ISO/IEC. Retrieved from https://www.iso.org/obp/ui/#iso:std:iso:9241:-11:ed-1:v1:en

McHugh, Mary L. (October 15, 2012). Interrater reliability: the kappa statistic. *Biochemia Medica*. Retrieved from https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3900052/

Misfud, Justin. (June 22, 2015). Usability Metrics – A Guide To Quantify The Usability Of Any System. *Usability Geek*. Retrieved from
https://usabilitygeek.com/usability-metrics-a-guide-to-quantify-system-usability/

Rudner, Lawrence M. Bayesian Essay Test Scoring sYstem - BETSY. Accessed: February 8, 2018. Available: http://echo.edres.org:8080/betsy/

techwriter. (October 7, 2010). 3 Different Readability Indexes for your Technical Document. *Technical Communication Center*. Retrieved from https://www.technicalcommunicationcenter.com/2010/10/07/3-different-readability-indexes-for-your-technical-document/

Thomas, Nathan. (July 13, 2015). How To Use The System Usability Scale (SUS) To Evaluate The Usability Of Your Website. *Usability Geek*. Retrieved from https://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/
