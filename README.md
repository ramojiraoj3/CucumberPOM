# CucumberPOM
This is flight booking project using selenium POM and Cucumber Framework

Project Name		: Flight booking in SpiceJet (CucumberPOM)

2. Introduction 		            :  The project is about to  select the most optimal flight (fastest and cheapest) 
3. Tools used   		            :  Maven, Eclipse, Selenium, Page Object Model, Cucumber, Log4j
4. Steps to import the project	:  Open the given clone URL and click on "DBSCucumberPOM.zip" and click on Download button shown in right side. Then open eclipse right 			  	  	                                 click on workspace click on import --> Maven --> Existing Maven Projects --> Next --> Root Directory --> Browse --> select the download project                                    from your system.
5. How to Run the project	      :  By using TestRunner File/ using POM file/thorough command line.
Each step should have the exact commands to run it. eg: 

1. It can be executed from     "com.qa.runner" package open "TestRunner.java"
    Right click on the file and select "Run As" then "Junit Test".
2. Using pom.xml
    The maven surefire plugin will execute the test with the maven command as "mvn clean install".
3. Run through command line.
    Then open Run.bat file and specify the command as "mvn clean install -DbrowserValue=firefox" save and run it.
    The default browser is set as "chrome".
									
5. How and where to view the reports:- In console JUnit its display detailed report default cucumber reports. And removed debugging statements such as System.out.println(), but  used Log4j to logging of events both in log file and console.
