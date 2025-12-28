# Ex02 Time Table
## Date:24/12/25

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
time.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <center>
        <img src="logo.png" height="100" width="700">
    </center>
    <h1 align ="center"><b>SLOT TIME TABLE-KIRUTHIKAVASANTHIM (25013097)</b></h1>
    <table align="center" border="5" cellpadding="6" cellspacing="2">
        <tr>
            <th bgcolor="yellow">DAY/TIME</th>
            <th bgcolor="yellow">MONDAY</th>
            <th bgcolor="yellow">TUESDAY</th>
            <th bgcolor="yellow">WEDNESDAY</th>
            <th bgcolor="yellow">THURSDAY</th>
            <th bgcolor="yellow">FRIDAY</th>
            <th bgcolor="yellow">SATURDAY</th>
        </tr>
        <tr>
            <th bgcolor="yellow" align="center">8-10</th>
            <td bgcolor="lightblue" align="center">PUBLIC SPEAKING</td>
            <td bgcolor="lightblue" align="center">PYTHON</td>
            <td bgcolor="lightblue" align="center">-</td>
            <td bgcolor="lightblue" align="center">-</td>
            <td bgcolor="lightblue" align="center">WEB</td>
            <td bgcolor="lightblue" align="center">-</td>
        </tr>
        <tr>
            <th bgcolor="yellow">10-12</th>
            <td bgcolor="lightblue" align="center">PYTHON</td>
            <td bgcolor="lightblue" align="center">-</td>
            <td bgcolor="lightblue" align="center">WEB</td>
            <td bgcolor="lightblue" align="center">-</td>
            <td bgcolor="lightblue" align="center">PUBLIC SPEAKING</td>
            <td bgcolor="lightblue" align="center">-</td>
        </tr>
        <tr>
            <th bgcolor="yellow">12-1</th>
            <td bgcolor="lightblue" colspan="6" align="center">LUNCH</td>
        </tr>
        <tr>
            <th bgcolor="yellow">1-3</th>
            <td bgcolor="lightblue" align="center">-</td>
            <td bgcolor="lightblue" align="center">WEB</td>
            <td bgcolor="lightblue" align="center">MENTOR MEET</td>
            <td bgcolor="lightblue" align="center">WEB</td>
            <td bgcolor="lightblue" align="center">PYTHON</td>
            <td bgcolor="lightblue" align="center">PUBLIC SPEAKING</td>
        </tr>
        <tr>
            <th bgcolor="yellow">3-5</th>
            <td bgcolor="lightblue" align="center">-</td>
            <td bgcolor="lightblue" align="center">PUBLIC SPEAKING</td>
            <td bgcolor="lightblue" align="center">-</td>
            <td bgcolor="lightblue" align="center">PYTHON</td>
            <td bgcolor="lightblue" align="center">-</td>
            <td bgcolor="lightblue" align="center">PUBLIC SPEAKING</td>
        </tr>
    </table>
</body>
</html>
```

## OUTPUT

![WhatsApp Image 2025-12-28 at 12 57 17](https://github.com/user-attachments/assets/11c7521e-f318-40e3-b3a1-b236aaf2c0f2)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
