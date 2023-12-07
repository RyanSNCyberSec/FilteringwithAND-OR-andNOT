<h1>Filtering with AND, OR, and NOT as well as some completed Joins in SQL </h1>

 

<h2>Description</h2>
In this scenario, I used the AND, OR, and NOT operators in SQL to filter for information. This was done to get specific information about employees, their machines, and the departments they’re in. Additionally, I use INNER JOIN and RIGHT JOIN to retrieve information from two different tables, from separate machines, employees, and login attempts tables. This was done to investigate a recent security incident that compromised some machines.
<br /> .


<h2>Languages and Utilities Used</h2>

- <b>MariaDB shell</b>
- <b>SQL</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Program Walk-through:</h2>

<p align="center">
Retrieving after-hours failed login attempts: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/SQL%20filtering%20query%20NOT%20OR%201.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Retrieving login attempts on specific dates: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/SQL%20filtering%20query%20NOT%20OR%202.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Retrieving login attempts outside of Mexico: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/SQL%20filtering%20query%20NOT%20OR%203.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Retrieving employees in Marketing: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/SQL%20filtering%20query%20NOT%20OR%204.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Retrieving employees in Finance or Sales: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/SQL%20filtering%20query%20NOT%20OR%205.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Retrieving all employees not in IT: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/SQL%20filtering%20query%20NOT%20OR%206.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2>Additional Completed Joins</h2>

<p align="center">
Matching employees to their machines: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/SQL%20Inner%20Join%201.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Returning more data with a RIGHT JOIN: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/SQL%20Right%20Join%20-%20Outer%20Join.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Retrieving the login attempt data with an INNER JOIN: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/SQL%20Inner%20Join.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
