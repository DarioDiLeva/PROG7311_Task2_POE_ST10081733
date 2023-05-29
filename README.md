# PROG7311_Task2_POE_ST10081733

/*
Read Me File 
Version of visual Studio used: 2022
Dario Di Leva
ST10081733
*/

/*
Employee user will be said as "user"
Chatgpt was used for part of the project I didnt understand 

*/

When opening my visual studio project, click on open a project or solution tab and find the sln file that is within my file. 

Need to do this otherwise the database won't appear

/*
How the Program works
*/
Login Default Page:

When opening the application it will send you to the default page, there will be 2 options: Login for Farmer and Login for Employee. What the user should do first is to press the button under Employee Login with these Login details:

Username:
Emp01

Password:
Password1

Employee Board:

After login in it will send you to the employee board page in this page you can select which farmer in the dropdownlistto see what products fall under the username, the second dropdownlist is a filter between Fruits, Vegetables, Meat and All that you can use to filter out the farmer that enter those specific products. When you click display products it will show you the products that you have selected. 

If there is nothing that displays to the user a error message will appear telling the user to add a farmer, click on add farmer to go to farmer register page, if a farmer as been entered they click logout to go to the home page.

Farmer Registration Page:

In this page the user will enter the Farmer Username, Farmer Email, Farmer Name, Farmer Surname, Farmer Phone Number, Farmer Password and Confirm Password. 

When the user fill in all these fields they then click add farmer to send the farmers details to the database and will be prompted with a message box saying that farmer has been entered.

I added an exception where all fields needs to be enter otherwise it sends an error message to the user to make sure all the fields are filled, another exception where phone number has to be 10 characters and Password and Confirm Password needs to be the same otherwise it sends an error telling the user to makes sure the passwords are the same. 

When the user is done they will then click on the Back to Employee Board button.


Farmer Board:

When the user has entered the Farmer's Username and Password, it will sent them to the farmer board where they will enter, The Product Code, Product Type, Product Name and the date that the data was entered, when the user enters all this information they will then click enter and receive a prompt telling that the information has been sent to the database.

The user will then click the log out button to go back to the home page.

-----------------------------------

When the user has entered the farmer's detail and the farmer as entered the products, the user will then log back into the employee login and enter the employee board which is where the user will enter all the respected data and click display products product to see the products made by the farmer. 

-----------------------------------
