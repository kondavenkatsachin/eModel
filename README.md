# Introduction 
  This cypress automation framework helps to test E2E UI along with API functionalities.
# Getting Started
# Prerequisites
1) Install IDE
It's a good idea to have an IDE. Visual Studio Code is the preferred IDE for Cypress projects.
You can download Visual Studio Code from here: https://code.visualstudio.com/download

2) Install Node.js
We need to install Node.js because we need to use npm and npx which get downloaded along with node.js.
You can download node.js from here: https://nodejs.org/en/download/

3) Install git
You can download git from here: https://git-scm.com/downloads

# Installation And SetUp
# Steps To Clone Git Repo 
1) Go to location where you want to clone the project. Right click and choose “git bash here”
![Step 1](./Images/Step1.png)
1) Clone the repo using this git command --->
   git clone https://aisemodal.visualstudio.com/eModal%20Product/_git/eModal.TestAutomationTemplate
![Step 2](./Images/Step2.png)
1) Once the repository cloning gets completed then below screen will be displayed
![Step 3](./Images/Step3.png)
1) Go to “eModal.TestAutomationTemplate” directory and press enter below screen will be displayed
![Step 4](./Images/Step4.png)
1) After changing the directory you will be shown on main branch as shown below
![Step 5](./Images/Step5.png)

# Project Set Up In Visual Studio Code
1) Open visual studio code and choose open folder
![Step 6](./Images/Step6.png)
1) Select the framework folder and then in visual studio code project structure will be as shown below
![Step 7](./Images/Step7.png)

# Automation Script Development Process 
In framework there are two folders inside integration folder and those are API and UI. For example if someone wants to develop UI automation script go to UI_Tests under Integration folder and create .js file as shown below.
![Step 8](./Images/Step8.png)
1) Declare  UI elements within describe block as shown below. Mention the references upon the describe block
![Step 9](./Images/Step9.png)
1) Inside "it" block you can develop the test case as shown below. 
![Step 10](./Images/Step10.png)
1) Similarly To create API test scripts. Go to API_Tests which is inside integration folder and create a js file as shown below
![Step 11](./Images/Step11.png)
1) Inside it block start creating test script as shown below.
![Step 12](./Images/Step12.png)

# Framework Components
To develop UI or API scripts this framework contains reusable methods inside common_methods folder. Reusable methods such as browser_actions, api_methods, DB_methods and test_datamethods.
# Browser Actions
![Step 13](./Images/Step13.png)
# API Methods
![Step 14](./Images/Step14.png)
# DB Methods
![Step 15](./Images/Step15.png)
2)    For rest of the installations move to project folder in visual studio code or in command prompt and type npm install .
# Running Tests
1) To run UI tests type this command at Visual studio terminal ----> npm install cypress:run-ui
2) To run API tests type this command at Visual studio terminal ----> npm install cypress:run-api
# View Test Execution Result Report
  To view reports go to project reports folder and click on index.html file 
  
