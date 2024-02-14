NightNight Coffee Operational Database
This SQL Database is created to manage operations for the mock company "Night Night Coffee," which operates a 24-hour cafe in Philadelphia. In addition to serving customers in their cafe, NightNight Coffee also sells their own roasted coffee to other businesses in the area.

Requirements
NightNight Coffee's operational database must keep track of the following entities:

Customers
Sales
Buildings
Staff Members
Drinks
Daily Coffee Production
Entity Details

Customers

Each customer is identified by a unique Customer ID.
Attributes stored for each customer include Number of Sales, First Name, Last Name, and Email Address.

Sales

Each sale is identified by a unique Sale ID.
Attributes include Customer ID, Sale Type (In-Store, B2B, or Digital), Drink ID, and Sale Total.
Every sale must include at least one Drink ID.

Buildings

Each building is identified by a unique Building ID.
Attributes include Building Type, Zip Code, and Number of Staff Members.


Staff Members
Each staff member is identified by a unique Staff ID.
Staff Type can be In-Store, Production, Managerial, or Digital.
Attributes include Staff Name (composed of first name and last name).


Drinks
Each drink is identified by a unique Drink ID.
Attributes include Drink Name, Drink Price, and Number of Drinks Sold.


Daily Coffee Production
Each production record is identified by a unique Production Number.
Attributes include Date, Weight, Proportion of Robusta Beans, and Proportion of Arabica Beans.
Multiple production records can be stored for the same date.


Relationships
Each customer can make one or more sales, and each sale is made by exactly one customer.
Each sale must include one or more drinks, and each drink can be sold in one or more sales.
Each staff member works in exactly one building, and each building holds one or more staff members.
Each sale is held in exactly one building, and each building holds multiple sales.
Each building can store one or more coffee production records, and each coffee production record must be stored in one or more buildings.


Notes
Staff members can also be customers but are not required to be.
Buildings can store multiple coffee production records, but it's not mandatory for each building to do so.
