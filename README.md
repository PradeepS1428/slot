# Ex04 Time Table
## Date:17.11.2026

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<!DOCTYPE html>
<html>
<head>
    <title>Slot Time Table</title>
</head>

<body>

<center>

    <!-- College Logo -->
    <img src="logo.png" width="600" height="120">

    <h3>SLOT TIME TABLE - PRADEEP (26015813)</h3>

    <!-- Time Table -->
    <table border="3" cellspacing="2" cellpadding="10"
           bgcolor="yellow">

        <tr bgcolor="red">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>

        <tr>
            <th bgcolor="brown">8-9.30</th>
            <td align="center">PYTH</td>
            <td align="center">PYTH</td>
            <td align="center">PYTH</td>
            <td align="center">FREE SLOT</td>
            <td align="center">MATHS</td>
            <td align="center">MATHS</td>
        </tr>

        <tr>
            <th bgcolor="brown">9.45-11.15</th>
            <td align="center">MATHS</td>
            <td align="center">FWAD</td>
            <td align="center">FREE SLOT</td>
            <td align="center">SNM</td>
            <td align="center">FWAD</td>
            <td align="center">DE</td>
        </tr>

        <tr>
            <th bgcolor="brown">11.15-1.15</th>
            <td colspan="6" align="center">L U N C H</td>
        </tr>

        <tr>
            <th bgcolor="brown">1.15-2.45</th>
            <td align="center">FWAD</td>
            <td align="center">DE</td>
            <td align="center">FREE SLOT</td>
            <td align="center">JAP</td>
            <td align="center">JAP</td>
            <td align="center">SNM</td>
        </tr>

        <tr>
            <th bgcolor="brown">3-4.30</th>
            <td align="center">EDM</td>
            <td align="center">EDM</td>
            <td align="center">CDS</td>
            <td colspan="3" align="center">FREE SLOT</td>
        </tr>

    </table>

    <br><br>

    <!-- Subject Details -->
    <table border="1" cellspacing="2" cellpadding="8">

        <tr>
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
            <td align="center">19AI301</td>
            <td>Python programming(PYTH)</td>
        </tr>

        <tr>
            <td align="center">3.</td>
            <td align="center">19MA220</td>
            <td>Maths for Artificial Intelligence(MATHS)</td>
        </tr>

        <tr>
            <td align="center">4.</td>
            <td align="center">19AI302</td>
            <td>Engineering Design and Modelling(EDM)</td>
        </tr>

        <tr>
            <td align="center">5.</td>
            <td align="center">19EE404</td>
            <td>Digital Electronics(DE)</td>
        </tr>

        <tr>
            <td align="center">6.</td>
            <td align="center">19EY708</td>
            <td>Career Development Skills (CDS)</td>
        </tr>
        <tr>
            <td align="center">7.</td>
            <td align="center">19MA211</td>
            <td>Statistics and Numerical Methods(SNM)</td>
        </tr>
        <tr>
            <td align="center">8.</td>
            <td align="center">19GE624</td>
            <td>Japanese Language(JAP)</td>
        </tr>
        
    </table>

</center>

</body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2026-11-17 110203.png>)
## RESULT

The program for creating slot timetable using basic HTML tags is executed successfully.
