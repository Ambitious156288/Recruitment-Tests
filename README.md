# Herokuapp Login Test (Playwright)

This automated test verifies a successful login on the following website:  
https://the-internet.herokuapp.com/login

## Prerequisites
```bash
git clone https://github.com/Ambitious156288/Recruitment-Tests.git
```

```bash
npm install
```

```bash
npm run watch
```
or
```bash
npm run test
```

 


## Test Steps

Below are the detailed steps performed by the automated test:

1. **Navigate to the login page**  
   The test opens the page: `https://the-internet.herokuapp.com/login`

2. **Enter login credentials**  
   The test fills in the login form automatically:
   - **Username** field: `tomsmith`
   - **Password** field: `SuperSecretPassword!`

3. **Click the login button**  
   The test clicks the **Log in** button to submit the form.

4. **Verify success message**  
   After a successful login verify success message..

5. **Verify redirect to '/secure' url**  
   After a successful login verify url 'secure'.

## Test file 

You should write your test cases in /tests/interview.spec.js
