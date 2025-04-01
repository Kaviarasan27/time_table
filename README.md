# Ex03 Time Table
# Date:31-03-2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<html>
<head>
<title>Timetable</title>
</head>
<body>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
    <caption><b>TIME TABLE -kaviaarasan (212224110030)</b></caption> -
    <tr align="center">
        <th bgcolor="yellow">Day/Time</th>
        <th bgcolor="yellow">Monday</th>
        <th bgcolor="yellow">Tuesday</th>
        <th bgcolor="yellow">Wednesday</th> 
        <th bgcolor="yellow">Thursday</th>
        <th bgcolor="yellow">Friday</th>
        <th bgcolor="yellow">saturday</th>
    </tr>
    <tr align="center">
        <th bgcolor="yellow">8-10</th>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
        <td>FUNDAMENTALS OF C PROGRAMMING</td>
        <td>FUNDAMENTALS OF C PROGRAMMING</td>
        <td>FREE SLOT</td>
    </tr>
    <tr align="center">
        <th bgcolor="yellow">10-12</th>
        <td>BASIC ELECTRICAL, ELECTRONICS AND MEASUREMENT ENGINEERING</td>
        <td>FREE SLOT</td>
        <td>HUMAN VALUES AND PROFESSIONAL ETHICS</td>
        <td>ENGINEERING DESIGN AND MODELLING</td>
        <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
        <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
    </tr>
    <tr>
        <th bgcolor="light green">12-1</th>
        <td colspan="6" align="center">L U N C H</td>
    </tr>
    <tr align="center">
        <th bgcolor="yellow">1-3</th>
        <td>FREE SLOT </td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        <td>MENTOR MEETING</td>
        <td>STATISTICS AND NUMERICAL METHODS</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        <td>STATISTICS AND NUMERICAL METHODS</td>
    </tr>
    <tr align="center">
        <th bgcolor="yellow">3-5</th>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
        <td>ENGINEERING DESIGN AND MODELLING</td>
        <td>FREE SLOT</td>
        <td>BASIC ELECTRICAL, ELECTRONICS AND MEASUREMENT ENGINEERING</td>
        <td>FREE SLOT</td>
    </tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
    <tr align="center">
        <th>S. No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
    </tr>
    <tr>
        <td align="center">1.</td>
        <td align="center">19AI414</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
    </tr>
    <tr>
        <td align="center">2.</td>
        <td align="center">19AI304</td>
        <td>FUNDAMENTALS OF C PROGRAMMING</td>
    </tr>
    <tr>
        <td align="center">3.</td>
        <td align="center">19EE305</td>
        <td>BASIC ELECTRICAL, ELECTRONICS AND MEASUREMENT ENGINEERING</td>
    </tr>
    <tr>
        <td align="center">4.</td>
        <td align="center">19AI302</td>
        <td>ENGINEERING DESIGN AND MODELLING</td>
    </tr>
    <tr>
        <td align="center">5.</td>
        <td align="center">19CY205 </td>
        <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
    </tr>
    <tr>
        <td align="center">6.</td>
        <td align="center">19MA211</td>
        <td>STATISTICS AND NUMERICAL METHODS</td>
    </tr>
    <tr>
        <td align="center">7.</td>
        <td align="center">19HS801</td>
        <td>HUMAN VALUES AND PROFESSIONAL ETHICS</td>
    </tr>
</table>
</body>
</html>

```
# OUTPUT

![Screenshot 2025-04-01 090127](https://github.com/user-attachments/assets/a9ceff20-9d2d-42bf-bd9f-49b73ba8cdc4)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
