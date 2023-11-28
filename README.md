# SQL Filtering Queries

# Description
 - In this project, I will obtain specific information about employees, their machines, and the departments they belong to from a database. I will demonstrate how I would use the AND, OR, and NOT operators to create more complex filters for SQL queries.
   
# Enviornments & Utilities Used
 - mySQL
 - MariaDB Shell

# Walkthrough
<p align="center">
<b></b>Retrieving log-in attempts made after hours: My query syntax would be as followed.
 <br/>
 " SELECT * FROM log_in_attempts WHERE login_time > AND success = 0; " 
  <br/>
 <br/>
  <img src="https://i.imgur.com/HAK3CKe.png" height="50%" width="50%"
<br/>
  <br />
  <br/>
  Step 2:
  <br /> 
  I want to create a new user named Alex. To do that, I will click on the example (local) entry. This is the entry for the domain that my account is managing. I will scroll down and double click on the "Users" entry to see the list of users and groups that currently exist. <br/>
  <img src="https://i.imgur.com/nEsuanm.png" height="90%" width="90%"
<br />
<br />
<br/>
Step 3: Adding the New User
<br/>
To create a new user, I will use the tasks list on the right. Under the "Users" section, there's a "New" menu entry, which opens a submenu to select what's the type of entity that you want to create. In this case, I want to create a new user, so I'll click on the User option.
  <img src="https://i.imgur.com/FMGVs8f.png" height="115%" width="115%"
  <br/>
  <br />
<br/>
Step 4:
<br/>
This will open a new window that lets you fill in a number of fields related to the new user. There are a lot of fields available, but only a couple are mandatory (indicated with the red star). For now, I can leave the rest empty. The user that we are creating is named Alex, with their username being also alex. <br/>
  <img src="https://i.imgur.com/i7OcAzO.jpg" height="80%" width="80%"
  <br/>
  <br />
<br/>
Step 5:
<br/>
The system will not enable an account that doesn't have a good password. In this case, the password is empty because we haven't set it. Obviously, an empty password is not a good password. I can set a password using the Reset password menu option. <br/>
  <img src="https://i.imgur.com/J4G6BBd.png" height="20%" width="20%"
  <br/>
  <br />
<br/>
Step 6:
<br/>
Enter a password and confirm the password into the Reset Password window. I will make sure that the "User must change password at next logon" option is already checked, this will ensure that the user will change their password when they log in. So now I'll click on the OK button to set the password. The goal of this is that after they've logged in once, I will not know their new password. <br/>
<img src="https://i.imgur.com/QngjwQ8.png" height="100%" width="100%"
  <br/>
  <br/>
 <br/> In Conclusion:
 <br/>
  That's it! I have just created Alex as a user using the Active Directory tool. From there I could add Alex to a "Group" coinciding with the department Alex belongs to or is currently working with inside of our organization.
