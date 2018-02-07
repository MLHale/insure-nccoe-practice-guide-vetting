The NCCoE produces practice guides (NIST SP 1800 series) in an effort to increase adoption of NIST standards and cybersecurity technologies. Each guide consists of three volumes. Volume A is a high level executive summary. Volume B contains rationale for adopting the method described and functional evaluations. Volume C contains detailed how-to instructions on how to implement the method. Although the guides describe specific technologies, they are designed to be used with other products. There is little to no research into the usability of technical how-to guides. We will look at look at existing usability scales in user experience design and investigate their usage with the practice guides.

ISO 9241-11 defines usability as the "Extent to which a product can be used by specified users to achieve specified goals with effectiveness, efficiency and satisfaction in a specified context of use."(ISO citation) Effectiveness is defined as "Accuracy and completeness with which users achieve specified goals." (ISO citation) According to an article by Justin Mifsud (Usability Geek citation) discussing ISO 9241-11, effectiveness can be calculated by measuring completion rate. Mifsud provided the follolwing formula to calculate effectiveness as a percentage:

<img src="http://usabilitygeek.com/wp-content/uploads/2015/06/usability-metrics-effectiveness.jpg" alt="usability-metrics-effectiveness" width="750" height="75" />

This measurement can be applied to Volume C of the practice guides. Due to the technical nature of the document, an ideal effectiveness rating would be 100%. We can hypothesize that if one task is not completed successfully, the implementation of that guide's method can not be adequately completed. For that reason, we can instead calculate effectiveness by measuring number of errors. Mifsud (citation) defines erorrs as "unintended actions, slips, mistakes or omissions that a user makes while attempting a task."

<a href="http://www.codecogs.com/eqnedit.php?latex=Effectiveness&space;=&space;\frac{\text{Number&space;of&space;tasks&space;which&space;resulted&space;in&space;an&space;error}}{\text{Total&space;number&space;of&space;tasks&space;in&space;guide}}&space;*&space;100\%" target="_blank"><img src="http://latex.codecogs.com/gif.latex?Effectiveness&space;=&space;\frac{\text{Number&space;of&space;tasks&space;which&space;resulted&space;in&space;an&space;error}}{\text{Total&space;number&space;of&space;tasks&space;in&space;guide}}&space;*&space;100\%" title="Effectiveness = \frac{\text{Number of tasks which resulted in an error}}{\text{Total number of tasks in guide}} * 100\%" /></a>

ISO 9241-11 (citation) defines satisfaction as "Freedom from discomfort, and positive attitudes towards the use of the product." Mifsud (citation) states "User satisfaction is measured through standardized satisfaction questionnaires which can be administered after each task and/or after the usability test session." The article lists several types of questionnaires and the usage of each. With adequate time and resources for a usability test session, satisfaction could be measured for the practice guides. Usability test session participants should include a mix of technology experts (for technology realted to the practice guide), varying levels of cybersecurity professionals, and varying levels of IT professionals. 

Other metrics of interest to apply to the guides are accuracy, readability, understandability, and consistency. Consistency applies to consistent messaging acorss all three volumes of the guide. Areas of inconsistency between volumes will be recorded and reported. Accuracy applies to Volume C. It is important the instructions are correct. To measure the accuracy of the guide as a percentage, the following formula can be used:

<a href="https://www.codecogs.com/eqnedit.php?latex=Accuracy&space;=&space;\frac{\text{Number&space;of&space;tasks&space;containing&space;incorrect&space;information}}{\text{Total&space;number&space;of&space;tasks&space;in&space;guide}}&space;*&space;100\%" target="_blank"><img src="https://latex.codecogs.com/gif.latex?Accuracy&space;=&space;\frac{\text{Number&space;of&space;tasks&space;containing&space;incorrect&space;information}}{\text{Total&space;number&space;of&space;tasks&space;in&space;guide}}&space;*&space;100\%" title="Accuracy = \frac{\text{Number of tasks containing incorrect information}}{\text{Total number of tasks in guide}} * 100\%" /></a>

While replicating the practice guide example, any tasks containing errors will be recorded. The accuracy of the how-to guide will then be calculated and reported.

Readability is a measure of how easily something can be read. Understandability is a measure of how easily a subject can understand the material. Many automated tools are available to calculate readability and understandability. These metrics primarily apply to volumes A and B.


## Usability

#### ISO 9241-11 Definition
https://www.iso.org/obp/ui/#iso:std:iso:9241:-11:ed-1:v1:en

#### Usability Metrics:
https://usabilitygeek.com/usability-metrics-a-guide-to-quantify-system-usability/

#### Tips/Tricks for Evaluating Documentation Usability:
https://techwhirl.com/tips-and-tricks-10-heuristics-documentation-usability/

#### Implementing Usability Testing (references many sources that may be worth looking at)
http://stars.library.ucf.edu/cgi/viewcontent.cgi?article=5372&context=etd

#### Usability Test Plan Template
https://www.usability.gov/how-to-and-tools/resources/templates/usability-test-plan-template.html

## Readability/Understandability
#### Readability indicators:
https://www.webpagefx.com/tools/read-able/

#### Automated Readability Tool:
https://readable.io/

#### Test Readability in Microsoft Word
https://support.office.com/en-us/article/Test-your-document-s-readability-85b4969e-e80a-4777-8dd3-f7fc3c8b3fd2

## Accuracy
accuracy = # of errors/# of tasks
