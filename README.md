## API Testing Report

#### [Booking](https://api-testing-report1-sakib.netlify.app/)
#### [Student Details](https://api-testing-report2-sakib.netlify.app/)

## Method
- POST
- GET
- PUT
- DELETE

## Command

1) **Newman Install:**
   - npm install -g newman

2) **Reporter Install:**
   - npm install -g newman-reporter-html
   - npm install -g newman-reporter-htmlextra

3) **Report Generate:**
   - newman run "..\CollectionName.json" -e "..\EnvironmentName.json" -r cli,html
   - newman run "..\CollectionName.json" -e "..\EnvironmentName.json" -r cli,htmlextra 
