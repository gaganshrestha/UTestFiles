# UTestFiles
Cypres test files for UI and REST API testing

Steps:

<b>Installations requirements</b>
___________________________

1. Install node.js (version >= 14) (https://nodejs.org/en/download/).
2. Install latest Cypress (10.10.0) (https://docs.cypress.io/guides/getting-started/installing-cypress). 
3. Install cypress mochawesome reporter (https://www.npmjs.com/package/cypress-mochawesome-reporter).

<b>Configurations</b>
____________________________________

1. Ensure to update the content of the following enclosed files in the local cypress project:
  a. cypress.config.js
  b. cypress/support/e2e.js
  

<b>Test files<b>
____________________________________

Copy the following enclosed files in the local cypress project:

  1. cypress/support/landingPageSelectors.js
  2. cypress/support/LoginPageSelectors.js
  3. cypress/fixtures/requestBody.json
  4. cypress/e2e/apiTests.cy.js
  5. cypress/e2e/UITests.cy.js
  
  
 <b>Running tests / access test report</b>
 ____________________________________
 
 1. From your project directory, run the following command:
    `npx cypress run --browser chrome`
    
 2. HTML report will be created under the local project directory - `cypress/reports/html/index.html`. Open the file in the browser.
    
 
 
