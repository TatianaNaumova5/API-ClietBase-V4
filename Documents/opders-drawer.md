Orders Drawer

The registered and verified user can start creating a new order on the Orders Page
( https://clientbase.us/v4/order) by clicking the "Create Order" button.
Drawer (Modal window) with label "Create new Order" opens by sliding out from the right side of the page and stays open on the right half of the same page.

After filling all required fields in the Drawer (*Client, *Service, *Client Price, *Client Paid,  *Vendor Price, *Vendor Paid - all are marked with red asterisks(*)), and clicking the "Create" button, the User can create a new Order.

If the user tries to create an Order with the empty required fields, the red error message "Required" appears under the empty fields and no new order will be created.

Drawer “Create new Order” has the next entities:

1.    The button “X” is located on the left upper corner. “X” is highlighted when the cursor placed on. User is able to close the Drawer by clicking the button “X”. User is able to close the window by clicking outside of the Drawer. Changes will not be saved and will not be appears in the columns on Orders dashboard.

2.    Header “Create new Order”. Located on the left upper corner, right of the button “X”.

3.    The “Client” field is required and is marked with a red asterisk. Border is highlighted when the cursor placed on border or the field. The field has a placeholder “Select a client” and arrow down mark. User is able to choose the existing Client from the drop-down list by clicking on the field or arrow down mark. When creating an order while the client exists, the system will automatically indicate the existing Client's Name and Phone in the drop-down list. An error message “Required” in red color appears under the field if the field is empty after submitting the form.

4.    The “Service” field is required and is marked with a red asterisk. Border is highlighted when the cursor placed on border or the field. The field has a placeholder “Service” and arrow down mark. User is able to choose the existing Service from the drop-down by clicking on the field or arrow down mark. When user opens a drop-down, the system automatically provides the list of services, where, in the following order, are shown: Service Name, Vendor Name, Vendor Price and Client Price. Required fields "Client Price" and "Vendor Price" are pre-filled automatically after choosing the Service in the “Service” field. An error message “Required” in red color appears under the field if the field is empty after submitting the form.

5.    The “Client Price” field is required and is marked with a red asterisk. Border is highlighted when the cursor placed on border or the field. The field is pre-filled automatically after choosing the Service in the “Service” field. The field accept only numbers (0-9), point (.), and comma(,). Entering other characters into the field causes the appearance of an error message “Allowed only numbers and .,” in red color under the field. When user deletes data from the field, an error message “Required” in red color appears under the field. An error message “Required” in red color appears under the field if the field is empty after submitting the form.

6.    The "Client Paid" field is required and is marked with a red asterisk. Border is highlighted when the cursor placed on border or the field. "Client Price" field is pre-filled automatically after choosing the Service in the Service field. The field accept only numbers (0-9), point (.), and comma(,). Entering other characters into the field causes the appearance of an error message “Allowed only numbers and .,” in red color under the field. When user deletes data from the field, an error message “Required” in red color appears under the field. An error message “Required” in red color appears under the field if the field is empty after submitting the form.

7.    The “Vendor Price” field is required and is marked with a red asterisk. Border is highlighted when the cursor placed on border or the field. "Vendor Price" field is pre-filled automatically after choosing the Service in the Service field. The field accept only numbers (0-9), point (.), and comma(,). Entering other characters into the field causes the appearance of an error message “Allowed only numbers and .,” in red color under the field. When user deletes data from the field, an error message “Required” in red color appears under the field. An error message “Required” in red color appears under the field if the field is empty after submitting the form.

8.    The “Vendor Paid” field is required and is marked with a red asterisk. Border is highlighted when the cursor placed on border or the field. The field accept only numbers (0-9), point (.), and comma(,). Entering other characters into the field causes the appearance of an error message “Allowed only numbers and .,” in red color under the field. When user deletes data from the field, an error message “Required” in red color appears under the field. An error message “Required” in red color appears under the field if the field is empty after submitting the form.

9.    The "Client Paid" and the "Vendor Paid" fields accept:
1.  Numbers (0-9) and point (“.”), and comma(“,”) only.
2.  Min. 1 and max. 10 digits in number.
3.  Decimal part should contains 2 (two) digits.

Floating point for currency value. User should key in the currency value with a decimal point. Use the point (“.”), and comma(“,”) to represent the difference between whole numbers and partial numbers.

If the user entering other characters, the message “Only numbers, point (“.”), and comma(“,”) are allowed” in red color appears under the field.

10. The “Description” field is not required. field is not required.
    The form can be submitted with an empty field. The field accepts only Upper and Lower Latin letters, spaces, emoji, digits, and special characters (!@#$%^&*()_+_+{}[]:"|;'\<>?,./±§=). Max (chars)  = ∞.

11. The “Create” button is active all the time.
    If a User tries to create an Order when at least one required field is empty, clicking the “Create” button does not result in creating a new Order, does not show the new Order in the dashboard and does not close the Modal window. A message "Required" appears under the empty fields.

After clicking the “Create” button information about created Order appears in the Orders dashboard with corresponding data.
