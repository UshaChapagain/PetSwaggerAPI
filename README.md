# Karobar API Assignment - PET SWagger
This repository contains automated tests for the PetStore Swagger API, which is publicly available for testing purposes. The API can be accessed at [PetStore Swagger](https://petstore.swagger.io/).
These tests verify that the API functions correctly and meets its defined requirements.

## **Project Structure**

```
KarobarAPIassignment
│
├─ KarobarAPIassignment/
│ └─ Testcases
├─ reports/ # Newman HTML reports (generated automatically)
├─ package.json # npm configuration & scripts
├─ .gitignore 
└─ README.md 
```

## Getting Started

These instructions will guide you through setting up and running the API tests on your local machine.

## **Prerequisites**
- [Node.js](https://nodejs.org/)
- npm 
- Newman (Postman CLI tool)

Setup Instructions:

1. Clone the repository:
```
git clone https://github.com/UshaChapagain/APIPractice.git
cd karobarAPIassignment
```


2. Install project dependencies:
```
npm install
```

3. Running Tests

The project uses npm scripts to run Newman tests and generate HTML reports.
Run all API tests:
```
npm run run-api-tests
```
CLI output shows test results in the terminal.

The detailed test report is available at reports/newman-report.html. Open this file in a web browser to inspect the results.



