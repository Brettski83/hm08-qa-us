Name: Project 8
Description: The objective of this project is to write several, individualized automated tests, checking the overall functionality of 'ordering a taxi' in the Urban Routes app. 
Technologies and techniques used: Visual Studio Code(software) Firefox and or Chrome(browser). WebdriverIO, E2E testing, JavaScript, Node.js, mocha. 
Test instructions: Ensure that Visual Studio Code has been installed on your computer. Install WebdriverIO directly on to VS Code. WebdriverIO is a tool to run automated(UI) tests. The method of testing will be End-to-end. CSS Selectors will be used in conjuction with Devtools. JavaScript is the language used in conjunction with Node.js for this project.  
Running the test: Write individual tests for the following steps below of 'ordering a taxi' in the Urban Routes app. Use the npm run wdio command to run the tests.
 
1. Setting the address
2. Selecting Supportive plan
3. Filling in the phone number
4. Adding a credit card (Tip: the “link” button doesn’t become active until the card CVV field on the “Adding a card” modal id=”code” class=”card-input” loses focus. To change focus you can simulate the user pressing TAB or clicking somewhere else on the screen).
5. Writing a message for the driver
6. Ordering a Blanket and handkerchiefs (Tip: there are two selectors to be aware of here. One selector to click on and one to run expect on to verify that the state changed).
7. Ordering 2 Ice creams
8. The car search modal appears
9. Waiting for the driver info to appear in the modal (optional) In addition to the steps above there is an optional step you can check. This one is a bit more tricky than the others but it’s good practice since you will likely encounter more difficult tasks in your career.

Remember: Use the 'describe & it' functions from the mocha library for a more organized and structuted test.
Write your tests in the createAnOrder.e2e.js file located in the test/specs folder.
Store(input) your locators in the page.js file.
The wdio.conf.js file is for pasting your URL.
Upon completion of writing your test(s) Use the npm run wdio command to run the test(s).