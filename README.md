# QA API Testing – Postman & Newman

Automated API testing project using Postman for request design and assertions, and Newman for command-line execution and reporting.

## What is covered

- REST API testing (GET, POST, PUT, DELETE)
- Postman collections and environments
- Assertions and data validation
- Environment variables
- Command-line execution with Newman
- HTML test reports

## Tools & Technologies

- Postman
- Newman
- Node.js
- JSONPlaceholder (public mock API)

## How to run the tests

Install dependencies:
`npm install`

Run API tests:
`npm run api:test`

Generate HTML report:
`npm run api:report`

## Project structure

postman/
 ├─ collections/
 └─ environments/

newman/
 └─ reports/
package.json

## Notes

This project uses a public mock API. POST requests return simulated data for testing purposes.


