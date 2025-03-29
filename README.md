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
</body>
</html>
```
# OUTPUT
![Screenshot (68)](https://github.com/user-attachments/assets/404181ef-7d40-41c0-8142-87b10ed799bb)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
