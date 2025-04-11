# Ex03 Time Table
## Date:11.04.2025

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
<html>
<head>
    <title>Document</title>
    <center>
        <img src="c:\Users\admin\Downloads\logo.png" height="100" ; width="540">
    </center>
</head>
<body>
        <Table Border="1" Align="center" cellpadding="5" >  
        <tr>
            <th>Time/Day</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <td>8-10</td>
            <td>free slot</td>
            <td colspan="2" ;align="center">Free Slot</td>
            <td>free slot</td>
            <td colspan="2" ;align="center">Free Slot</td>
        </tr>
        <tr>
            <td>10-12</td>
            <td>Fundamentals of c programming</td>
            <td>EMPD</td>
            <td>FWAD</td>
            <td>Computer networks</td>
            <td>Reasoning ability</td>
            <td>Fundamentals of c programming</td>
        </tr>
        <tr>
            <td>1-3</td>
            <td>Free slot</td>
            <td>Free slot</td>
            <td>Mentor Meet</td>
            <td>Free slot</td>
            <td>Computer networks</td>
            <td>Free slot</td>
        </tr>
        <tr>
            <td>3-5</td>
            <td>Free slot</td>
            <td>Introduction to datascience</td>
            <td>Introduction to datascience</td>>
            <td>EMPD</td>
            <td>FWAD</td>
            <td>Free Slot</td>
        </tr>
    </Table>
   <Table Border="1" Align="center" cellpadding="7" >  
        <tr>
            <th>S.NO</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19CS406</td>
            <td>Compurt Networks</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19EY709</td>
            <td>Reasoning ability</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19AI403</td>
            <td>introduction to data science</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19AI304</td>
            <td>Fundamentals of C programming</td>
        </tr>
        <tr>
            <td>6</td>
            <td>19AI303</td>
            <td>Engineering mechanics and product development</td>
        </tr>
    </Table>
</body>
</html>

```



## OUTPUT
![Screenshot 2025-04-11 093856](https://github.com/user-attachments/assets/fa37316e-701e-4590-9d0b-24a46cf7b0e6)
![Screenshot 2025-04-11 093810](https://github.com/user-attachments/assets/3a72014c-4a68-4378-ab3e-0937f7eeb3f8)




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
