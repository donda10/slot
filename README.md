# Ex03 Time Table
## Date:
12-12-2024

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
<!doctype html>
<html>
<head>
<title align="center" >SLOT TIMETABLE</title>
</head>
<BODY TEXT="BLACK">
<img src= "logo.png" width="600">
<br>
<table border= "4" bgcolor="ORANGE" cellpadding="10" cellspacing="5" a
<caption><b>Simon Malachi S 24900355</b></caption>
<tr>
<th>Day/time</th>
<th>8:00-8:10</th>
<th>10:00-12:00</th>
<th Rowspan="7" bgcolor="Green">lunch</th>
<th>1:00-3:00</th>
</tr>
<tr>
<th>Monday</th>
<th>C Prog</th>
<th>UHV</th>
<th></th>
</tr>
<tr>
<th>Tuesday</th>
<th></th>
<th>PHY</th>
<th>WEB</th>
</tr>
<tr>
<th>Wednesday</th>
<th></th>
<th>PYTHON</th>
<th>MENTOR</th>
</tr>
<tr>
<th>Thursday</th>
<th></th>
<th>MATH</th>
<th>WEB</th>
</tr>
<tr>
<th>Friday</th>
<th>PHY</th>
<th>C Prog</th>
<th>PYTHON</th>
</tr>
<tr>
<th>Saturday</th>
<th></th>
<th>WEB</th>
<th>MATH</th>
</tr>
</table>
</BR>
<table border="4" cellspacing="5" width="615">
<tr>
<th>S.NO.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<th>1.</th>
<th>19AI304</th>
<th>FUNDAMENTALS OF C PROGRAMMING</th>
</tr>
<tr>
<th>2.</th>
<th>19A1414</th>
<th>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</th>
</tr>
<tr>
<th>3.</th>
<th>19AI301</th>
<th>PYTHON PROGRAMMING</th>
</tr>
<tr>
<th>4.</th>
<th>19MA222</th>
<th>PROBABILITY OF QUEUEING MODELS </th>
</tr>
<tr>
<th>5.</th>
<th>ECA-M</th>
<th>MENTOR MEET</th>
</tr>
<tr>
<th>6.</th>
<th>SH3214</th>
<th>PHYSICS FOR QUANTUM COMPUTING</th>
</tr>
<tr>
<th>7.</th>
<th>SH7801</th>
<th>HUMAN VALUES AND PROFESSIONAL ETHICS</th>
</tr>
</table>
</body>

</html>


```


## OUTPUT
![alt text](<Screenshot (22).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
