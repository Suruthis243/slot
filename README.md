# Ex03 Time Table
## Date: 05.11.2025

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
	<title>SLOT TIMETABLE</title>
	<body>
	<center>
	<table border="5" bgcolor="yellow" cell spacing="10" cellpadding="10">
	<caption>SLOT TIME TABLE-SURUTHI S(24013561)</caption>
	<img src = "/static/logo.png" height="100" width="540">
	<tr>
	<TR bgcolor="violet">
	<th>Day/Time</th>
	<th>Monday</th>
	<th>Tuesday</th>
	<th>Wednesday</th>
	<th>Thursday</th>
	<th>Friday</th>
    <th>Saturday</th>
	</TR>
	<tr>
	<th bgcolor="violet">8-10</th>
	<td>FREE SLOT</td>
	<td>CA</td>
	<td>C PROGRAM</td>
	<td>FREE SLOT</td>
	<td>CHEMISTRY</td>
    <td>FREE SLOT</td>
	</tr>
	<tr>
	<th bgcolor="violet">10-12</th>
	<td>FWAD</td>
	<td>CALCULUS</td>
	<td>FWAD</td>
	<td>CA</td>
	<td>CDS</td>
    <td>CALCUS</td>
	</tr>
	<tr>
	<th bgcolor="violet">1-3</th>
	<td>C PROGRAM</td>
	<td>CHEMISTRY</td>
	<td>MM</td>
	<td>FREE SLOT</td>
	<td>FREE SLOT</td>
    <td>FWAD</td>
	</tr>
	</table>
	<br>
	<table>
	<table border="5" cell spacing="10" cellspading="15">
	<tr>
	<th>S.NO</th>
	<th>SUBJECT CODE</th>
	<th>SUBJECT NAME</th>
	</tr>
	<tr>
	<th>1</th>
	<td>19A1414</td>
	<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT(FWAD)</td>
	</tr>
	<tr>
	<th>2</th>
	<td>19AI304</td>
	<td>FUNDAMENTALS OF C PROGRAMMING(C PROGRAM)</td>
	</tr>
	<tr>
	<th>3</th>
	<td>19CS305</td>
	<td>COMPUTER ARCHITECTURE(CA)</td>
	</tr>
	<tr>
	<th>4</th>
	<td>19PH214</td>
	<td>PHYSICS AND QUANTUM COMPUTING(PQC)</td>
	</tr>
	<tr>
	<th>5</th>
	<td>19CY205</td>
	<td>PRINCIPLE OF CHEMISTRY IN ENGINEERING(CHEMISTRY)</td>
	</tr>
    <tr>
    <th>6</th>
    <td>ECA-M-SCOFT</td>
    <td>MENTOR MEET(MM)</td>
    </tr>
	</table>
	</body>
	</center>
	</head>
</html>
```

## OUTPUT
<img width="949" height="512" alt="Screenshot 2025-11-05 134030" src="https://github.com/user-attachments/assets/f236c5b2-a435-45db-85a1-720768eac578" />



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
