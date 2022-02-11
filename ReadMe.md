## Part I. Testing us (kevin.) 
Write a script to test a payment in kevin. demo page.

- Go to [kevin. website](https://kevin.eu)
- Accept all cookies
- Navigate to the demo page from the top toolbar
- Choose redirect payment flow
- Fill all the fields with data (0.01 for payment amount, your own email for email)
- Find the checkbox for terms and conditions but don't click it at first
- Choose Swedbank as the payment bank
- Click PAY
- Check if the error message for Terms and Conditions checkmark appears
- Check the checkmark for terms and conditions
- Proceed with payment

**Bonus Points**
- Save the cookies after accepting them and write an extra `it` statement that will reopen [kevin. website](https://kevin.eu) and check cookies content
- Feel free to add any assertions and checks you see fit
- Please make sure that URLs used in the test are initiated as variables
- Make **base URL** a configurable variable
- Make **amount** and **email** variables environmental
- Assert that the error message when terms are not accepted is marked with a certain colour

## Part II. Testing us (kevin.)
Find our documentation [here](https://docs.getkevin.eu/public/platform/v0.3), prepare and execute tests for the [Payment Initiate Endpoint](https://docs.getkevin.eu/public/platform/v0.3#operation/initiatePayment). 

Tests format and execution method is up to you:

1. Test plan (sheet) of your desired format with test results attached
2. API testing tool set, such as Postman collection with test scripts for each case/scenario
3. Automatic test scripts, written on test automation frameword, such as Cypress, Selenium, etc.
4. None of the above, in which case please provide a reference for you chosen approach and comprehensive remarks on the execution

## Remarks
- Feel free to use any test tool you find suitable for this task (e.g. Postman, Cypress, Selenium).
- Please include `README.md` with instructions how to launch tests.

## Submitting the task
Upload the completed task to GitHub and send us a link to `code@kevin.eu`.

- Make sure you don't mention `kevin.` anywhere in the code or repository name.
- Please include how long it took for you to do the tasks.# kevin.qa.try-out
