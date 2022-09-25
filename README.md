# API-Automation-with-Postman

## Technology and Tools used
- Postman
- Newman

## Scenario of the Project
- Admin will login to the system
- Create a Customer and Agent
- Deposit money to the newly created Agent
- Agent will deposit money to the newly created Customer
- Customer will withdraw money from the Agent
- Customer will send money to the other customer

## Prerequisite
***You must have installed the followings***
- Node.js
- Newman

      npm i newman
      
- HTML Extra

      npm i newman-reporter-htmlextra
      

## How to run the project
- Clone the project
- Run the following command to execute the collection

      npx newman run .\collection\collection.json 

- Run the command to generate HTML Report

      npm test 

 



