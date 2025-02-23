======================================
Sudhir Identity Test Automation Framework
======================================
This project is a template for test automation framework, which provides structured and standard way of creating automated test scripts for GUI.

This is a reusable automation framework that blends together Selenium WebDriver, Cucumber JVM

This framework supports automation on Chrome Web browser.

Tools & libraries
=================
The test automation framework is comprised of following tools and libraries

*Cucumber-JVM:- BDD Framework
*Custom Page Object Pattern and utility functions
*Selenium WebDriver: - Browser automation framework
*JAVA: - Programming language
*TestNg: - TestNg Java testing framework
*Maven: - Build tool
*Aqua: - Integrated Development Environment

Machine Configuration
====================
Configure below software's and setup: -
*Java 18
*Apache Maven 3.9.9

Set environment variables
--------------------------
In User variables
    Add - %JAVA_HOME%\bin

In System variables select Path and click Edit
    Ensure JDK bin location is added here (in my case C:\Program Files\Java\jdk18.0.2.1\bin)
    Ensure Maven location is added here (C:\apache-maven-3.9.9\bin)

IDE Configuration
==================
Aqua 2024.3.2
----------------

*Cucumber for Java
*Gherkin
*Maven Integration
*TestNg
*ChromeDriver - 133.0.6943.127

Import Project into Intellij
----------------------------
File>Import Project>

Browse to IdentityE2E-master and import the project

Getting Started
===========================

Feature Files
-------------------------------------------------------------------
These files contains the acceptance criteria which are written in Gherkin Language and contains various scenarios.
The feature files are tagged with "@tagname" to group common feature files

File Extension:  *.feature
Location: "/SudhirHudlProject/src/test/resources/login.feature"

Page Objects
-------------------------------------------------------------------
PageObjects are used to store the WebElements for a Web Page.

Location: "/SudhirHudlProject/src/test/java/com.hudl.test.stepsFiles/LoginPage.java"

Run the tests
---------------------------------------------
*command line using Maven:-  mvn clean test
