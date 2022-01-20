# Banking Record System

Customer Billing System Project generates an application which can be used in any departmental store, shops, cafes etc. for billing to the customer.

You can use this application to keep the records such as name, address, mobile number, paid amount, due amount, payment date etc. of your regular costumer. Moreover, if you have a new customer, you can add and edit the account at any time.

## Abstract:
File handling has been effectively used for each feature of this project. Here, I am going to describe these features in brief.

* Add Record: 

For this feature void read_data() function has been used to add banking record into the file. It asks for information such as account number, first name, last name and balance to be entered.


* Show/List Data:


With the information provided in add record, the void show_data() function in this banking record system project in C++ show the record corresponding to a particular account number, first name and last name. Current balance of the account holder is displayed.


* Search Record:


When the function for this feature is first executed, it shows the total records in the file, and the user can then search by record number. If the record searched for is not found, the banking record system project in C++ displays the message – “Error in opening! File Not Found!!”


* Edit Record:


This works in similar manner to the Search feature. When the function for Edit Record is first executed, it shows the total records in the file, and the user can edit the information by providing record number. Then, the C++ project shows all the data in that record, and the user can enter any data to modify. If the record to be edited for is not found, it displays the message – “Error in opening! File Not Found!!”


* Delete Record:


First of all, when the function of this feature is executed, it shows all the records in the file, and the user can enter the record number to delete. If the record was not found, this banking record system project in C++ displays the message – “Error in opening! File Not Found!!”


## User Defined Functions Used:

Although graphics has not been used in this project, the application of user defined functions and structures have been effectively used here. The major user defined functions used in this C project are:

* void input()
* void writefile()
* void search()
* void output()

The function void input() is used to add the new customer account i.e. with the help of this functions the parameters such as name, address, phone number, amount paid etc. are asked and entered. Another function void writefile() has been utilized to create a file on hard disc of computer for storing the information and data of a customer.

The function void search() has been used to look for previously stored accounts either by name or by number of the customer. The fourth and the last user defined function used in this Customer Billing System Project in C is void output() which has been defined to show the result as console output.

## Structure:
In Customer Billing System, structure has very beautifully used to group the data type in single unit. The date variables (day, month and year) have been grouped in the structures named date where as other variables such as name, number, street, paid amount etc. are grouped under another structure named account.

Customer Billing System application is so simple to use. In order to use the application, click at the exe file and then, you will have three options to:

* To add account
* To search account
* To exit
As per your need, enter 1, 2,or 3 and follow the instructions provided by the application itself.

## Features:

* It can hold any number of accounts and account can be added to the program at any time.
* The programming of simple calculations such as calculation of due amount, balance etc. have been embed in the code of project.
* The Customer Billing System project in C gives you the facility of searching the account by two ways, either by name of the customer or by the number of customer.
* The due amount to be paid is shown as negative balance.


If you have nothing to do with the program, you can directly exit from the main menu.

## Output Screens:

Main Menu


![image](https://user-images.githubusercontent.com/73773202/150315024-6b9c1dcd-6b45-4524-9ee2-e9484dfff4f8.png)


Customer Accounts

![image](https://user-images.githubusercontent.com/73773202/150315050-843f5216-734e-4abb-ae3b-7eb4dcc54a28.png)


---
