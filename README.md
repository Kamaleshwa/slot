# Ex03 Time Table
## Date:

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

<!DOCTYPE html>
<html>
<head>
    <title>SLOT TIME TABLE - KAMALESHWAR (212223240063)</title>
    <style>
            table {
                border-collapse: collapse;
                width: 80%;
                margin: 5px auto;
        }

        table + table {
            margin-top: 20px;
        }

        th, td {
            border: 5px solid Black;
            text-align: center;
            padding: 8px;
        }

        img {
            width: 100%;
            height: 15%;
        }

        .center-text {
            text-align: center;
        }
        
        strong {
            font-weight: bold;
            font-size: 30px;
        }
        ```
    </style>
 </head>
 <body>
    <img src="c:\Users\admin\Pictures\capcut\logo.png">
    <div class="center-text">
        
        <p><strong>SLOT TIME TABLE - KAMALESHWAR (212223240063) </strong></p>
    </div>
    <table>
        <tr>
            <th colspan="1" bgcolor="red">Day/Time</th>
            <th colspan="1" bgcolor="red">Monday</th>
            <th colspan="1" bgcolor="red">Tuesday</th>
            <th colspan="1" bgcolor="red">Wednesday</th>
            <th colspan="1" bgcolor="red">Thursday</th>
            <th colspan="1" bgcolor="red">Friday</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="blue">8-10</th>
            <th colspan="3" bgcolor="pink">FREE SLOT</th>
            <th colspan="1" bgcolor="pink">PHY</th>
            <th colspan="1" bgcolor="pink">CHE</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="blue">10-12</th>
            <th colspan="1" bgcolor="pink">GER</th>
            <th colspan="1" bgcolor="pink">FREE SLOT</th>
            <th colspan="1" bgcolor="pink">FWAD</th>
            <th colspan="1" bgcolor="pink">FWAD</th>
            <th colspan="1" bgcolor="pink">PHY</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="blue">12-1</th>
            <th colspan="5" bgcolor="pink">LUNCH</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="blue">1-3</th>
            <th colspan="2" bgcolor="pink">FREE SLOT</th>
            <th colspan="1" bgcolor="pink">MAT</th>
            <th colspan="1" bgcolor="pink">MAT</th>
            <th colspan="1" bgcolor="pink">SS</th>
        </tr>
        </tr>
        <tr>
            <th colspan="1" bgcolor="blue">3-5</th>
            <th colspan="2" bgcolor="pink">FREE SLOT</th>
            <th colspan="1" bgcolor="pink">GER</th>
            <th colspan="1" bgcolor="pink">CHE</th>
            <th colspan="1" bgcolor="pink">FWAD</th>
        </tr>
    </table>

    <table>
        <tr>
            <th colspan="1" bgcolor="White">S. No.</th>
            <th colspan="1" bgcolor="White">Subject Code</th>
            <th colspan="2" bgcolor="White">Subject Name</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">1.</th>
            <th colspan="1" bgcolor="White">19AI41</th>
            <th colspan="2" bgcolor="White">Fundamentals of Web Application Development(FWAD)</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">2.</th>
            <th colspan="1" bgcolor="White">19EN612</th>
            <th colspan="2" bgcolor="White">German Basic (GER)</th>        
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">3.</th>
            <th colspan="1" bgcolor="White">19PH206</th>
            <th colspan="2" bgcolor="White">Physics for Information Technology (PHY)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">4.</th>
            <th colspan="1" bgcolor="White">19CY205</th>
            <th colspan="2" bgcolor="White">Principles of Chemistry in Engineering (CHE)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">5.</th>
            <th colspan="1" bgcolor="White">19MA201</th>
            <th colspan="2" bgcolor="White">Calculus and Matrix Algebra (MAT)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">6.</th>
            <th colspan="1" bgcolor="White">19EY701</th>
            <th colspan="2" bgcolor="White">Soft Skills (SS)</th> 
        </tr>
    </table>
</body>
</html>
```

## OUTPUT
![image](https://github.com/Kamaleshwa/slot/assets/144980199/5931d58b-3f2e-4c29-b7fd-9de69f2d8e4c)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
