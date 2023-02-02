Home Page


1.  By navigating to the home page users can see:
   “ClientBase” logo is in the upper left corner.
2. “Login” and “Get started - it’s free” links are in the upper right corner:
   “Login” should redirect the user to the login page;
   “Get started - it’s free” should redirect the user to the Register page.
3. In the middle of the Main Page the user can see three  types of text:
   The 1st header with tag <h1> => “Dispatching and accounting for service companies” - at the top and in the middle of the page;
   The text => “The easiest way to manage the process of receiving and transmitting an order.” is located under the 1st header in the middle of the page;
   The 2nd header with tag <h1>  =>  “Create an account” is located below the text in the middle of the page
4. The registration fields are located under the 2nd header in the middle of the page with the following placeholders:
   “First Name” - located on the left half of the page under 2nd header ;
   “First Name” field accepts:
   Latin letters only(A-Z, a-z);
   Digits (0-9);
   Special characters: #-_~!$&'()*+;=:@.
   Spaces between characters are allowed (“Anna Maria”);
   Leading and trailing spaces should be trimmed;
   Min 3 characters;
   If less than 3 characters are entered into the field, error ”Min 3 characters” in red color with appears under the field;
   User can print max 100 symbols;
   If user enters more then 100 symbols into the field, error = "Must be less than 100 characters" appears under the field;
   If the field is empty, error = “Required” appears under the field;

“Last Name” - located on the right half of the page next to “First Name”;
“Last  Name” field accepts:
Latin letters only (A-Z, a-z);
Digits (0-9);
Special characters: #-_~!$&'()*+;=:@.
Spaces between characters are allowed (“Anna Maria”);
Leading and trailing spaces should be trimmed
Min 3 characters;
If less than 3 characters are entered into the field, error ”Min 3 characters” appears under the field;
User can print max 100 symbols;
If user enters more then 100 symbols into the field, error = "Must be less than 100 characters" appears under the field;
If the field is empty, error = “Required” appears under the field;

“Email” - located under fields “First Name” and “Last Name”;
“Email” field accept:
Email syntax: xxx@xxx.xxx
Latin letters (A-Z, a-z);
Digits (0-9);
All symbols from the keyboard !@.#$%^&*()_?><+={}[]/
Spaces between characters are not allowed;
Leading and trailing spaces should be trimmed;
Length restrictions for each email part:
Local part: min 1 char, max 64 char
Domain part: min 1 char, max 253 char
High-domain part: min 2 char, max 11 char
User can print min 6 symbols;
User can print max 330 symbols;
If the user enters an invalid email format, error = “Email is not valid email” should appears under the field
If the field is empty, error = “Required” appears under the field

“Password” - located under field “Email”;
“Password” field accepts:
Latin letters (A-Z, a-z);
Digits (0-9);
All symbols from the keyboard !@.#$%^&*()_?><+={}[]/
Spaces between characters are not allowed (“adaf dtfuu”);
Leading and trailing spaces should be trimmed;
User can print min 8 characters;
User can print max 30 characters;
If the user enters an invalid Password, error =”Password is not valid password” should appears under the field;
If the field is empty, error = “Required” appears under the field
Entered password is hidden with dots. Users are able to see the symbols after clicking the eye icon;

The submit button “Register” - located in the middle, under “Password”.
Register button is disabled by default.
When all fields on the page are filled with valid value - “Register” button is enabled and redirects to the onboarding page.
5. Under the “Register” button in the middle of the page, any user can see text "Already have an account? Just click "Log in." The link “Log in” should redirect the user to the login page.

