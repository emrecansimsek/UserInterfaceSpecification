# User Interface Specification

**This document has been written to explain the details and functions of the user interface design in the image below.**

![](https://lists.office.com/Images/969df1bb-97b6-44ef-9108-dc18a5fd96c2/298428f6-6729-4501-a9de-dcaf554877fe/T4JRHA4Y8E2E91ER9XU0TNKHPD/c2f1cb7e-5022-433a-93a2-1ac0b6ec1015)
#1.Default Page
When user opens the page, it should only show the Navbar and table as a default. New User input area shouldn't be shown at the beginning. If user wants to open that component, he/she should click the "New User" button.

#2.Navbar
Navbar is for controlling the page. It has three main components: A,B,C.

![](https://i.ibb.co/tQBsYy6/1Navbar.jpg)

<span style="color:red">A</span>:User can open the "New User" component by clicking the button to add new user to the system. If it is already been opened before, clicking that button will hide that component. Only table will be shown on the screen.
<span style="color:red">B</span>:It is a checkbox which is checked as default. By checking this box; user will not be able to see user details in the table below.
<span style="color:red">C</span>:Save button for adding new user. The button should not become active until all the information in the new user field is filled in. After all information is entered, the new user information is saved in the table by pressing the button. 

#3. User Table
User table is the table which user can see the details of all users.After the user enters the new user information and clicks the "Save Button(2.C)", the information is reflected in the table.Table has four main components: A,B,C,D
![](https://i.ibb.co/jfTQBQ5/23.jpg)

<span style="color:red">A</span>:ID column is for User ID's which is automatically created has been added to the table. It also has a button for sorting the list according to ID.
<span style="color:red">B</span>:User Name column is for User Names which has been added to the table. It also has a button for sorting the list according to User Name.
<span style="color:red">C</span>:Email column is for emails which has been added to the table. It also has a button for sorting the list according to email.
<span style="color:red">D</span>:Enabled column is for true or false condition which has been added to the table. It also has a button for sorting the list according to true or false value.


#4. New User

New user is a input area which includes all the neccessary inputs for adding the new user to the table. After clicking the "New User Button (2.A)" in the Navbar, it opens. Without filling all the input areas except "G:Enabled Checkbox", "Save Button(2.C)" does not become active.

![](https://i.ibb.co/s3QW1Xr/3.jpg)

<span style="color:red">A</span>:Header titled "New User".
<span style="color:red">B</span>:Username input area for new user. It should warn the user if that username has already been added and not accept it.
<span style="color:red">C</span>:Name input area for new user and not accept it.
<span style="color:red">D</span>:Phone input area for new user. It should warn the user if that phone has already been added and not accept it.
<span style="color:red">E</span>:Email input area for new user. It should warn the user if that email has already been added and not accept it.
<span style="color:red">F</span>:User role multiple select input area. It should include three roles:
1. Guest
2. Admin
3. SuperAdmin

The user must select one of these roles.

<span style="color:red">G</span>:Enabled checkbox. It is not compulsory to check the box to save user.

#5.UI CSS Design
All the detailed information about the CSS design for the screen above is explained below. Desginer should follow referrals and everything should be same as the screen that shown in the beginning of the document.
##5.2 Navbar
**5.2.1 New User Button** 
"New User" button in the navbar (2.A) should have include the "+" sign in it and the button color should be blue.
**5.2.2 Checkbox** 
Enabled checkbox should be placed next to "New User Button". If it's clicked, the color should be blue.
**5.2.3 Save Button** 
Save button should be shown as light blue when it's disabled and it should be placed right side of the Navbar.

##5.3 User Table

**5.3.1 Table**
First row of the table background should be blue and the font color should be white. After that row, the row background colors that come after should be white and light blue, so that the same color is not used consecutively. Font color should be black. In this way, the ease of distinguishing the rows should be provided for the user.

##5.4 New User
**5.4.1 Header**
There should be a header area titled "New User" with a light grey background.
**5.4.2 Input Areas**
Input areas should be listed towards to bottom. In input areas there should not be placeholders except "User Roles(4.F)". "User Roles(4.F)" input area should have "Select user roles..." placeholder. Background should be white and the font color should be black.


