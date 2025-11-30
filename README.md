# Ex02 Time Table
## Date:30.11.2025

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
<html>
    <head>
        <title>Timetable</title>
    </head>
    <body>
        <img src="logo.png" width="594px;">
        <br>
        <br>
        <table border="4" cellspacing="3" cellpadding="6" style="background-color: rgb(51, 255, 0);">
            <caption><b>SLOT TIME TABLE - MOHAMED MUBEEN A  (25004201)</b></caption>
            <tr bgcolor="Pink" align="center">
                <th>Day/Time</th>
                <th>MONDAY</th>
                <th>TUESDAY</th>
                <th>WEDNESDAY</th>
                <th>THURSDAY</th>
                <th>FRIDAY</th>
                <th>SATURDAY</th>
            </tr>
            <tr bgcolor="Yellow" align="center">
                <td bgcolor="SkyBlue">8-10</td>
                <td>FREE SLOT</td>
                <td>FCP</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
                <td>FCP</td>
            </tr>
            <tr bgcolor="Yellow" align="center">
                <td bgcolor="SkyBlue">10-12</td>
                <td>FREE SLOT</td>
                <td>CE</td>
                <td>FREE SLOT</td>
                <td>FCP</td>
                <td>FWAD</td>
                <td>FWAD</td>
            </tr>
            <tr bgcolor="Yellow" align="center">
                <td bgcolor="SkyBlue">12-1</td>
                <td colspan="6">LUNCH BREAK</td>
            </tr>
            <tr bgcolor="Yellow" align="center">
                <td bgcolor="SkyBlue">1-3</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>MM</td>
                <td>FREE SLOT</td>
                <td>CE</td>
                <td>FCP</td>
            </tr>
            <tr bgcolor="Yellow" align="center">
                <td bgcolor="SkyBlue">3-5</td>
                <td>CE</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>CE</td>
                <td>FCP</td>
                <td>FREE SLOT</td>
            </tr>
        </table>
        <br>
        <table border="3" cellspacing="4" cellpadding="4">
            <tr align="center">
                <th>S.No.</th>
                <th>Subject Code</th>
                <th style="width: 408px;">Subject Name</th>
            </tr>
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td>Fundamentals of Web Application Development (FWAD)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19EN101</td>
                <td>Communicative English (CE)</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19AI304</td>
                <td>Fundamentals of C Programming (FCP)</td>
            </tr>
        </table>
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot (17).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
