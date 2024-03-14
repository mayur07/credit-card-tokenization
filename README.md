# Payment-Profile-Tokenizer 

This is just aPOC version of the JS library to tokenize credit cards
library used https://stripe.com/en-gb-pl/payments/elements

You will need some backend that will receive full credit card data and do the tokenization in your selected gateway
and in the end, return you the token.

## Usage

Run those commands in the console:

```
npm install
npm start
```

This should open a new tab in your browser (if not you can manually go to http://localhost:4000)

This example uses a fake backend that simulates something that you would normally have in a production environment.

It supports two scenarios:
- use credit card number 4242 4242 4242 4242 to obtain the token from the backend (you will see it in the browser console)

- use credit card number 4111 1111 1111 1111 to simulate an error from the backend (you will see it in the browser console)

