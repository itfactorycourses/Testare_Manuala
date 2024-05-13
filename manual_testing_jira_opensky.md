# Testing Project for Opensky

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

**Application under test:** opensky.com

**Tools used**: Jira, Zephyr Squad.

## 1. Functional specifications:

The stories attached [here](https://github.com/itfactorycourses/Testare_Manuala/blob/main/Jira_Stories.doc) were created in Jira and describe the functional specifications of the "Sign In" module, for which the final project is performed upon.

You can find a example of one of the stories that were created in the picture below:

![image](https://github.com/itfactorycourses/Testare_Manuala/assets/143410937/bb61d16a-9add-400e-bc72-7025f7387228)


## Release

Here you can find the release that was created for this project:

![image](https://github.com/itfactorycourses/Testare_Manuala/assets/143410937/e044f46f-29d3-4302-ae51-bdd891f44c4c)

## 2. Testing process
The test process was performed based on the standard test process as described below.

### 1.1 Test planning
The Test Plan is designed to describe all details of testing for the Login module of the Opensky e-commerce application. 

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the projects risks associated with the plan. 

The test plan that was created for this project can be found [here](https://github.com/itfactorycourses/Testare_Manuala/blob/main/Plan%20de%20Testare%20-%20de%20incarcat%20pe%20git%20(modificat%20conform%20proiectului%20vostru).pdf)

#### 1.1.1. Roles asigned to the project and persons allocated

<table>
<tr><td>Project manager </td><td>Ion Popescu</td> </tr>
<tr><td>Product owner</td><td>Maria Ionescu</td></tr>
<tr><td>Software developer</td><td>Mihai Andrescu</td></tr>
<tr><td>QA Engineer</td><td>Catalin Radu</td></tr>
</table>

#### 1.1.2 Entry criteria defined

- The business requirements must be finalizate
- The roles must have been allocated
- The test plan must be finished and sent to the stakeholders
- The entry criteria and exit criteria must be defined
- The project risks must have been identified and mitigated


#### 1.1.3 Exit criteria defined

- 95% of the test can be executed
- not finding bugs of major severity in a specific period of time
- the existing bugs that were reported must have been fixed and followed by retesting and regression testing
- the deadline has been reached


#### 1.1.4 Test scope

##### Tests in scope:

In order to fulfill the testing objectives we are only going to focus on the Login Module (and Register Module) which has been placed in the scope of testing and has been targeted for improvement over the next two months.

From the point of view of the testing techniques we are going to use mostly blackbox testing with the following test design techniques: 

- equivalence partitioning
- boundary value analysis
- decision table

From a testing type perspective we are going to use  non-functional testing  where we are going to cover only usability testing and compatibility testing.
Also, positive testing and negative testing are to be done, and (according to the needs) retesting and regression testing will be done when defects are going to be fixed or when modifications of any type are going to be brought to the code.

##### Tests not in scope:

We are not going to cover during the testing process any techniques related to whitebox testing. 

Also, performance and security testing will not be performed during this session of testing. 

From the perspective of the modules covered, any other functionality that is located outside of the login or register module are not to be tested.

#### 1.1.5 Risks detected

##### Project risks:
(enumerati aici toate riscurile de proiect pe care le-ati identificat pentru proiectul vostru)

##### Product risks:
(enumerati aici toate riscurile de produs pe care le-ati identificat pentru proiectul vostru)

#### 1.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

### 1.2 Test Monitoring and Control
(inserati aici motivul pentru care a fost facuta etapa de monitorizare si control si respectiv cum s-a facut aceasta etapa. Aici veti insera de asemenea si raportul de status (test status report) din zephyr - test metrics - primul din lista care sa reflecte activitatea si evolutia testarii. Recomand aici sa executati teste aproape in fiecare zi ca sa vada angajatorul implicarea voastra in testare)

### 1.3 Test Analysis
The testing process will be executed based on the application requirements.

You can find below an example of ten test conditions (out of a total of 15) that were created in the scope of this project:

![image](https://github.com/itfactorycourses/Testare_Manuala/assets/143410937/492a20fa-d87a-4f1e-a8af-7074e9a4dd1c)

You can find the full set of test conditions together with all the test cases in the following paragraph.

### 1.4 Test Design
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed [here](https://github.com/itfactorycourses/Testare_Manuala/blob/main/Jira_TestCases.doc)

### 1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

(inserati lista de elemente care sunt evaluate in etapa de implementare)

### 1.6. Test Execution
Test cases are executed on the created test Cycle summary.

Bugs have been created based on the failed tests. The complete bug reports can be found here: 

The following is a summary of the bugs that have been found (inserati o lista cu titlurile bug-urilor identificate impreuna cu prioritatea si severitatea fiecaruia)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

### 1.7 Test Completion As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: (inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)

Test execution chart was generated and can be found below.

(inserati aici raportul de executie generat din jira din sectiunea de dashboards)

The final report shows that a number (inserati numarul de teste) tests have failed of a total of (inserati numarul de teste)

A number of (inserati numarul de bug-uri) total bugs were found, from which the priority is: (inserati numarul de bug-uri) are high and (inserati numarul de bug-uri) are medium.

(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)
