# AutomationAllureReport
Steps to Execute
Step 1: Install Cucumber Eclipse Plugin:

Goto Eclipse -> Help -> Eclipse Marketplace -> Search for 'Cucumber Eclipse Plugin' -> Click Install
Step 2: Download the project from the GIT Repo

Step 3: Import the Maven project into Eclipse

Menu -> File -> Open Projects from File System -> Choose the import Source and Click Finish
Step 4: Expand the Project on Package Explorer

Step 5: Expand src/test/java -> runner file -> open the TestRunner.java

Step 6: To run the testcases, Right Click on TestRunner.java file -> Run As -> JUnit Test

Step 7: To Produce Allure Report, run maven clean first and maven verify

Step 8: Reports will be generated in target/custom-allure-report -> index.html

Step 9: the report folder can be changed in pom.xml
