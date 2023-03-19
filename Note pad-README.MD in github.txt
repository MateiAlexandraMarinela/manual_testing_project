Final project for ITF Manual Testing Course

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course 
and apply them in practice, using a live application.
Application under test:https://www.aeries.com/solutions/demo/
API Documentation:https://airportgap.dev-tester.com/
The final project will be split into 3 sections:Testing section, API section and SQL section.
Tools used: JIRA, Zephyr Squad, Postman, MySQL Workbench.
Functional specifications:
The below Story was created in JIRA and describes the functional specifications of the teacher role, 
for which the final project is performed upon.





1.1 Testing section
The Test Plan is designed to describe all details of testing for the Teacher role from the Aeries aplication.
The plan identifies the items to be tested, the features to be tested, the types of testing to be performed 
and the risks associated with the plan.

1.1.1 Roles assigned to the project and persons allocated
Due to the fact that this is a project done by myself on an open source aplication to prove all of the information
i have learned there are no roles assigned.

1.1.2 Entry criteria defined
-functional specifications are defined
-initial project risks were detected and mitigated

1.1.3 Exit criteria defined
-number of unresolved bugs is insignificant or they have medium priority
-all tests have been executed
-deadline was reached

1.1.4 Test scope
 TESTS IN SCOPE:All the feature of the Teacher role which were defined in software 
requirement specs need to be tested: functional testing, GUI testing 
 TESTS NOT IN SCOPE: performance testing, compatibility testing with multiple browsers 

1.1.5 Risks detected
Project risks:lack of experience of the QA team, short deadline for testing
Product risks:the intrest for the product can be low due to the domain for wich it was created,
              validation constraints on the fields might be too restrictive to the end-user

1.1.6 Evaluating entry criteria
The entry criterias defined in the Test Planning phase have been achieved and the test process can continue.

1.2 Test Monitoring and Control
Various periodic reports were generated to reflect the current status of the testing process. 
The following status report was generated after 5 of the test cases were executed,
and the first bug was found, on the 12th of March 2023.





1.3 Test Analysis
The testing process will be executed based on the above requirements 
for the Teacher role. The following test conditions were found:
-view student profile
-view attendance detail
-view contacts
-take attendance
-mass apply attendance codes
-submit/modify attendance notes

1.4 Test Design

Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, 
the test design techniques used for generating test cases are use case testing and positive and negative testing.
Test cases:






The test cases with steps can be viewed here:






1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:


Testing environment is up and running:https://demo.aeries.net/
Access to the testing environment is given: Username : teacher| Password : teacher
Cycle summary was created
Test cases were added to the cycle summary

1.6 Test Execution

Test cases are executed on the created test Cycle summary:



Bugs have been created based on the failed tests.



Regression testing is needed after the bugs are fixed


1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, 
this feature is suggested to ‘Go Live’ by the Testing team
The traceability matrix was generated and can be found here: Traceability matrix
Test execution chart was generated, the final report shows that a number 2 tests have failed of a total of 13
A number of 13 test cases were planned for execution and all of them were executed
A number of 2 total bugs were found, for which the priority is medium.

Test execution chart:


2.API testing

The API testing was executed on a different aplication:https://airportgap.dev-tester.com/
The collection used can be found here:


3.SQL section
Created a database named 'flowershop', and the tables 'customers', 'orders' and 'inventory'
with all the columns needed to save data per specifications.
Performed different queries inside the sql file:.



