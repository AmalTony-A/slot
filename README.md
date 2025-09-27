# Ex03 Time Table
## Date: 18.09.2025

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
<head>
    <title>Time Table</title>
    <style>
        .a th {
            background-color: rgb(8, 191, 236);
        }
        .a td {
            background-color: rgb(236, 254, 41);
        }
        img {
            width: 550px;
            height: auto;
        }
    </style>
</head>
<body>
    <center>
    <img src="/static/logo.png">
    <br><br>
    <div class="a">
    <table border="4">
        <caption>SLOT TIME TABLE - A. Amal Tony Charles (25016419)</caption>
        <thead>
            <tr>
                <th>Date/Time</th>
                <th>8-10</th>
                <th>10-12</th>
                <th>12-1</th>
                <th>1-3</th>
                <th>3-5</th>
            </tr> 
        </thead>
        <tbody>
            <tr><th>Monday</th><td>Free slot</td><td>Python programming</td><td rowspan="6">Lunch</td><td>Free slot</td><td>Free slot</td></tr>
            <tr><th>Tuesday</th><td>FC</td><td>Free slot</td><td>Free slot</td><td>FC</td></tr>
            <tr><th>Wednesday</th><td>FWAD</td><td>FWAD</td><td>Mentor meet</td><td>Python programming</td></tr>
            <tr><th>Thursday</th><td>Python programming</td><td>Python programming</td><td>Free slot</td><td>Free slot</td></tr>
            <tr><th>Friday</th><td>FC</td><td>Free slot</td><td>FWAD</td><td>Python programming</td></tr>
            <tr><th>Saturday</th><td>FWAD</td><td>FC</td><td>FWAD</td><td>Free slot</td></tr>
        </tbody>
    </table>
    </div>
    <br>
    <table border="1">
        <caption>Subject List</caption>
        <thead>
            <tr>
                <th>S.NO.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
        </thead>
        <tbody>
            <tr><th>1.</th><td>19AI414</td><td>FWAD</td></tr>
            <tr><th>2.</th><td>19AI301</td><td>Python programming</td></tr>
            <tr><th>3.</th><td>19CS547</td><td>Fundamentals of Crypto Currency</td></tr>
        </tbody>
    </table>
    </center>
</body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2025-09-27 211524.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
