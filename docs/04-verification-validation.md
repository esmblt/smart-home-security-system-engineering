Lets get some refresh on what verification and validation is:

Verification and validation in software engineering are processes that ensure a software system meets requirements and performs as intended.


In summary:

Verification checks whether the software is built correctly by evaluating design, code, and documentation against specifications.

Validation ensures the right software is built by confirming it meets user needs and intended use.

How to create test cases
Note: If you are unable to use Testomat due to licensing issues, you may use the template provided in the resources/downloads section to complete the project.

We will use Testomat(opens in a new tab) to create test cases. Lets check how to do it:

First, you need to register into testomat, once registered, go to the Dashboard and create a new project by using the Create button:

Image showing the Testomat web application Dashboard and the create new project button
Create new project

On new project select Classical (to support markdown format) and add a project title, like Smart Home System, click on the Create button.

Image showing the Create new project section, where you can select between classical and BDD format (classical selected) and the project title set as Smart Home System.
Create new project form

After the project is created, the dashboard is shown, where you can start creating your test suites. A test suite is just a group of test cases for better organization.

Image showing the testomat Dashboard with the create new Suite button selected
Testomat Dashboard

Create a new Suite with name: "Verification". After creating expand the suite using the left arrow icon.

Use the Create test or the top right button plus (+) -> Test to create a new test inside the selected suite.

Image showing how to create a new test inside a suite by using the create test button or the top right plus button then clicking on Test
Create new test

If creating the new test with the plus (+) button, a popup will show to select which suite to create the test into. Select Verification and then click on Select button.


A new window to create a new test will show:

Image showing the new test window with the title and description forms.
New test window

Now:

Add the test title
Add the following template inside the test description and replace the description with your test details:
### Description
Add the description of the test here

### Prerequisite
* Add prerequisite 1 for the test here
* Add prerequisite 2 for the test here

### Steps
1. Step 1
*Expected:* What to expect after executing this step

2. Step 2
*Expected:* What to expect after executing this step

...

n. Step n
*Expected:* What to expect after executing this step

### Expected result
What is the expected result. Example: This test passes if something and something happens or fails if something else happens.
Save the test by clicking on the Save button.
Image shows the test case form showing the title, description and save button
Filling the test data and saving the test case

Your test is saved inside the Suite, now you can start creating new tests.

Creating Test cases
Verification test cases
Create a test suite named Verification and create test cases to verify:

Motion sensor integration
Door/window sensor integration
Water leak sensor integration
Security camera integration,
Verify login functionality (correct and fail)
Remember what the system must do and write a test case to verify each one of the requirements.

Validation test cases
Create a test suite named Validation and create test cases scenarios for the following validation methods:

Motion detection and alert notification
Door/Window sensor activation
Remote camera access and live view
System arm/disarm functionality
Simultaneous sensor triggers (3 or more sensors being triggered at the same time)
High volume user access (3 or more devices accessing and interacting with the app at the same time)
Note: How to download created test cases from testomat:

Go to the left menu, click on Tests
Click on the three dot button on the top right.
Select, export as Spreadsheet
Save the file for submission
Image showing how to export test case as spreadsheet for submission
Exporting test cases