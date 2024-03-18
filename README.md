# Ex03 Time Table
## Date:

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
<!DOCTYPE html>
<html>
<body>
<center><img src="logo.png" style="width:620px;height:120px;">
<h3 align="center"> SLOT TIME TABLE-SHREE LEKHA.S(212223110052)</h3>
<table  style="background-color:rgb(23, 236, 236);"border="4" align="center">

<tr>
<th style="background-color:rgb(255, 255, 0);" >Day/Time</th>
<th style="background-color:rgb(255, 255, 0);" >Monday</th>
<th style="background-color:rgb(255, 255, 0);" >Tuesday</th>
<th style="background-color:rgb(255, 255, 0);" >Wednesday</th>
<th style="background-color:rgb(255, 255, 0);" >Thursday</th>
<th style="background-color:rgb(255, 255, 0);" >Friday</th>
<th style="background-color:rgb(255, 255, 0);" >Saturday</th>
</tr>

<tr>
<th style="background-color:rgb(255, 255, 0);" >8-10</th>
<td>Chemistry</td>
<td>free</td>
<td>Web</td>
<td>EDM</td>
<td>Free</td>
<td>Soft Skill</td>
</tr>

<tr>
<th style="background-color:rgb(255, 255, 0);" >10-12</th>
<td>Beee</td>
<td>Web</td>
<td>CN</td>
<td>Free</td>
<td>C</td>
<td>CN</td>
</tr>

<tr>
<th style="background-color:rgb(255, 255, 0);" >1-3</th>
<td>Web</td>
<td>Gender</td>
<td>Free</td>
<td>Beee</td>
<td>CA</td>
<td>Chemistry</td>

</tr>

<tr >
<th style="background-color:rgb(255, 255, 0);" >3-5</th>
<td>C</td>
<td>EDM</td>
<td>Free</td>
<td>Free</td>
<td>free</td>
<td>free</td>
</tr>


</table>
<br>
<table border="4" align="center">

<tr>
<th>S.no</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>

<tr>
<td>1</td>
<td>19CY205</td>
<td>Principles of Chemistry in Engineering(Chemistry)</td>
</tr>

<tr>
<td>2</td>
<td> 19EE305</td>
<td>Basic Electrical, Electronics and Measurement Engineering(Beee)</td>
</tr>

<tr>
<td>3</td>
<td>19AI414 </td>
<td>Fundamentals of Web Application Development(Web)</td>
</tr>

<tr>
<td>4</td>
<td>19AI304</td>
<td>Fundamentals of C Programming(C)</td>
</tr>


<tr>
<td>5</td>
<td>19EN609</td>
<td>Gender Sensitization(Gender)</td>
</tr>

<tr>
<td>6</td>
<td>19AI302 </td>
<td>Engineering Design and Modelling(EDM)</td>
</tr>
 
<tr>
<td>7</td>
<td> 19CS406</td>
<td>Computer Networks(CN)</td>
</tr>

<tr>
<td>8</td>
<td>19CS305</td>
<td>Computer Architecture(CA)</td>
</tr>

<tr>
<td>9</td>
<td>19EY702 </td>
<td>Creative Skills for Communication(Soft Skill)</td>
</tr>





</table>
</body>
</html>
```


## OUTPUT



![Uploading Screenshot 2024-03-17 203510.png…]()


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
