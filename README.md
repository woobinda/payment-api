# Interaction with e-commerce web Api on Flask framework.

The interaction with the customer online store and payment web API service.
Contains form for ordering in store, and providing a redirect customers to the page of payment service.
Service redirect url depending on the currency (RUB or UAH) of payment.

To install all dependencies you can use the console command for Makefile with already installed pip package manager:

$make install

To run application with gunicorn web server you can use the console command for Makefile:

$make start
