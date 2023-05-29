/*
Read Me File 
Version of Visual Studio used: 2022
Dario Di Leva
ST10081733
*/

/*
Employee user will be referred to as "user" for this readme
Chatgpt was used for part of the project I didn't understand 

*/

When opening my visual studio project, click on open a project or solution tab and find the sln file that is within my file. 

The user will need to do this inorder for the database to appear

/*
How the Program works
*/

Login Default Page:

When opening the application click on the default page and run.
There will be 2 options: Login for Farmer and Login for Employee. 
The user clicks on the button under Employee Login and will be prompted to fill in the Login details:

Username:
Emp01

Password:
Password1

Employee Board:

After login, the user will be directed to the employee board page. 
If there is nothing that displays, the user clicks on add farmer to go register a farmer on the farmer register page

-----------------------------------
Farmer Registration Page:

On this page the user will enter the Farmer Username, Farmer Email, Farmer Name, Farmer Surname, Farmer Phone Number, Farmer Password and Confirm Password. 

After the user has filled in all these fields,  click add farmer button to send the farmers details to the database and will get prompted with a message box saying that farmer has been created.

I added an exception where all fields need to be completed, otherwise the user will receive an error message to make sure all the fields are filled. An additional exception is that the phone number has to be 10 characters. In addition the Password and Confirm Password needs to be the same, otherwise the user receives an error message prompting the user to ensure both passwords are the same. 

When the user is done, they will then click on the Back to Employee Board button.
Once the farmer has been created successfully, the user will click on the logout button to go back to the home page

-----------------------------------
Farmer Board:

The created farmer can now access the application via the Farmer Board. The farmer enters his username and password and clicks on the login button and will prompt a messagebox. 

The farmer will enter the Farmer Board where his product details can be captured. 

The farmer will enter Product Code, Product Type, Product Name and the date that the product was entered, when the farmer enters all this information they will then click enter. A prompt will be received, confirming that the information has been sent to the database.

The farmer will then click the log out button to go back to the home page.


-----------------------------------

When the user logs back into their employee board they can select the farmer and select the product type filter and click the display Products button to view the list of products 

Once complete the user will log out
-----------------------------------


