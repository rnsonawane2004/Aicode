| Test Case Id | Test Description | Pre-Conditions | Expected Results | Actual Results | Status |
|--------------|------------------|----------------|------------------|----------------|--------|
| COMP01 | Verify navigation to Customers Page | User logged in and on Home Page | User should see 'Customers' option under 'Sell' dropdown and navigate to Customers Page | | |
| COMP02 | Verify 'New Customer' button functionality | User on Customers Page | Clicking 'New Customer' should open 'Add New Company Form' | | |
| COMP03 | Verify mandatory fields in form | User on 'Add New Company Form' | 'Company Name' and 'Currency' should be marked as required and form should validate these fields before submission | | |
| COMP04 | Verify form submission with all fields filled | All required and optional fields filled correctly | Form should submit, save company info, and redirect to Customers Page with new company listed | | |
| COMP05 | Verify form submission with only required fields filled | Only 'Company Name' and 'Currency' filled | Form should submit, save company info, and redirect to Customers Page with new company listed | | |
| COMP06 | Verify error handling for empty required fields | 'Company Name' or 'Currency' not filled | Form should prompt user to fill required fields | | |
| COMP07 | Verify Cancel button functionality | User on 'Add New Company Form' | Clicking 'Cancel' should close the form and return to Customers Page without saving changes | | |