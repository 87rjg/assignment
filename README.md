# assignment


An Android application for the merchants - Which captures/shows the business and product details
with login/authentication functionality:

1. Login Screen: This screen should get the username and password from the user, connect to
the server for authentication and shows the appropriate message.

 used Firebase for authentication and pre-define the credentials for sample users.

2. Home Screen: This is the landing page for the App which has two tabs, one for the merchant
profile and other with the list of all products listed by the merchant.

3. Business Profile Screen: This will display the merchant business details, which are (These
details can be hard coded):
• Business Name
• Description
• Ratings
• Address.
• City from the list of cities
• Picture of business

4. Product: This screen has following items:
• Product List Screen: This screen will list all the products listed by the merchant. By
default, initially the list will be empty, there should an Add product button to take
user on Add Product Screen. Tapping on the Product list item should take the user
on View Product screen.

• View Product Screen: This screen should display the individual product details
along with the product photos. It should also contain an Edit Product option.

• Edit Product Screen: This screen allows merchant to add the details of the new
product or edit the details of the existing product.

The product should contain the following data elements:
• Product Id.
• Name
• Description
• One or more pictures (Images can be hosted on firebase or any server)
• Product specification: This should be dictionary having key value pairs of string with
specification name and its value(s).

• Current Stock Quantity
• Product MRP
• Product Selling Price
