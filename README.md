# Ex03 Time Table
# Date: 29/03/2025
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
<html lang="en">
    <head>
        <title>Slot time table</title>       
    </head>
    <body>
        <center>
            <img src="logo.png"
            height="100"
            width="540"
        </center>
        <br>
        <table align="center"
        width="540"
        cellspacing="2"
        cellpadding="4"
        border="5"
        bgcolor="cyan">
        <caption><b> Slot time table Rabi Baskar Praburajan (212224040257) </b></caption>
        <tr align="center">
            <th bgcolor="white">Day/Time</th>
            <th bgcolor="white">Monday</th>
            <th bgcolor="white">Tuesday</th>
            <th bgcolor="white">Wednesday</th>
            <th bgcolor="white">Thursday</th>
            <th bgcolor="white">Friday</th>
            <th bgcolor="white">Saturday</th>
    </tr>
    <tr align="center">
        <th bgcolor="white">8-10</th>
        <td colspan="1" align="center">FREE</td>
        <td>ML</td>
        <td>ML</td>
        <td colspan="3" align = "center"> FREE SLOT</td>
    </tr>
    <tr align="center">
        <th bgcolor="white">10-12</th>
        <td>RA</td>
        <td>EVS</td>
        <td>MATHS</td>
        <td>EDM</td> 
        <td>CHE</td>
        <td>C</td>   
    </tr>
    <tr>
        <th bgcolor="white">12-1</th>
        <td colspan="6" align="center">L U N C H B R E A K</td>
    </tr>
    <tr align="center">
        <th bgcolor="white">1-3</th>
        <td>EDM</td>
        <td>FWAD</td>
        <td>MENTOR</td>
        <td>C</td>
        <td>FWAD</td>
        <td colspan="1" align="center">FREE</td>
    </tr>
    <tr align="center">
        <th bgcolor="white">3-5</th>
        <td colspan="2" align="center">FREE</td>
        <td>CHE</td>
        <td>FREE</td>
        <td>MATHS</td>
        <td>FREE</td>
    </tr>
    </table>
    <br>
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
        <td align="center">19AI410</td>
        <td>MACHINE LEARNING</td>
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
        <td align="center">19MA201</td>
        <td>CALCULUS AND MATRIX ALGEBRA</td>
    </tr>
    <tr>
        <td align="center">7.</td>
        <td align="center">19CY801</td>
        <td>ENVIRONMENTAL SCIENCES AND SUSTAINABILITY</td>
    </tr>
    <tr>
        <td align="center">8.</td>
        <td align="center">19EY709</td>
        <td>REASONING ABILITY</td>
    </tr>
</table>
</body>
</html>
```
# OUTPUT
![Screenshot (69)](https://github.com/user-attachments/assets/a289acfc-e609-48e6-963e-f48155e6ddde)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
