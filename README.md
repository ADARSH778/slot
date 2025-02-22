# Ex03 Time Table
## Date:18-03-2024

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
<head>
    <title>SEC SLOT TIMETABLE</title>
</head>
<img src="logo.png" width='600'align='center'>
<body>
    <table BORDER='3' width='600'bgcolor='cyan' cellspacing='3'>
        <CAPTION align="above">SLOT TIMETABLE-ADARSH CHOWDARY R(212223040166)</CAPTION>
        <tr>
            <th align="center" bgcolor="orange">Day/Time</th>
            <th align="center" bgcolor="orange">Monday</th>
            <th align="center" bgcolor="orange">Tuesday</th>
            <th align="center" bgcolor="orange">Wednesday</th>
            <th align="center" bgcolor="orange">Thursday</th>
            <th align="center" bgcolor="orange">Friday</th>
            <th align="center" bgcolor="orange">Saturday</th>
        </tr>

        <tr>
            <th align="center" bgcolor="orange">8-10</th>
            <td align="center" bgcolor="gold">PHY</td>
            <td align="center" bgcolor="gold">BEEE</td>
            <td align="center" bgcolor="gold">FWAD</td>
            <td align="center" bgcolor="gold">PHY</td>
            <td align="center" bgcolor="gold">BEEE</td>
            <td align="center" bgcolor="gold">PQM</td>
        </tr>

        <tr>
            <th align="center" bgcolor="orange">10-12</th>
            <td align="center" bgcolor="gold">FREE SLOT</td>
            <td align="center" bgcolor="gold">FWAD</td>
            <td align="center" bgcolor="gold">FREE SLOT</td>
            <td align="center" bgcolor="gold">PQM</td>
            <td align="center" bgcolor="gold">C</td>
            <td align="center" bgcolor="gold">DE</td>
        </tr>

        <tr>
            <th align="center" bgcolor="orange">12-1</th>
            <td align="center" bgcolor="silver" colspan="6">LUNCH</td>
        </tr>

        <tr>
            <th align="center" bgcolor="orange">1-3</th>
            <td align="center" bgcolor="gold">FWAD</td>
            <td align="center" bgcolor="gold">FREE SLOT</td>
            <td align="center" bgcolor="gold">DE</td>
            <td align="center" bgcolor="gold">FREE SLOT</td>
            <td align="center" bgcolor="gold">CN</td>
            <td align="center" bgcolor="gold">FREE SLOT</td>
        </tr>


        <tr>
            <th align="center" bgcolor="orange">3-5</th>
            <td align="center" bgcolor="gold">C</td>
            <td align="center" bgcolor="gold">FREE SLOT</td>
            <td align="center" bgcolor="gold">CN</td>
            <td align="center" bgcolor="gold">FREE SLOT</td>
            <td align="center" bgcolor="gold">FREE SLOT</td>
            <td align="center" bgcolor="gold">FREE SLOT</td>
        </tr>
    </table>

    <table border="3" width="600" cellspacing="3" cellpaddling="3">

        <tr>
            <th align="center">S.NO</th>
            <th align="center">SUBJECT CODE</th>
            <th align="center">subject name</th>
        </tr>

        <tr>
            <td align="center">1</td>
            <td align="center">19AI304</td>
            <td align="center">Fundamental of  C programming(C)</td>
        </tr>

        <tr>
            <td align="center">2</td>
            <td align="center">19AI414</td>
            <td align="center">Fundamentals of Web Application Development(FWAD)</td>
        </tr>

        <tr>
            <td align="center">3</td>
            <td align="center">19CS406</td>
            <td align="center">Computer Networks(CN)</td>
        </tr>

        <tr>
            <td align="center">4</td>
            <td align="center">19EE305</td>
            <td align="center">Basic Electrical,Electronics and Measurement Engineering(BEEE)</td>
        </tr>

        <tr>
            <td align="center">5</td>
            <td align="center">19EE404</td>
            <td align="center">Digital Electronics(DE)</td>
        </tr>

        <tr>
            <td align="center">6</td>
            <td align="center">19MA222</td>
            <td align="center">Probability and Queueing models(PQM)</td>
        </tr>
    
        <tr>
            <td align="center">7</td>
            <td align="center">19PH214</td>
            <td align="center">Physics for quantum computing(PHY)</td>
        </tr>
    </body>
    </html>
```
## OUTPUT
![alt text](<Screenshot (17).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
