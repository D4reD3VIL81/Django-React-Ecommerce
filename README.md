# Ecommerce Website With Django + React
An ecommerce website using Django (Back-end), React (Front-end), DjangoRestFramework and PostgreSQL (Database). 

## Features
- Full featured shopping cart
- Product reviews and ratings
- Top products carousel
- Product pagination
- Product search feature
- User profile with orders
- Admin product management
- Admin user management
- Admin Order details page
- Mark orders as delivered option
- Checkout process (shipping, payment method, etc)
- PayPal / credit card integration

https://user-images.githubusercontent.com/26794816/199917658-bde2dc3f-60dc-4f61-98eb-7fd8bd89330b.mov

## Setup and Instructions
To get this project up and running you should start by having Python installed on your computer. It's advised you create a virtual environment to store your projects dependencies separately. You can install virtualenv with
```shell
pip install virtualenv
```
Clone or download this repository and open it in your editor of choice. In a terminal (mac/linux) or windows terminal, run the following command in the base directory of this project
```shell
virtualenv env
```
That will create a new folder `env` in your project directory. Next activate it with this command on mac/linux:
```shell
source env/bin/active
```
Then install the project dependencies with
```shell
pip install -r requirements.txt
```
Now you can run the project with this command
```shell
python manage.py runserver
```
After django you should install `yarn` or `npm` and start the project in `ecommerce/frontend` folder and use:
```shell
npm start
```
Now you can use the project on http://localhost:3000/.

Enjoy :)
