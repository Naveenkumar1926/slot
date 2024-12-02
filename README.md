# Ex03 Time Table
## Date:19/11/24

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
<img src="/static/logo.png"  width="500" height="70">
</center>
<table align="center" width="700" cellspacing="2" cellpadding="1" border="4" bgcolor="lavender">
<caption><b>SLOT TIME TABLE - ROHITH J (24000942)</b></caption>
<tr align="center">
<th bgcolor="lightblue">Day/Time</th>
<th bgcolor="skyblue">Monday
<th bgcolor="skyblue">Tuesday
<th bgcolor="skyblue">Wednesday
<th bgcolor="skyblue">Thursday
<th bgcolor="skyblue">Friday
<th bgcolor="skyblue">Saturday
</tr>
<tr align="center">
<th bgcolor="skyblue">8am-10am</th>
<td >Free</td>
<td >Free</td>
<td >Free</td>
<td >Human Values and Professional Ethics</td>
<td >Free</td>
<td >Free</td>
</tr>
<tr align="center">
<th bgcolor="skyblue">10am-12pm</th>
<td >Fundamentals of Web Application Development</td>
<td >Inroduction to Data Science</td>
<td >Fundamentals of Web Application Development</td>
<td >C-programming</td>
<td >Communicative English</td>
<td >Digital Electronics</td>
</tr>
<tr>
<th bgcolor="skyblue">12pm-01pm</th>
<td colspan="6" align="center"> L U N C H - T I M E </td>
</tr>
<tr>
<tr align="center">
<th bgcolor="skyblue">01pm-03pm</th>
<td >>Digital Electronics</td>
<td >C-programming</td>
<td >Mentor Meeting</td>
<td >Communicative English</td>
<td >Inroduction to Data Science</td>
<td >Fundamentals of Web Application Development</td>
</tr>
<tr align="center">
<th bgcolor="skyblue">03pm-05pm</th>
<td >Free</td>
<td >Free</td>
<td >Free</td>
<td >Free</td>
<td >Free</td>
<td >Free</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>No.</th>
<th>Subject Code:</th>
<th>Subject Name:</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI403</td>
<td>Introduction to Data Science</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI304</td>
<td>C-programming</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19EE404</td>
<td>Digital Electronics</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">SH7801</td>
<td>Human Values and Professional Ethics</td>
<tr>
<td align="center">6.</td>
<td align="center">19EY708</td>
<td>Communicative English</td>
</tr>
</table>
</body>
</html>   

```
## OUTPUT
![alt text](<Screenshot 2024-12-02 090345.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
