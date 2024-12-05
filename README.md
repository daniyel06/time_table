# Ex03 Time Table
# Date:
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
    <body>
        <img src="logo.png" width="800" height="200">
        <table border="1" cellspacing="15" cellpadding="2">
            <caption>SLOT TIME TABLE-Daniyel Antony Raj SD(24002985)</caption>
            <tr bgcolor="orange">
                    <th>Time</th>
                    <th>08 - 10</th>
                    <th>10 - 12</th>
                    <th>12 - 01</th>
                    <th>01 - 03</th>
                    <th>03 - 05</th>
                </tr>
                <tr>
                    <th>Monday</th>
                    <td></td>
                    <td>Web</td>
                    <td>L</td>
                    <td>C</td>
                    <td></td>
                </tr>
                <tr>
                    <th>Tuesday</th>
                    <td>Career</td>
                    <td>D.E.</td>
                    <td>U</td>
                    <td>Chem</td>
                    <td></td>
                </tr>
                <tr>
                    <th>Wednesday</th>
                    <td>C</td>
                    <td></td>
                    <td>N</td>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <th>Thursday</th>
                    <td>EDM</td>
                    <td></td>
                    <td>C</td>
                    <td>Web</td>
                    <td></td>
                </tr>
                <tr>
                    <th>Friday</th>
                    <td>Chem</td>
                    <td>Math</td>
                    <td>H</td>
                    <td>D.E.</td>
                    <td></td>
                </tr>
                <tr>
                    <th>Saturday</th>
                    <td>EDM</td>
                    <td></td>
                    <td>H</td>
                    <td>Math</td>
                    <td>Web</td>
                </tr>
                    </table>
    </body>
</html>
<br>
<html>
    <body>
        <table border="2" cellspacing="15" cellpadding="2">
            <caption>COURSE</caption>
            <tr bgcolor="orange">
                <th>S.No</th>
                <th>COURSE CODE</th>
                <th>COURSE NAME</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19EY708</td>
                <td>CAREER DEVOLPMENT</td>
            </tr>
            <TR>
                <td>2</td>
                <td>19AI302</td>
                <td>ENGINEERING DESIGN AND MODELLING</td>
            </TR>
            <TR>
                <td>3</td>
                <td>19MA201</td>
                <td>MATHS</td>
            </TR>
            <TR>
                <td>4</td>
                <td>19CY205</td>
                <td>CHEMISTRY</td>
            </TR>
            <TR>
                <td>5</td>
                <td>19AI414</td>
                <td>WEB APPLICATION DEVELOPMENT</td>
            </TR>
            <TR>
                <td>6</td>
                <td>19AI304</td>
                <td>C PROGRAMMING</td>
            </TR>
            <TR>
                <td>7</td>
                <td>19EE404</td>
                <td>DIGITAL ELECTRONICS</td>
            </TR>
        </table>
    </body>
</html>
```

# OUTPUT
![alt text](<Screenshot 2024-11-28 211340.png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
