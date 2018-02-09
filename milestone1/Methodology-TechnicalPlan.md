## Technical Plan

Utilizing the agile methodology, we will develop a baseline for our scale, replicate the lab solution, and then finalize the scale.

### Developing a Baseline Scale
First, we will need to develop a baseline scale before we actually go through the document. By doing this, we will have a stronger idea of what we are looking for while we go through the document. We will adapt the System Usability Scale from a systems view to a technical document view. We will modify the text of the survey questions while maintaining integrity of the scale. 

Usability effectiveness will be measured against Volume C of the practice guides. Due to the technical nature of the document, an ideal effectiveness rating would be 100%. We can hypothesize that if one task is not completed successfully, the implementation of that guide's method can not be adequately completed. For that reason, we can instead calculate effectiveness by measuring number of errors. Mifsud (2015) defines erorrs as "unintended actions, slips, mistakes or omissions that a user makes while attempting a task."

<a href="https://www.codecogs.com/eqnedit.php?latex=Effectiveness&space;=&space;\frac{\text{Number&space;of&space;tasks&space;completed&space;successfully}}{\text{Total&space;number&space;of&space;tasks&space;undertaken}}&space;*&space;100\%" target="_blank"><img src="https://latex.codecogs.com/gif.latex?Effectiveness&space;=&space;\frac{\text{Number&space;of&space;tasks&space;completed&space;successfully}}{\text{Total&space;number&space;of&space;tasks&space;undertaken}}&space;*&space;100\%" title="Effectiveness = \frac{\text{Number of tasks completed successfully}}{\text{Total number of tasks undertaken}} * 100\%" /></a>

Other metrics of interest to apply to the guides are accuracy, readability, understandability, and consistency. Consistency applies to consistent messaging acorss all three volumes of the guide. Areas of inconsistency between volumes will be recorded and reported. Accuracy applies to Volume C. It is important the instructions are correct. To measure the accuracy of the guide as a percentage, the following formula can be used:

<a href="https://www.codecogs.com/eqnedit.php?latex=Accuracy&space;=&space;\frac{\text{Number&space;of&space;tasks&space;containing&space;incorrect&space;information}}{\text{Total&space;number&space;of&space;tasks&space;in&space;guide}}&space;*&space;100\%" target="_blank"><img src="https://latex.codecogs.com/gif.latex?Accuracy&space;=&space;\frac{\text{Number&space;of&space;tasks&space;containing&space;incorrect&space;information}}{\text{Total&space;number&space;of&space;tasks&space;in&space;guide}}&space;*&space;100\%" title="Accuracy = \frac{\text{Number of tasks containing incorrect information}}{\text{Total number of tasks in guide}} * 100\%" /></a>

Many automated tools are available to calculate readability and understandability. Readable.io, Grammarly, and BETSY are examples of automated tools we will employ. To further measure understandability during the replication phase, we will document any areas of the how-to guide that require additional research/knowledge outside of the practice guide. These metrics primarily apply to volumes A and B. 
While replicating the practice guide example, any tasks containing errors will also be recorded. The accuracy of the how-to guide will then be calculated and reported.

### Replicating the Lab Solution
In order to replicate the solution laid out within the lab document, we will first be required to get rack space/hosting for our virtual machines. The University of Nebraska-Omaha's vSTEAL lab environment is a strong contender. Otherwise, we will use a combination of locally hosted and cloud hosting via Azure or AWS. We intend to go through the same combination of lab setups that the NIST document, Volume C, uses and perform all the same tests to ensure we recieve the same results.

### Finalizing the Scale
After we have finished replicating the Volume C example, we will use the baseline scale developed in our first step to grade the NIST document and make an adjustments to the baseline scale. Each member of our group will apply the scale to the guide. After each member grades the document, we will apply Cohen's kappa to measure the interrater reliability of our scale. If we have poor interrater reliability, we will go back and re-evalutate how we measure the metrics of the scale in order to provide a consistent usability scale.
