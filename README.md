<h1>Final Project for ITF Manual Testing Course</h1>


The scope of the final project is to use all gained knowladge throught the course and apply them in practice using a live application.
<p>Application under test:https://www.aeries.com/solutions/demo/<br>
API Documentation:https://airportgap.dev-tester.com/</p>
<p>The final project will be split into 3 sections:Testing section, API section and SQL section.<br>
Tools used: JIRA, Zephyr Squad, Postman, MySQL Workbench.</p>
<p>Functional specifications:<br>
The below Story was created in JIRA and describes the functional specifications of the teacher role, 
for which the final project is performed upon.</p>


![Story!](https://github.com/MateiAlexandraMarinela/manual_testing_project/blob/main/print%20screen%20to%20use%20in%20github/Story-The%20teacher%20role-functional%20specifications.png)



<h3>1.1 Testing section<br></h3>
The Test Plan is designed to describe all details of testing for the Teacher role from the Aeries aplication.<br>
The plan identifies the items to be tested, the features to be tested, the types of testing to be performed 
and the risks associated with the plan.

<h4>1.1.1 Roles assigned to the project and persons allocated<br></h4>
Due to the fact that this is a project done by myself on an opensource aplication to prove all of the information
I have learned there are no roles assigned.

<h4>1.1.2 Entry criteria defined<br></h4>
-functional specifications are defined<br>
-initial project risks were detected and mitigated

<h4>1.1.3 Exit criteria defined<br></h4>
-number of unresolved bugs is insignificant or they have medium priority<br>
-all tests have been executed<br>
-deadline was reached

<h4>1.1.4 Test scope<br></h4>
 TESTS IN SCOPE:All the feature of the Teacher role which were defined in software 
requirement specs need to be tested: functional testing, GUI testing<br>
 TESTS NOT IN SCOPE: performance testing, compatibility testing with multiple browsers 

<h4>1.1.5 Risks detected<br></h4>
Project risks:lack of experience of the QA team, short deadline for testing<br>
Product risks:the intrest for the product can be low due to the domain for wich it was created,<br>
              validation constraints on the fields might be too restrictive to the end-user

<h4>1.1.6 Evaluating entry criteria<br></h4>
The entry criterias defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control<br></h3>
Various periodic reports were generated to reflect the current status of the testing process.<br> 
The following status report was generated after 5 of the test cases were executed,<br>
and the first bug was found, on the 12th of March 2023.

![mon!](https://github.com/MateiAlexandraMarinela/manual_testing_project/blob/main/print%20screen%20to%20use%20in%20github/monitoring%20and%20control3.png)




<h3>1.3 Test Analysis<br></h3>
The testing process will be executed based on the above requirements<br>
for the Teacher role.<br>The following test conditions were found:<br>
-view student profile<br>
-view attendance detail<br>
-view contacts<br>
-take attendance<br>
-mass apply attendance codes<br>
-submit/modify attendance notes

<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad.<br> Based on the analysis of the specifications, 
the test design techniques used for generating test cases are use case testing, UI testing and positive and negative testing.<br>
Test cases:

![Test C!](https://github.com/MateiAlexandraMarinela/manual_testing_project/blob/main/new%20commit/Screenshot%202023-03-27%20124325.png)






The test cases with steps can be viewed here:<a href="https://github.com/MateiAlexandraMarinela/manual_testing_project/blob/main/print%20screen%20to%20use%20in%20github/test%20cases%20with%20steps-test%20design.xlsx">Test cases with steps</a>






<h3>1.5 Test Implementation<br></h3>
The following elements are needed to be ready before the test execution phase begins:


Testing environment is up and running:https://demo.aeries.net/<br>
Access to the testing environment is given:<br> Username : teacher<br> Password : teacher<br>
Cycle summary was created<br>
Test cases were added to the cycle summary

<h3>1.6 Test Execution</h3>

Test cases are executed on the created test Cycle summary:
![Cycle summary!](https://github.com/MateiAlexandraMarinela/manual_testing_project/blob/main/print%20screen%20to%20use%20in%20github/Cycle%20Summary-test%20execution.png)



Bugs have been created based on the failed tests.<br>
Bug example: ![Bug1!](
https://github.com/MateiAlexandraMarinela/manual_testing_project/blob/main/print%20screen%20to%20use%20in%20github/bug%20report%20example/raport%20bug1.png)
 ![Bug2!](https://github.com/MateiAlexandraMarinela/manual_testing_project/blob/main/print%20screen%20to%20use%20in%20github/bug%20report%20example/raport%20bug%202.png)





Regression testing is needed after the bugs are fixed.


<h3>1.7 Test Completion<br></h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section,<br> 
this feature is suggested to ‘Go Live’ by the Testing team<br>
The traceability matrix was generated and can be found here: <a href="https://github.com/MateiAlexandraMarinela/manual_testing_project/blob/main/print%20screen%20to%20use%20in%20github/taceability%20matrix/Traceability%20Matrix.xlsx">Traceability matrix</a><br>
Test execution chart was generated, the final report shows that <br>a number 2 tests have failed of a total of 13<br>
A number of 13 test cases were planned for execution and all of them were executed<br>
A number of 2 total bugs were found, for which the priority is medium.

Test execution chart:

![Chart!](https://github.com/MateiAlexandraMarinela/manual_testing_project/blob/main/print%20screen%20to%20use%20in%20github/raport%20executie.png)


<h3>2.API testing</h3>

The API testing was executed on a different aplication:https://airportgap.dev-tester.com/<br>
The collection used can be found here:<a href="https://github.com/MateiAlexandraMarinela/manual_testing_project/blob/main/Api%20tests%20for%20Airport%20Gap%20FP.postman_collection.json">JSON file with the collection of requests created for the airportgap API</a>


<h3>3.SQL section<br></h3>
Created a database named 'flowershop', and the tables 'customers', 'orders' and 'inventory'
with all the columns needed to save data per specifications.<br>
Performed different queries inside the sql file: <a href="https://github.com/MateiAlexandraMarinela/manual_testing_project/tree/main/MySQL">flowershop.sql</a>



