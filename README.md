# table-creation
AIM:

TO CREATE THE TABLE AND FORM USING BASIC HTML TAGS.

PROCEDURE:

•	Open a Html Document
•	Create a table using the tags <table></table>.
•	Create rows in the table using <tr>This is the row tag</tr>.
•	Insert the data into rows using <td> Table Data</td> tags.
•	Close the table tag.
•	Close the html tag </html>


SOURCE CODE:

<html>
<head>
<title> TIME TABLE
</title>
</head>


<body>
<h1>
<u> CS&BS TIME TABLE </u>
</h1>


<table>
<table border = 5 width = 1000 >
<tr>
<th> TIME </th>
 


<th> 8:30 - 9:20 </th>
<th> 9:20 - 10:10 </th>
<th> 10:10 - 10:30 </th>
<th> 10:30 - 11:20 </th>
<th> 11:20 - 12:10 </th>
<th> 12:10 - 12:50 </th>
<th> 12:50 - 1:40 </th>
<th> 1:40 - 2:30 </th>
<th> 2:30 - 3:20 </th>

</tr>
<tr>
<th> PERIOD </th>
<th> 1 </th>
<th> 2 </th>
<th rowspan="6">Break</th>
<th> 3 </th>
<th> 4 </th>
<th rowspan="6">Lunch</th>
<th> 5 </th>
<th> 6 </th>
<th> 7 </th>
</tr>
<tr>
<th> DAY 1 </th>
<th> IS </th>
<th> PE2 </th>
<th> AI </th>
<th> CN </th>
<th colspan="2">PE2 Lab</th>
<th> BCVS </th>
</tr>
 


<tr>
<th> DAY 2 </th>
<th> PE2 </th>
<th> CN </th>
<th> IS </th>
<th> PE3 </th>
<th> IAF </th>
<th colspan="2">PE3 Lab</th>
</tr>
<tr>
<th> DAY 3 </th>
<th> PE3 </th>
<th> IS </th>
<th> FCA </th>
<th> AI </th>
<th> CN </th>
<th colspan="2">IS/CN LAb</th>
</tr>
<tr>
<th> DAY 4 </th>
<th> CN </th>
<th> IAF </th>
<th> BCVS </th>
<th> PE2 </th>
<th> AI </th>
<th colspan="2">AI/CN Lab</th>
</tr>
<tr>
<th> DAY 5 </th>
<th> FCA </th>
<th> AI </th>
 


<th> IS </th>
<th> PE2 </th>
<th colspan="2">AI/IS Lab</th>
<th> CPS </th>

</tr>
</table>
</body>
</html>




 AIM
TO CREATE A FORM (STUDENT MARK ENTRY)USING BASIC HTML TAGS.


PROCEDURE:

1-	Open your HTML document.
2-	The content of an HTML form must be typed within the <form> and </form> tags. 3- Create a text box using <input type="text" />.
4-Add combo buttons for options. Using <select> tag. 5- Create a Submit <button>.
6-	Create a Reset <button>.
7-	Type </form> at the end of the form. SOURCE CODE:
<html>
<head>
<title>Student Mark Entry</title>
</head>


<body>
<center>
<br>
<h1>Student Mark Entry</h1>
 


<table>
<form>
<tr>
<td>NAME:</td>
<td><input type="text"></td>
</tr>
<tr>
<td>REGISTRATION NO:</td>
<td><input type="text"></td>
</tr>
<tr>
<td>SECTION:</td>
<td><select name="sec" id="sec">
<option value="" disabled selected hidden>Choose a Section</option>
<option value="A">CSE A</option>
<option value="B">CSE B</option>
<option value="C">CSE C</option>
<option value="D">AI&ML</option>
<option value="E">CS&BS</option>
</select></td>
</tr>
<tr>
<td>ENTER MARKS:</td>
</tr>
<tr>
<td>ADVANCE FINANCE:</td>
<td><input type="number"></td>
</tr>
<tr>
<td>ARTIFICAL INTELLIGENCE:</td>
<td><input type="number"></td>
 


</tr>
<tr>
<td>BUSINESS COMMUNICATION & VALUE SCIENCE:</td>
<td><input type="number"></td>
</tr>
<tr>
<td>COMPUTER NETWORK:</td>
<td><input type="number"></td>
</tr>
<tr>
<td>FINANCIAL AND COST ACCOUNTING:</td>
<td><input type="number"></td>
</tr>
<tr>
<td>INFORMATION SECURITY:</td>
<td><input type="number"></td>
</tr>
<tr>
<td>MODERN WEB APPLICATION:</td>
<td><input type="number"></td>
</tr>
<tr>
<td><input type="submit" value="submit"></td>
<td><input type="reset" value="reset"></td>
</tr>
</form>
</table>
</center>
</body>
OUTPUT:
 



 





RESULT:

TO CREATE THE TABLE AND FORM USING BASIC HTML TAGS IS SUCCESSFULLY COMPLETED.


