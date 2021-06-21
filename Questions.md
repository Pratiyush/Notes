Cypress
-------
Over the past few days, I have been playing around with cypress, and it has been an enriching experience. I have been doing end-to-end testing for a few years now, but working with cypress has been a different experience altogether.

Cypress is opensource next-gen front-end testing tool specifically developed for modern web apps(React, Vue, Angular). Cypress End To End test makes it incredibly easy for users to debug and write. We have capability of mocking or manupalaing the application traffice or api calls from frontend to backend or vice versa.

Most of the modern testing tools including selenium run outside the browser and uses remote command to interact with it. On the other hand, Cypress operates directly within a web browser. Cypress currently has more than 30K starts, around 2K Fork(1) in Github which is way more than Selenium(2). Cypress lets user wirte or debug quality test easily.

https://github.com/Pratiyush/Notes/blob/master/cypress/quesitons.md

https://chercher.tech/cypress-io/cheat-sheet-cypress-io

> Test Retries - We can configure how many times a test can retry if it fails.

* assertions is the way to validate the expected and actual values.  

* Object identificaiton is one of very important for testing and there are mutliple ways we can do it in cypress.
  *   By ID #id
  *   By classname .classname
  *   By Xpath - using cypress-xpath plugin 
  *   text on page 
  *   Recommanded Way: data-* data-testid, data-test, data-cy

What are best Practices in Cypress?
---------------------------
https://docs.cypress.io/guides/references/best-practices

What ate cypress plugines?
----------------------------

There are lots of communnity and official plugins in cypress and we can use as per our requirement.

Some examples of plugins are below.
 
* Cucumber - Run cucumber/gherkin-syntaxed specs with cypress.io. It is Preprocessors plugin.
Note: The event file:preprocessor is used to customize how your test code is transpiled and sent to the browser. 

* cypress-file-upload - Simple custom command to ease file upload testing
* cypress-xpath  - Adds XPath command. This repo is also a good example of using custom commands to do retries.
  Note: XPath can be used to navigate through elements and attributes in an XML document and HTML Page.

What is Cypress Studio?
----------------------------
It is used to record the test cases and test can be modified as per our need. Its experimental tool stable version is yet to come.

What is Cypress Dashboard?
--------------------------
The Cypress Dashboard is web-based component that provides various features related to projects and test runs in Cypress. It provides the visual representation of the test runs, their reports, and status on a single web window.

Xray
------
Xray is a complete Test Management tool for Jira. It is a full-featured app that does not require any other software in order to run.

Xray supports the entire testing life cycle:  test planning, test design, test execution and test reporting. We do this by using special Jira issue types, so you can use all Jira benefits that you are used to.

Our aim is to help you improve the quality of your systems through effective and efficient testing. That's why from our first version, Xray already supports both manual and automated tests, including full support for BDD framework (e.g. Cucumber) examples/tests in the native language (i.e., English).

What is Gherkin?
------------------
Gherkin is a set of grammar rules that makes plain text structured enough for Cucumber to understand. 

 ```Feature: Account Holder withdraws cash
 
  Scenario: Account has sufficient funds
    Given the account balance is $100
      And the card is valid
      And the machine contains enough money
    When the Account Holder requests $20
    Then the ATM should dispense $20
      And the account balance should be $80
      And the card should be returned
 ```
 
 Modern App Automation Reports
 ------------------------------
 Selenium Uses - ExtendReport and Allure Reports
 Cypress Uses - allure, mochawesome
 
 Allure Reports are more intuative
 -------------------------------------
![image](https://user-images.githubusercontent.com/2181212/122803441-e9097200-d2c6-11eb-8df9-e31ca9308ed1.png)

![image](https://user-images.githubusercontent.com/2181212/122803459-eeff5300-d2c6-11eb-9e7c-e290cc27a324.png)

 Extend Report
 -------------
 ![image](https://user-images.githubusercontent.com/2181212/122803306-bb242d80-d2c6-11eb-8f6d-1f7a6c96a82f.png)

 Mochawesome
 --------------
 ![image](https://user-images.githubusercontent.com/2181212/122803212-992aab00-d2c6-11eb-917a-33ac3184db68.png)
 
 
 
Test Pyramid
----------------



