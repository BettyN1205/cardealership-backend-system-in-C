# cardealership-backend-system-in-C

======================== BN Inventory Management Headquarters ========================
Implemented a vehicle inventory management system, including: 
1. Total inventory and branch inventory management (CRUD);
2. Total inventory allocation to branch inventory;
3. Inventory transfer between branch inventories;
4. A simple Branches to Customer Sale System
5. A simple Search Engine


        

=========================================================================================
The original requirements are as follows:

In this project, you are working on the back end of a famous car dealership website.

The name of the dealership you are working with is your first name and your last name.

Your dealership has 5 different branches in 5 different cities in North America including Canada, USA, and Mexico. Therefore, the offers and prices are in three different currencies.

In case, you need to implement a conversion rate, you can implement a fixed rate; however, implementing a variable rate would be an advantage and you will receive extra points.

As an example, the rate to convert the USD to CAD can be assumed as a fixed rate of 1.3; though in reality, this rate could change from 1.2 to 1.4 on daily basis.

The same as the previous project you have gone through, you need to deal with an inventory.

In this project, each of the branches holds a minimum of 5 cars and a maximum of 10 cars.

The dealership works with the following brands which are divided into three different categories:

Group 1:

- Kia

- Toyota

- Honda

- Mazda

- Nissan



Group 2:

- Ford

- Genesis

- Volvo

- Acura



Group 3:

- BMW

- Audi

- Bentley

- Ferrari

- Aston Martin

- Bugatti



Each car you define MUST have two different trims.



The features and specifications you need to define for the cars are listed below:

- Model

- Manufacturer

- Color (upgradable)

- Mileage

- Manual/Automatic Transmission (upgradable)

- Engine (Engine struct)

- Chassis (Chassis struct)

- Exterior (Exterior struct)

- Seating & Trim (Seating & Trim struct)

- Dimensions (Dimensions struct)

- Airbags (Yes/No)

- number of the Airbags

- Fuel Economy (Fues Struct)

- Hybrid (Yes/No)

- Fully Electrified (Yes/No)

- Automatic Parking Assistance (Yes/No - Upgradable)

- Night Vision Assistance (Yes/No)

- Cruise Control (Yes/No - Upgradable)

- 2WD/4WD

- Hill assist

- Tire Pressure Monitoring System (Yes/No - Upgradable)

- Voice Command

- Lane Change Indicator

- Forward Collision Warning Sensor

- Blind spot warning sensors

- Seat heater (numbers)

- Steering heater (Yes/No)





Each branch has the following public information :

- Address

- Postal Code

- Phone number

- Fax Number

- Customer Service Email

- Name of the General Manager



Each branch has the following confidential information:

- General Manager’s phone number

- General Manager’s cell phone number

- General Manager’s address

- General Manager’s Email

- General Manager’s date of employment

- General Manager’s years of experience

- Finance Manager’s first name and last name

- Finance Manager’s phone number

- Finance Manager’s cell phone number

- Finance Manager’s address

- Finance Manager’s date of employment

- Finance Manager’s years of experience

- Number of the available cars

- Complete Information about the available cars

There are four different stories that your code must represent:

1. One of the branches of the dealership sells a car (The inventory must be updated)

2. One of the branches of the dealership buys a car (The inventory must be updated)

3. One of the branches of the dealership transfers a car from one branch to the other (the transfer expenses and the currency rate must be taken into consideration.)

4. The dealership supplies brand-new cars to the different branches


- All brand-new Honda in Canada has a 2% rebate as a credit.

- All brand-new Volvo above 60,000 in Mexico have a 3% rebate as credit.

- In the USA, there is a loyalty program for BMW, VOLVO, AUDI, BENTLEY, and Ferrari - If the customer is eligible for the loyalty program then a 2.5% promotion will be implemented to their purchase (not a rebate).


Your website has a search engine based on your available inventories of all the branches and the following inputs could be inserted from the user as the search criteria:

1. Car Model

2. Car Manufacturer

3. Brand-new / Used / Both

4. Range of mileage 

5. Price range

6. Color

7. Availability in the country (In this case, you initially need to determine the location)
