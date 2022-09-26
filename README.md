# CarRentalDjangoProject

The Online Car Rental System project in Django has two modules One for car dealers, one for clients, . Models, URLS, and views are handled by each app in the usual Django way. 
Anyway, Customer logs into the customer portal, specifies the area in which he wants the car, and the system searches all available car-dealers and their vehicles in that area, displaying the results to the customer. If the car has already been rented.

Also, I have used the local MYSQL database, and the python classes in `models.py` assisted in database management and upgrading. The database configuration can be found in ocrs/ocrs/`settings.py`, where you can add your own database, username, and password in the DATABASE section.

## Steps to execute the project

1. Open MYSQL workbench and execute the following commands: ```cmd DROP DATABASE IF EXISTS `ocrsdjango`; CREATE DATABASE `ocrsdjango`; USE `ocrsdjango`; ``` And a new database will be created.
2. First we’d need to install the pre-requisite modules by opening the command prompt / terminal, Go inside the project folder and then type the following command: ``` pip install -r requirements.txt ```
3. Type the following command to run the webserver: ``` python manage.py runserver ```
4. Finally, open the browser and go to `http://127.0.0.1:8000/`

## Module Description:
**Admin Features of Online Car Rental system in Django**
* *Sign up –* The admin needs to sign up first to create an account.
* *Login –* After creating an account, The admin need to login first to enable to access the system.
* *Manage Order –* For the order, The admin can view order of the customer.
* *Sales Management –* The admin can view the daily sales.
* *Manage Vehicle –* The admin can add, update, and delete vehicle information.
* *Homepage –* In the homepage you can see the orders, sales, home, and vehicles.

**User Features of Online Car Rental system in Django**
* *Sign up –* The user needs to sign up first to create an account.
* *Login –* After creating an account, The user need to login first to enable to access the system.
* *Search Car–* For the search car, The user will search a car to rent.
* *Rent Car –* The user can update, delete orders and view the car details.

