# Payment-Gateway-Integration-

This is a sample code for creating a native payment integration for Ecwid. 

It has the following features: 

- automated read/save of user's settings
- up-to-date elements for user interface
- basic initialization and interaction with Ecwid JS SDK

## Files' descriptions

- `payment-request.php` – payment URL for the integration. Customers will be directed to that URL at the checkout to make the payment for order. It will also be used to update order status when callback is received from payment

- `index.html`, `functions.js`, `CssFw.css` – files for merchant settings in Ecwid Control Panel

