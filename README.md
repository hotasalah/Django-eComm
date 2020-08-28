# Django-eComm
fully functional eCommerece website with user and guest checkout capabilities.



#### An online store for Classical Music Instruments.

This project is a fully functioning eCommerce website from start to checkout functionality. Users have the ability to add multiple products to cart, varying from instructions and their outfit.


Once a user creates an account, will automatically be added as a customer and will be treated as an authenticated user.
This process was handled and programmed using the Django Signals feature.


## User/Guest Checkout

The main focus of this eCommerce project is to integrate guest checkout ability along with user accounts. This kind of functionality has come to be expected by users and forcing them to create an account can affect sales significantly as any resistance does.


## Authenticated User Vs Guest Checkout

Authenticated users & guests have virtually the same process with slight differences. Users with accounts will have the ability to view pending and previous orders while guests will have items stored in cookies and will have the option to create account after a successful purchase.

Authenticated User Process:

Add item to cart
Edit Order
Checkout
View pending and previous orders + Order details 
Guest Checkout Process

Guest Checkout Process:

Add item to cart
Edit Order
Checkout
Create Account to view Order 


## Items stored in Cookies

Guest Checkout is handled by sending temporary cookies to the client's web browser, consisting of the order details, to be able to proceed in the checkout process.
