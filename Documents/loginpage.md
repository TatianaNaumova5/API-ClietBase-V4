Login page

On the login page:

Top left of the page a user can see the ‘ClientBase’ Logo 
(Located on the top left corner above the header) which is clickable and will redirect user to the main page.

Header - Welcome back! - (Located on the top left corner under the logo.)

2 fields with the placeholders Email and Password. (Under the header)

When a user enters invalid data, an error should appear under the field(s) and red cross marks appear in the field(s).

When a user enters valid credentials, a green checkmark appears in the field(s).
Button Login is disabled by default. (Bottom left under the password field)
When a user fills out the form and no errors appear, the button becomes active.

There are 2 prescriptions under the button:
Don’t have an account? Create one. with the link Create one. which opens the register page

Forgot your password? Reset it. with the link Reset it. which opens the reset password page. If the user submits invalid credentials pop-up Authorization failed appears.


Email field accepts:

Latin letters (A-Z, a-z)

Digits (0-9)

Special characters (#-_~!$&'()*+;=:@.)

There are length restrictions for each email part:

Local part: min 1, max 64

Domain name: min 1, max 253

Top-level domain: min 2, max 11

Email must meet the syntax requirements such as xxx@xxx.xxx

If user enter invalid email format, error 'Email' is not a valid email should appear under the field;

If less than allowed min of characters are entered into the field, error Must be more than 5 characters should appear under the field;

If more than allowed max of characters are entered into the field, 

Password field accepts

All letters

All symbols from the keyboard except space

Min 8 characters, max 30

Entered password should be hidden with dots. Users are able to see the symbols after clicking the eye icon

If less than allowed min of characters are entered into the field, error Must be more than 7 characters should appear under the field;

If more than allowed max of characters are entered into the field, error Must be less than 31 characters should appear under the field;

An error Required in red color should appear under the field;

Leading and trailing spaces should be trimmed;

Clients page dashboard + Client Detailed View


1)	User story: As a register user, I should be able to view the list of my clients
      There is a nav-bar in the top of the page, which contains Logo ClientBase, 4 highlights  links: Clients, Orders, Vendors, and Services, which redirects to a corresponding pages. When the user is on the page, the relevant link is underlined. There is Username on the right side, which opens dropdown with the Profile, and Logout.
      Under nav-bar there are three search fields with placeholders: Name, Phone, Email and “Reset” BTN. Search fields find corresponding row with Client data from the Client list. For success search must be enough to fill a few characters in any field. The search begins from the first character in the field.

Search fields have no restrictions and users can enter any letters, numbers and symbols.
If the search can't find any matches the dashboard will be empty.
Leading and trailing spaces should be trimmed;

“Reset” BTN is active and clickable by default. It deletes all data from the search fields.
There is “Create Client” BTN on the right side. This BTN allow a register user to create a new Client, when the user fills in all required fields on drawer, which appears after “Create Client” click.
The Client dashboard consist from 5 columns with titles:
-   	1st column: Name. It shows the clients names. Client name is the link and redirect users to detailed Client page with all Clients data.
-   	2nd column: Phone. It shows the clients phone numbers.
-   	3rd column: Email. It shows the clients email.
-   	4th column: Description. It shows additional data, notes or detail of Client.
-   	5th column: Actions. There is an action ellipsis, which opens dropdown on click, in every cell of this column, which allow a user to Edit or Delete corresponding client. The user can click on ellipsis and choose one option (Edit or Delete) on the drawer.
     The Clients data sets in the rows of dashboard.
     The user can see 20 rows on page. When whole number of clients increase more then 20, the counter under dashboard shows number of clients and number of necessary pages. Numbers of pages are clickable BTN. The user can go to the new page by click on the any BTN.

2)	User story: As a register user, I should be able to view the full information of my clients
      When user click on link in the column “Name” the Client page must open.    
      There is a nav-bar in the top of the page, which contains Logo ClientBase, 4 links Clients, Orders, Vendors, and Services, which redirects to a corresponding pages. When the user is on the page, the relevant link is underlined. There is Username on the right side, which opens dropdown with the Profile, and Logout.

There is header “Client Name”  on the left upper side'

Under the header user can see 2 columns. 1st column on the right, 2nd column on the left.
Every column consists from 2 parts. Left part consists key words, right part consists their values.
1st column key words:
Created – the date of creating of that Client. The date should be given in AM:PM format.
Updated – the date of last update of that Client. The date should be given in AM:PM format.
Email – email of that Client
Phone – the phone number of that Client
Notes – additional data of that Client
2nd  column key words:
Total Paid – the amount, which was paid by Client
Total Debt – the amount, which Client will have to pay
Total Profit Actual – amount of profit which Company received
Total Profit Potential – amount of profit which Company planned to receive
Lower the user can see all Orders of chosen Client
There is the header “Orders”  on left side, and the window indicate the amount of orders.
There is “Create Order” BTN on the right side. BTN is active and clickable by default.  Click on this BTN opens the drawer which allows a user to create new order of chosen Client.

Under the header there is the Order dashboard of chosen Client. Order dashboard shows whole information of all orders. It consists from 13 columns:
-   	1. Created – date of creation of the Order. The date should be given in AM:PM format.
-   	2. Service – name of service. It is the link, which redirect to page of detail information of Service.
-   	3. Client – consists from 3 parts: Price (price of service), Paid (amount which Client paid) and Debt (amount which Client will have to pay). ). The number in the Debt cell is calculated automatically as the difference between Price and Paid. If the client paid less than Price, the amount in the Debt cell is red. If the client paid more than Price, then the amount in the Debt cell is black and has a minus. When the number in the Paid cell is equal to the number in the Price cell, the number in the Debt cell is 0. When the number in the Debt cell is black, the word 'Pay' in the ‘Client paid’ cell automatically changes to a green checkbox. The user can only enter data using the Edit function in the Actions column.
-   	4. Vendor -  consists from 3 parts: Price (price of service), Paid (amount which Company paid to Vendor) and Debt (amount which Company will have to pay Vendor). The number in the Debt cell is calculated automatically as the difference between Price and Paid. If the Company paid less than Price, the amount in the Debt cell is red. If the Company paid more than Price, the amount in the Debt cell is black and is minus. When the number in the Paid cell is equal to the number in the Price cell, the number in the Debt cell is 0. When the number in the Debt cell is black, the word 'Pay' in the ‘Paid to vendor’ cell automatically changes to a green checkbox. The user can only enter data using the Edit function in the Actions column.
-   	5. Profit – consists from 2 parts: Actual (amount of profit which Company received) and Plan (amount of profit which Company planned to receive). The user cannot enter data into this column by himself. The number in the ‘Actual’ cell is automatically calculated as the difference between the ‘Client paid’ and ‘Vendor paid’ cells. The number in the ‘Plan’ cell is automatically calculated as the difference between the ‘Client price’ and ‘Vendor price’ cells.


Those three columns (3, 4, 5) show the numbers values.
-   	6. Client paid – shows whether Client has paid or not on the last update date. Value is highlight and clickable word “Pay”, which changes on green check-box, when click. If the user changes the clickable word "Pay" to the green check-box by click, the numbers in the ‘Client paid’ and ‘Client Debt’ cells automatically change. In the ‘Client Debt’ cell appears 0. The user must be able to edit this action.
-   	7. Sent to vendor - shows whether Order was sent or not to Vendor on the last update date. Value is highlight and clickable word “Send”, which changes on green check-box, when click. The user must be able to edit this action.
-   	8. Vendor done - shows whether Vendor has done or not the Order on the last update date. Value is highlight and clickable word “Done”, which changes on green check-box, when click. The user must be able to edit this action.
-   	9. Got from Vendor - shows whether Company has got or not the Order from Vendor on the last update date. Value is highlight and clickable word “Got”, which changes on green check-box, when click. The user must be able to edit this action.
-   	10. Paid to vendor - shows whether Company has paid or not to Vendor on the last update date. Value is highlight and clickable word “Pay”, which changes on green check-box, when click. If the user changes the clickable word "Pay" to the green check-box by click, the numbers in the ‘Vendor paid’ and ‘Vendor Debt’ cells automatically change. In the ‘Vendor Debt’ cell appears 0. The user must be able to edit this action.
-   	11. Informed Client - shows whether Company has informed Client or not to Vendor on the last update date. Value is highlight and clickable word “Info”, which changes on green check-box, when click. The user must be able to edit this action.
-   	12. Client received - shows whether Client has received the Order or not on the last update date. Value is highlight and clickable word “Recd”, which changes on green check-box, when click. The user must be able to edit this action.
-   	13. Action. There is an action ellipsis, which opens dropdown on click, which allow a user to Edit or Delete corresponding order. The user can click on ellipsis and choose one option (Edit or Delete) on the drawer.
         All Clients data sets on the raw in accordance every column.
3)	User story: As a user, I should be able to edit or delete my client
      The user can edit or delete Client on the detailed Client page after redirection.
      At the right from Header should be the Pencil icon, which opens dropdown on click, with Edit and Delete options.

When user chooses edit option, drawer with the prefilled form opens on the right side of the window and user can edit an entity.
When user chooses delete option confirmation modal window with the name of the entity and 2 buttons appears in the middle of the page. User can discard deleting by clicking Cancel button or delete it by clicking OK button.
