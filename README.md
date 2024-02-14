# NNCoffeeOperationalDatabase
SQL Database created based off mock company "Night Night Coffee"

NightNight Coffee DB Requirement Set:
NightNight Coffee sells coffee/tea/chais and other cafe-related drinks in a 24-hour cafe to customers, as well as selling their own roasted coffee to other businesses in the Philadelphia area. NightNight Coffee Company Sales Management Database will keep track of Customers, Sales, Buildings, Staff Members, Drinks, and Daily Coffee Production.
For each customer, the database will keep track of a unique Customer ID, Number of Sales, First Name, Last Name, and Email Address.
For each sale, the database will keep track of a unique Sale ID, Customer ID, Sale Type (In-Store, B2B, or Digital), Drink ID, and Sale Total.
Each sale must have at least 1 Drink ID
For each building, the database will keep track of a unique Building ID, Building Type, Zip Code and Number of Staff Members.
For each staff member, the database will keep track of a unique Staff ID, Staff Type (In-Store, Production, Managerial, and Digital), and the Staff Name composed of the staff’s first name and last name.
For each drink, the database will keep track of a unique Drink ID, Drink Name, Drink price, and Number of Drinks sold.
For daily coffee production, the database will keep track of a unique Production Number, Date, Weight, Proportion of Robusta Beans, and Proportion of Arabica Beans.
Each customer makes one or more sales. Each sale is made by exactly one customer.
Each sale must sell one or more drinks. Each drink is sold in one or more sales, but does not have to be sold.
Each staff member must work in exactly one building. Each building must hold one or more staff members. 
Each sale is held in exactly one building. Each building holds multiple sales.
Each daily coffee production number does not have to have the same weight or proportion, but it can have the same date
A staff member can be a customer, but does not have to be one.
Each building can store one or more coffee production records, but does not have to. Each coffee production record must be stored in one or more buildings.
