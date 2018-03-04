# Modify System Usability Scale From a Systems View to a Technical Document View.

## Overview of Systems Usability Scale

The System Usability Scale is a ten question 5-point likert scale survey. Each question is answered on a scale of 1 - 5 with one being "Strongly Disagree" and five being "Strongly Agree". The ten questions from the System Usability Scale (SUS) can be viewed as two "groups" of five questions each. All of the odd-numbered questions are a regular likert item. All of the even-numbered questions are a reverse-likert item. By being a reverse-likert item, the question is designed to be answered negatively. For example, the SUS has the question "I found the system unnecessarily complex." For the system to have high usability, the survey administrator would want the survey taker to answer "Strongly Disagree" to the item.

After all ten questions have been answered, the SUS score is calculated as follows:
<ul>
  <li> Each odd numbered question: questionScore = questionAnswer - 1 </li>
  <li> Each even numbered question: questionScore = 5 - questionAnswer </li>
  <li> Add up total of all questionScore </li>
  <li> Multiply total by 2.5 </li>
  <li> Result equals the SUS score </li>
</ul>

According to Thomas (2015), the SUS scores can be evaluated as follows:
<ul>
  <li> 80.3 and above = A. Users love the site and would reccomend it to others </li>
  <li> 68 = C. There's room for improvement </li>
  <li> 51 and below = F. Usability needs to be made a priority and fixed quickly </li>
</ul>

## Comparison of SUS and PGUS

The text of the original SUS questions have been modified to apply to the NIST Practice Guides while maintaining the integrity of the SUS questions. This new scale is the Practice Guide Usability Scale (PGUS).

| Question Number | System Usability Scale Question | Practice Guide Usability Scale Question |
| ---- | --------------------------------| --------------------------------------- |
| 1 | I think that I would like to use this system frequently. | I think that I would be able to implement other practice guides. |
| 2 | I found the system unnecessarily complex. | I found the practice guide unnecessarily complex. |
| 3 | I thought the system was easy to use. | I thought the practice guide was easy to use. |
| 4 | I think that I would need the support of a technical person to be able to use this system. | I think that I would need the support of a technical person to be able to implement the practice guide. |
| 5 | I found the various functions in this system were well integrated. | I found the various tasks in this practice guide were adequately explained. |
| 6 | I thought there was too much inconsistency in this system. | I thought there was too much inconsistency in the practice guide. |
| 7 | I would imagine that most people would learn to use this system very quickly. | I would imagine that most people would be able to easily implement this practice guide. |
| 8 | I found the system very cumbersome to use. | I found the practice guide very difficult to follow. |
| 9 | I felt very confident using the system. | I felt very confident implementing the practice guide. |
| 10 | I needed to learn a lot of things before I could get going with this system. | I needed to learn a lot of things before I could begin implementing this practice guide. |

## Practice Guide Usability Scale Survey

This is just a visual draft of the survey. For our research, the survey will be built and administered through Qualtrics.

<img src="./PGUS.PNG" />  

## Caculating PGUS Score

Qualtrics also provides the ability to download raw data results. These raw results will be used to calculate the PGUS score. The same methodology for calculating the SUS score will be implemented to calculate the PGUS score.

More details to come...

<!-- need to investigate methods for calculating PGUS score from raw data
excel, develop script, online calculator available?? -->