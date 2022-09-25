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

## Test Cases Link
https://docs.google.com/spreadsheets/d/1a0wLac1Ia2a84V4-8CJ2pktmoqk7tRw3XEjVSAPhSkw/edit?usp=sharing

## Bug Report
https://docs.google.com/spreadsheets/d/1ElMfzx2NnxbGsEHwYpbJzOT89NTNT0BixYWRHtO9-hc/edit?usp=sharing

## API Documentation
https://documenter.getpostman.com/view/15460728/2s83KXdNa6

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

## Output Screenshot
- Summary

![image](https://user-images.githubusercontent.com/58165269/192123935-449bd234-eea2-4ded-9f3e-3f537435020b.png)


- Total Requests

![image](https://user-images.githubusercontent.com/58165269/192123969-5f023ef9-428b-4a10-9948-98dfbe94d13e.png)


- Failed Tests

![image](https://user-images.githubusercontent.com/58165269/192123981-3a15357b-5b34-4ff4-83b1-55da9fd34b67.png)




