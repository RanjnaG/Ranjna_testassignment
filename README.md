# Ranjna_testassignment

Ranjna Gupta- WestPac Automation Test Assignment


Download the folder from Github
Unzip the folder

About Project:
Westpac KiwiSaver Retirement Calculator
using KiwiSaver Retirement Calculator for Employed,Self-Employed and Not employed user scenarios are created using Cucumber Junit BDD framework.

Framework: Junit, BDD Cucumber
Language used: Java


1) Page Object: -Contains Calculator Web Elements and its methods

2) Two Feature Files are created 
- First feature file covers 'user clicks on information icon besides Current age
- Second feature file covers of 3 scenarios mentioned in the requirement i.e (High Risk Profile, Self-Employed, and not Employed)

 3)StepDefinition File-
- Each of the feature is mapped in Step Definitions file(Contains background, hooks, and step definitions for executing tests ##Selenium WebDriver)

4)TestRunner File
- TestRunner file is created to glue Features with Step Defination

- CucumberOptions: Contains the test runner class and function to execute all tests

This project is configured to use Chrome WebDriver's. The default is set to Chrome. The WebDriver's added to this project to run in Mac and windows


Pre-requisites

Java installed in the system
Maven installed in the system
Latest version of Chrome Browser should be installed



keep the folder the structure intact
To execute the test automation scripts: Run the following maven command from command line
mvn clean test

To view the reports in the project, 
/KiwiSaver_Calculator/target/site/cucumber-pretty/index.html

Open index.html with chrome browser 



