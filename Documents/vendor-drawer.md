Vendors Drawer

User story: As a user, I should be able to create a new vendor.

On the top of the drawer at the left side the user should see the gray cross mark and the header ‘Create Vendor’ next to it. There are 4 fields with the labels ‘Name’, ‘Phone’, ‘Email’ and ‘Description’. Each field is located next down to each other. There is a ‘Create’ button which is located under the last field at the left side of the drawer and always enabled by default. The ‘Name’ field is the required information and marked with an asterisk, so the user can not create the vendor without filling this field out. If the user will not fill out the ‘Name’ field, the red ‘Required’ error message should appear under the field.

‘Name’ field accepts:

Latin letters only (A-Z, a-z)

All symbols from keyboard

Min 3, max 100 characters

The field should accept spaces

If less than allowed min of characters are entered into the field, the red error ‘Must be more than 2 characters’ should appear under the field

If more than allowed max of characters are entered into the field, the red error ‘Must be less than 101 characters’ should appear under the field

‘Phone’ field accepts:

Digits only (0-9)

Special characters (+ ( ) -)

Min 10, max 16 characters

If less than allowed min of characters are entered into the field, the red error ‘Must be more than 9 characters’ should appear under the field

If more than allowed max of characters are entered into the field, the red error ‘Must be less than 17 characters’ should appear under the field

If the user fills out letters or invalid special characters, an error message ‘Must contain digits and ()-+’ should appear under the field.

‘Email’ field accepts:

Lealetters only (A-Z, a-z)

Digits only (0-9)

Special characters (#-_~!$&'()*+;=:@.)

There are length restrictions for each email part:

Local part: min, 1 max 64

Domain name: min, 1 max 253

Top-level domain: min 2, max 11

If less than allowed min of characters are entered into the field, the red error ‘Must be more than 5 characters’ should appear under the field

If more than allowed max of characters are entered into the field, the red error ‘Must be less than 331 characters’ should appear under the field

Email must meet the syntax requirements such as xxx@xxx.xxx

If the user fills out invalid data, the red ‘Email is not valid email’ error message should appear under the field.

‘Description’ field accepts:

All upper and lower case letters

Digits (0-9)

All symbols from the keyboard

No length restrictions

Leading and trailing spaces should be trimmed at all of the fields.

After submitting the form, saved information should appear on the dashboard on the corresponding columns. The newly created vendor appears as the first element on the list.

The user should be able to exit the drawer without submitting the form by clicking on the gray cross mark.
