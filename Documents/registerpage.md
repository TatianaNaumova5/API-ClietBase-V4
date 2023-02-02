#REGISTER PAGE

##As a new user, I should be able to register in the application.

On the register page user can see the header “Create an account”, 4 fields for the First Name, Last Name, Email  and Password with the placeholders. If a user enters invalid data, an error should appear under the field(s) and red cross marks appear in the field. When a user enters valid credentials green checkmarks appear in the field.

First and last name fields accepts:
Latin letters (A-Z, a-z)
Digits (0-9)
All symbols from the keyboard
Min 3 characters, max 100
If less than allowed min of characters are entered into the field, error Min 3 characters should appear under the field
If more than allowed max of characters are entered into the field, error Min 100  characters should appear under the field;
No spaces allowed. If enter a spaces in the fields should be appear red Special characters are not allowed
Email field accepts:
Latin letters (A-Z, a-z)
Digits (0-9)
Special characters (#-_~!$&'()*+;=:@.)
There are length restrictions for each email part:
Local part: min 1, max 64
Domain name: min 1, max 253
Top-level domain: min 2, max 11
Email must meet the syntax requirements such as xxx@xxx.xxx
If user enter invalid email format, error “Email” is not a valid email should appear under the field;
If less than allowed min of characters are entered into the field, error Must be more than 5 characters should appear under the field;
If more than allowed max of characters are entered into the field, error Must be less than 331 characters should appear under the field;
Password field accepts:
All letters
All symbols from the keyboard except space
Min 8 characters, max 30
Entered password should be hidden with dots. Users are able to see the symbols after clicking the eye icon
If less than allowed min of characters are entered into the field, error Must be more than 7 characters should appear under the field;
If more than allowed max of characters are entered into the field, error Must be less than 31 characters should appear under the field;
No spaces allowed. If enter a spaces in the field  should be appear red “Email” is not valid email
An error Required in red color should appear under the field;
Leading and trailing spaces should be trimmed;
Submit button with the text Register Button is disabled by default and enabled when the user fills out  the form with valid data;
Under the Register button the user can see the prescription Already have an account? Just click Log in with the link Log in, which redirects users to the Login page.
After submitting the form email with a confirmation link must be sent to the user and role NEW should be assigned. User will be able to get inside the application but main functionality will be restricted and not shown.
After confirming the email, user will be redirected to the page with the link Continue which will redirect the user to the onboarding process, and role VERIFIED will be assigned. After that user will have full access to the application.


