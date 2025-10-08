# Ex03 Time Table
## Date:08/10/2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="C:\Users\admin\OneDrive\Pictures\Screenshots\Screenshot 2025-09-24 101757.png" height="100" width="500">
</center>
<br>
<table align="center" width="500" cellspacing="3" cellpadding="2" border="2" bgcolor="yellow">
<caption><b>SLOT TIME TABLE - JAISREE B (212224230100)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
<th bgcolor="yellow">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td bgcolor="cyan">UI and UX Design</td>
<td bgcolor="cyan">FREE SLOT</td>
<td bgcolor="cyan">FREE SLOT</td>
<td bgcolor="cyan">FREE SLOT</td>
<td bgcolor="cyan">FREE SLOT</td>
<td bgcolor="cyan">FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td bgcolor="cyan">Computer Architecture</td>
<td bgcolor="cyan">Introduction to Machine Learning</td>
<td bgcolor="cyan"> Fundamentals of Web Application Development</td>
<td bgcolor="cyan">FREE SLOT</td>
<td bgcolor="cyan">Computer Architecture</td>
<td bgcolor="cyan">FREE SLOT</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="6" align="center" bgcolor="cyan">L U N C H    B R E A K </td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td bgcolor="cyan">Fundamentals of Web Application Development</td>
<td bgcolor="cyan">Time Series Analysis and Forecasting</td>
<td bgcolor="cyan">Mentor Meet</td>
<td bgcolor="cyan">UI and UX Design</td>
<td bgcolor="cyan">FREE SLOT</td>
<td bgcolor="cyan">FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td bgcolor="cyan">Time Series Analysis and Forecasting</td>
<td bgcolor="cyan">FREE SLOT</td>
<td bgcolor="cyan">Introduction to Machine Learning</td>
<td bgcolor="cyan">Database Management System and its Applications</td>
<td bgcolor="cyan">Database Management System and its Applications</td>
<td bgcolor="cyan">FREE SLOT</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="2" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AM401</td>
<td> Time Series Analysis and Forecasting</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS305</td>
<td>Computer Architecture</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS404</td>
<td>Database Management System and its Applications</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19AI410</td>
<td>Introduction to Machine Learning</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19CS549</td>
<td>UI and UX Design </td>
</tr>
</table>
</body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2025-09-24 112609.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
