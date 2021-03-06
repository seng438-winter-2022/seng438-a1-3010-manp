>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group \#: 23    |   |
|-----------------|---|
| Student Names:  |   |
| Muhammad Shakeel|   |
| Manpreet Singh  |   |
| Girimer Singh   |   |
| Tianfan Zhou    |   |

**Table of Contents**

[1 Introduction	](#_Toc439194677)

[2 High-level description of the exploratory testing plan	](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing	](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports	](#_Toc439194680)

[5 Any lessons learned from your teamwork on this lab ](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons
learned	](#_Toc439194682)

[7 Comments/feedback on the lab and lab document itself	](#_Toc439194683)

[8 References ](#_Toc439194684)


# Introduction

The purpose of this lab was to do exploratory testing and manual functional testing on an ATM system composed of two versions 1.0 and 1.1 respectively. Our understanding   about exploratory and manual functional testing was that both the testings have some limitations. Although these testing tools are helpful resources in finding bugs/defects but they are more time consuming and it is prone to human errors. [1] Exploratory testing requires a good understanding of the application and there is no logical plan that needs to be followed. On the other hand, manual scripted testing has an advantage of following a plan before actually running the tests. This clearly shows us that the test cases can be used again when appropriate while meeting all the required application/software requirements. And after the testing for version 1.0, we will perform our regression testing on version 1.1, which is an updated version of the program. We need to perform regression testing on the new version to see if perious bugs existing in version 1.0 have been solved, and also if there are any new bugs that come with modification of the code.

# High-level description of the exploratory testing plan

Our strategy to test the ATM machine was to perform invalid inputs for the following functions: withdrawal, deposit, transfer and balance inquiry and this would ensure they are working as designed. We worked in pairs of two to perform the testing. In each pair, one of the group members performed the testing on the ATM system and another group member recorded the bugs/defects on the backlog. Our observations on bugs/defects  were verified as a group. The following lists shows how the functions were split among us:

	Pair 1 : Withdrawal and Deposit, Transfer and Log							
	Pair 2 : Balance inquiry, Card and pin verification
	 												
After two groups finish their own job, we will combine all the bugs we found. And we will double check the bugs we found together to ensure the correctness. After that, we will also perform some random testing with the program to see if there are any unpredicted bugs existing.


# Comparison of exploratory and manual functional testing

The exploratory testing can be useful to get a good understanding of how the application performs based on the customer requirements. The manual functional testing can be useful to perform the same test if needed to ensure the requirements are still met. 

Also, it is possible that sometimes exploratory testing can find some issues which can not be found in manual testing. Since manual functional testing is based on the high level requirement of the system, it covers all the basic operations that a system should have. However, for exploratory testing it randomly tests functionalities of the system. There are some bugs which only exist in certain rare conditions of the system. Manual testing will normally not cover rare conditions but if we use exploratory testing there is a chance to find those bugs. For example, for bug 1-5 included in our defect report, which is “When a user presses any button except 1, 2 and 3 on the Num-pad, The machine dispenses $20 from any random account”. For that bug is not included within the manual functional testing table, but was found during the exploratory testing process.

In terms of efficiency, Exploratory Testing is more time saving and there is no lead-in time required for the test execution. Whereas, In the Manual Scripted Testing, It needs a lot of lead-in time for the test execution.[2] Moreover, In exploratory testing, there is no investment in preparing scripts and creating documentation which is usually required in the manual testing for the test execution.

Exploratory Testing is more effective than Manual functional testing as It establishes the faster feedback and helps to do quick and necessary changes in the development.

# Notes and discussion of the peer reviews of defect reports

Both the manual and exploratory testing was done in pairs. One member had the responsibility of finding the bugs while the other person recorded the findings in the backlog. We shared our findings with each other and we verified our findings by running the application again and producing that bug. This strategy ensured that we were able to find all possible bugs in the application. We used the backlog tool to organize our findings and make appropriate edits as needed to ensure all possible bugs are noted and discussed among the team. The backlog tool was effectively used as it showed the issues that have been resolved and issues that are yet to be resolved in the version 1.1. There was some ambiguity on the status assigned to each bug in the backlog as status meanings are open to individual interpretation. Team worked together to come to consensus on the best suitable statuses for better clarity.


# Any lessons learned from your teamwork on this lab
 
We learned that we are able to get more work done in less time when working with team members. We were able to share our knowledge with each other to get the work done more efficiently and effectively. Moreover, we were able to get the lab done in a timely fashion as we started early and spent some time each order until completion. This lab showed us the importance of teamwork since everyone was able to benefit from the important ideas and concepts that were shared among the team members.Teamwork is one of the most important skills that is needed in the industry and this lab gave us a good practice of that. We were able to use the tools required such as backlog in order to report our findings. Once each member found an issue or bug, it was reported to the backlog. The findings were later verified between each pair and with all team members. Backlog was a useful tool as everyone was able to see the bugs being reported and make appropriate changes if necessary. Backlog allowed real time updates that would be viewed by everyone. All the written reports were made on the google docs so that our team could effectively communicate and make changes accordingly. This helped us a lot as a group in writing our reports accurately.

# Difficulties encountered, challenges overcome, and lessons learned

There were some challenges and difficulties that we faced as a group. Most of the obstacles and challenges we faced were related to the setup needed to complete the testing. Since it was our first time using the backlog to report and record the bugs/defects, we had to get familiar with how the backlog works and operate to ensure that it can benefit us to report bugs in an efficient manner. After working on the backlog for some time, We managed to learn this new software and it helped us a lot in completing bug reports for this lab.

One of the other difficulties that we met is to report the bugs we found in a detailed and clear manner. Since at the beginning, we did not strictly follow the five steps to report a bug which includes in the lab instruction, and then when we were trying to verify those reported bugs at a later time, we found it was really hard to trace these reports. From this we learnt the importance of generating a detailed bug report. A bug report must contain information of the initial state of the system, steps to produce the bug we report, and both expected outcome and actual outcome. Such that it can not only provide a clear guide to the report users, but also gives reminders to ourselves.

Another lesson we learnt from this lab assignment is that, as a tester we must have a comprehensive and correct understanding of user requirements of the program. Every expected output should be strictly based on user requirement rather than something from our own perspective or guess. For example, when we are doing the testing for input 3 times incorrect passwords after inserting a card, initially we guess the expected output should be the card is retained and we do not have another chance to input a password again. That guess is based on our experience in real life. And when we were doing a test on version 1.0, the actual output actually matches with our expectation. However, that is incorrect and should be a bug. Since it doesn’t match with the actual requirement. According to the manual test case #40 which is given within lab instruction, users should still be allowed a chance to input the passwords after 3 unsuccessful attempts. Such that we need to report that as an error. 


# Comments/feedback on the lab and lab document itself

This lab gave us a good practical understanding of how exploratory and manual testing are done. Moreover, this lab gave us a very good understanding of how testing of a software or application is done in the real world.The lab document was very detailed and somewhat easy to follow the instructions outlined in the lab manual. From this lab, we learnt the importance of using exploratory testing, manual testing and regression testing. They are all useful testing methods used in the software testing process. Manual testing goes through all the fundamental functional requirements within the prepared table, and it checks if there are any bugs existing with functional operations. Exploratory testing is randomly testing the system. It can find some bugs emerging with some rigid conditions which normally can not be detected with manual testing. Regression testing is needed after the program writer has done some modification with the initial version of the program. After modification, testers need to check that the bugs found in the initial version have been solved, and also if there are new bugs generated in the new version. Within the software testing process, we need to repeat  these three testing processes to ensure a final bug free program. Although from this lab assignment, we have learnt the importance of team working. 

However in the future it would be a good idea to have lab documents to be short and concise. This can definitely help students save some time finding the useful information to implement the lab while fulfilling the requirements. The backlog system was very user friendly and easy to use for recording bugs when working in a team.  

# References
[1] Manual Testing Vs Automation Testing in Software Testing
Rajkumar
https://www.softwaretestingmaterial.com/manual-testing-vs-automation-testing/
 
[2] A quick guide to Exploratory Testing Vs Scripted Testing
https://reqtest.com/testing-blog/exploratory-testing-vs-scripted-testing/

