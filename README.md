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
<html>
    <head>
        <title>Saveetha Timetable</title>
    </head>

<body>
<center>
    <img src="/static/logo.png" height="100" width="800" alt="Saveetha Logo">
    <h3>SLOT TIME TABLE - Rivyudhaa M (26001079)</h3>
    <table border="3" cellpadding="8" cellspacing="1"
       width="620" bgcolor="">
       <tr bgcolor="pink">
        <th>Day/Time</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
        <th>Saturday</th>
       </tr>
       <tr>
        <th bgcolor="white">8:00-9:30</th>
        <td>CA</td>
        <td>CDS</td>
        <td>FREE SLOT</td>
        <td>PYTHON</td>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
       </tr>
       <tr>
        <th bgcolor="pink">9:45-11:15</th>
        <td>PYTHON</td>
        <td>FWAD</td>
        <td>FREE SLOT</td>
        <td>PYTHON</td>
        <td>FWAD</td>
        <td>ENG</td>
       </tr>
       <tr>
        <th>11:30-12:15</th>
        <td>SCOFT MENTOR MEET</td>
        <td>SCOFT MENTOR MEET</td>
        <td>SCOFT MENTOR MEET</td>
        <td>L U N C H</td>
        <td>SCOFT MENTOR MEET</td>
        <td>SCOFT MENTOR MEET</td>
       </tr>
       <tr>
        <th bgcolor="pink">12:15-1:00</th>
        <td>L U N C H</td>
        <td>L U N C H</td>
        <td>L U N C H</td>
        <td>SCOFT MENTOR MEET</td>
        <td>L U N C H</td>
        <td>L U N C H</td>
       </tr>
       <tr>
        <th bgcolor="white">1:15-2:44</th>
        <td>FWAD</td>
        <td>MAT</td>
        <td>FREE SLOT</td>
        <td>ENG</td>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
       </tr>
       <tr>
        <th bgcolor="pink">3:00-4:30</th>
        <td>MAT</td>
        <td>PYTHON</td>
        <td>FREE SLOT</td>
        <td>CA</td>
        <td>EDM</td>
        <td>EDM</td>
       </tr>
    </table>
    <br><br>
    <table border="1" cellpadding="8" width=75%>
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>

        <tr>
            <td>1.</td>
            <td>19CS305</td>
            <td>Computer Architecture (CA)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19AI301</td>
            <td>Python Programming (PYTHON)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19MA201</td>
            <td>Calculus and Matrix Algebra (MAT)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19EY708</td>
            <td>Career Development Skills (CDS)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19EN101</td>
            <td>Communicative English (ENG)</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>19AI302</td>
            <td>Engineering Design and Modelling (EDM)</td>
        </tr>
        <tr>
            <td>8.</td>
            <td>E-SCOFT-M</td>
            <td>Mentor Meet</td>
        </tr>
    </table>
</center>
</body>
</html>

```

## OUTPUT
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f78936dc-7248-407b-8808-4c6bd2797835" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/caeabc1d-47f5-4931-80d0-4a8edb553bc6" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
