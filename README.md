# SQL Filtering Queries

# Description
 - In this project, I will obtain specific information about employees, their machines, and the departments they belong to from a database. I will demonstrate how I would use the AND, OR, and NOT operators to create more complex filters for SQL queries.
   
# Enviornments & Utilities Used
 - mySQL
 - MariaDB Shell

# Walkthrough
<p align="center">
<b></b> 1). Retrieving login attempts made after hours: <br/>
 This query will show me all the login attempts made after business hours.
 <br/> My query syntax would be as such. 
 <br/>
 <br/>
 " SELECT * FROM log_in_attempts WHERE login_time > 18:00:00 AND success = 0; " 
  <br/>
  <img src="https://i.imgur.com/HAK3CKe.png" height="50%" width="50%"
<br/>
  <br />
  <br/>
  2). Retrieving login attempts on specific dates:
  <br /> 
  <img src="https://i.imgur.com/3SrTnol.png" height="50%" width="50%"
   <br />
<br />
<br/>
3). Retrieving login attempts outside of Mexico using the "WHERE NOT" and "LIKE" operators.
 <br/>
  <img src="https://i.imgur.com/b8babV0.png" height="50%" width="50%"
  <br/>
  <br />
<br/>
4). Retrieving employees in Marketing, Sales, and Finance that work in the "East Buildings" <br/>
  <img src="https://i.imgur.com/AvFVPHX.png" height="50%" width="50%"
  <br/>
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
