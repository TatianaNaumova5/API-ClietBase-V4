Orders page dashboard + Orders Detailed View
User story: As a user, I should be able to see the list of my orders
There is a nav-bar in the top left corner, which contains Logo link ClientBase, 4 links Clients, Orders, Vendors, and Services. All links redirect to corresponding pages.
Username link in the right top corner opens a dropdown with the Profile and Logout links which are clickable and redirect to corresponding pages.
Active link/btn in nav-bar should be underlined / highlighted.


From the order dashboard user should be able to see the list of his orders with the main information about (19 columns on dashboard in total):

Created

Client

Service

Client

Price

Paid

Debt

Vendor

Price

Paid

Debt

Profit

Actual

Plan

Client paid

Sent to vendor

Vendor done

Got from vendor

Paid to vendor

Informed client

Client received

Action



There should be an Action column with action ellipsis, which opens dropdown with Edit and Delete options.

Edit:
When the user chooses the edit option, a drawer with the prefilled form opens on the right side of the window and the user can edit an order.
Field ‘Client’ is inactive/unable to change.
Field ‘Service’ should be a dropdown with all services listed in Services dashboard. The user is not able to create a new service in the Edit order option but can choose any service from the existing list.
Fields ‘Client Price’, ‘Client Paid’, ‘Vendor Price’, ‘Vendor Paid’ are required / mandatory.
Field ‘Description’ is not mandatory and accepts any alpha-numeric characters and symbols.


Delete:
When the user chooses the Delete option, a confirmation modal window with the name of the order and 2 buttons appears in the middle of the page. Users can discard deleting by clicking the Cancel button or delete by clicking OK button.


Search:
There are 2 search fields with the placeholders Client Name and Service Name respectively.
Search fields have no restrictions and users can enter Latin letters, numbers and symbols.
If the search can't find any matches the dashboard will be empty.
Reset button is always active, resets search and deletes the values from both search fields.


There should be an active Create Order button, which opens the drawer with an empty order's form (see Orders drawer BRD).

Pagination:
The user can see 20 rows on a page. When the total number of entries exceeds 20, the counter under the dashboard shows the total number of Orders (items) and page numbers.
Page number is displayed in clickable BTN.

The ‘Next page’ BTN becomes active when the current page is not the last one.
The ‘Previous page’ BTN becomes active when the current page is not the first one.

When the number of pages exceeds 5, the first and the last pages are always shown.

If the current page number is smaller than the last page number by five or more, the ellipsis and the “next 5 pages’’ BTN appear.
e.g. the last page is #8, the current page is #4, then the ellipsis “next 5 pages’’ appears.

If the current page number is bigger than the first page by five or more, the ellipsis and the “previous 5 pages’’ BTN appear.
e.g. the current page is #5, the first page is #1, then the ellipsis “previous 5 pages’’ appears.

The user can go to any page by clicking its BTN.
New entity created by the user should appear as the first element on the list.


Columns:

‘Created’ column contains the date (dd month) of the created order and time in am/pm format.

‘Client’ column contains Client Name, is clickable and leads to the Client's page with a detailed view of all Client’s orders.   

‘Service’ column contains Service Name, is clickable and leads to the Service’s page.  

‘Client Price’.

‘Client Paid’.

‘Client Debt’ column is calculated automatically as a difference between ‘Client Price’ and ‘Client Paid’ and can not be changed by the user.

‘Vendor Price’.

‘Vendor Paid’.

‘Vendor Debt’ column is calculated automatically as a difference between ‘Vendor Price’ and ‘Vendor Paid’ and can not be changed by the user.

‘Profit Actual’ column is calculated automatically as a difference between ‘Vendor Paid’ and ‘Client Paid’ and can not be changed by the user.

‘Profit Plan’ column is calculated automatically as a difference between ‘Vendor Price’ and ‘Client Price’.

In columns #6 and #9 the positive number is shown in bold red font, the negative number is shown in regular font,
In column #10 the negative number is shown in bold red font, the positive number is shown in regular font.

‘Client paid’ column. ‘Pay’ label appears if the ‘Client Debt’ column is more than a zero. Green checkbox label appears if the ‘Client Debt’ column is zero or less.
‘Sent to vendor’ column. ‘Send’ label is set by default.
‘Vendor done’ column. ‘Done’ label is set by default.
‘Got from vendor‘ column. ‘Got’ label is set by default.
‘Paid to vendor’ column. ‘Pay’ label appears if the ‘Vendor Debt’ column is more than a zero. Green checkbox label appears if the ‘Vendor Debt’ column is zero or less.
‘Informed client’ column. ‘Info’ label is set by default.
‘Client received’ column. ‘Recd’ label is set by default.
‘Action’ column with action ellipsis, which opens dropdown with Edit and Delete options.

Columns #4-5 and #7-8 can be edited when the user uses the Edit option in the ‘Action’ column and these fields accept only positive numbers (integers/fraction).

Columns #12-18 are displayed as a clickable BTN, are calculated automatically and can be changed by the user by clicking the label / checkbox.
NB!
The user is not able to click the green checkbox in columns 12.‘Client paid’ and 16.‘Paid to vendor’ and if ‘Client Debt’ or ‘Vendor Debt’ are more than zero respectively.

