# Ex03 Time Table
## 212224040232
## Date:21.04.2025

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
<title>Slot TimeTable-Paranthaman</title>
</head>
<body style="background-color:#dff0ec;">
<img src="/static/logo.png" height="100" width="1450">
<br>
<br>
<table align="center" width="540" cellspacing="20" cellpadding="4"
border="5" bgcolor="#4ea1d4">
<caption><b>Slot TimeTable- Paranthaman  212224040232</b></caption>
<br>
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
<td >FREE SLOT</td>
<td>INTRODUCTION TO ML</td>
<td>INTRODUCTION TO ML</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>ETHICAL HACKING</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>FUNDAMENTALS OF C</td>
<td>EMPD</td>
<td>GAME DEVELOPMENT</td>
<td>FUNDAMENTALS OF WEB</td>
<td>GAME DEVELOPMENT</td>
<td>JAPANESE</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="6" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td >ETHICAL HACKING</td>
<td>FUNDAMENTALS OF WEB</td>
<td>MENTOR MEET</td>
<td>PROBABILITY</td>
<td>FUNDAMENTALS OF C</td>
<td>JAPANESE</td>

</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td >FREE SLOT</td>
<td>FREE SLOT</td>
<td>JAPANESE</td>
<td>EMPD</td>
<td>FREE SLOT</td>
<td>PROBABILITY</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center" bgcolor="Slate gray">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
    <td align="center">1.</td>
    <td align="center">19AI414</td>
    <td>FUNDAMENTALS OF WEB</td>
</tr>
<tr>
    <td align="center">2.</td>
    <td align="center">19AI303</td>
    <td>EMPD</td>
</tr>
<tr>
    <td align="center">3.</td>
    <td align="center">19AI410</td>
    <td>INTRODUCTION TO ML</td>
</tr>
<tr>
    <td align="center">4.</td>
    <td align="center">19CS417</td>
    <td>ETHICAL HACKING</td>
</tr>
<tr>
    <td align="center">5.</td>
    <td align="center">19IT402</td>
    <td>GAME DEVELOPMENT</td>
</tr>
<tr>
    <td align="center">6.</td>
    <td align="center">19MA222</td>
    <td>PROBABILITY</td>
</tr>
<tr>
    <td align="center">7.</td>
    <td align="center">19CY801</td>
    <td>JAPANESE</td>
</tr>
<tr>
    <td align="center">8.</td>
    <td align="center">19AI304</td>
    <td>FUNDAMENTALS OF C</td>
 </tr>
</table>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-04-21 090559.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
