# Apply-Filters-to-SQL-Queries

- In this Project i will investigate all potential security issues and update employee computers as needed. The following provide examples of how I used SQL with filters to perform security-related tasks.

<p align="center">
Retrieve after hours failed login attempts: <br/>

- In this project there were failed login attempts that were made after business hours. I will retrieving this information from the login activity. I will identify all unsuccessful attempts after 18:00.
- The login_time column in the log_in_attempts table contains information on when login attempts were made. Office hours end at '18:00'.
- The success column in the log_in_attempts table contains values of TRUE or FALSE to indicate whether the login was successful. 

<p align="center">
<img src="https://i.imgur.com/mgOiXR9.png" height="80%" width="80%" alt="Apply-Filters-to-SQL-Queries"/>
<img src="https://i.imgur.com/oxlM68m.png" height="80%" width="80%" alt="Apply-Filters-to-SQL-Queries"/>
<br />

- The output shows there are 19 failed login attempts. Coming from contries such as Mexico, USA, and Canada

<p align="center">
Retrieve login attempts on specific dates: <br/>

- In this project there have suspicious event that occurred on '2022-05-09'. I will retrieve all login attempts that occurred on this day and the day before ('2022-05-08').
- The login_date column in the log_in_attempts table contains information on the dates when login attempts were made.

<p align="center">
<img src="https://i.imgur.com/ass0fcT.png" height="80%" width="80%" alt="File-Permissions-in-Linux"/>

- As you can see in the screenshot there were a lot of login attempts on both days. In total there were 75 attempts. 

<p align="center">
Retrieve login attempts outside of Mexico: <br/>

-Now I investigating logins that did not originate in Mexico.

<p align="center">
<img src="https://i.imgur.com/jcCp8TS.png" height="80%" width="80%" alt="File-Permissions-in-Linux"/>

- As you can see in the screenshot there were a lot of login attempts that were not from Mexico. In total there were 144 attempts. 

<p align="center">
Retrieve employees in Marketing: <br/>

- In this part of the Project we will be updating employee machines we will obtain the information about employees in the 'Marketing' department who are located in all offices in the East building (such as 'East-170' or 'East-320').

<p align="center">
<img src="https://i.imgur.com/4RZDxKa.png" height="80%" width="80%" alt="File-Permissions-in-Linux"/>

- As you can see in the screenshot there are 7 employees that work in the Marketing Dapartment and are in the East building.

<p align="center">
Retrieve employees in Finance or Sales: <br/>

- Now we need to find the employees from Finance or the Sales department and we need to locate information on these employees.

<p align="center">
<img src="https://i.imgur.com/e1TMwVY.png" height="80%" width="80%" alt="File-Permissions-in-Linux"/>


- <p align="center">
Retrieve all employees not in IT: <br/>

- Now we need to find the all employees that are not from 'Information Technology'

<p align="center">
<img src="https://i.imgur.com/yX7dhwa.png" height="80%" width="80%" alt="File-Permissions-in-Linux"/>

- As you can see in the screenshot the output shows the all of the employees that are not in 'Information Technology'




