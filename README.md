# Ex03 Time Table
## Date:15-11-2024

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
    <img src="logo.png" alt="SAVEETHA LOGO" width="1550px" height="150px" >
    <br>
    <br>
    <table border="1" cellspacing="2" cellpadding="5" align="center">
        <caption align="center" style="color: brown;">
            <b>TIME TABLE - NANDA KISHOR(24011485)</b> 
            <p>   </p>
        </caption>
        <tr>
            <th>Days</th>
            <th>8:00-10:00</th>
            <th>10:00-12:00</th>
            <th>12:00-1:00</th>
            <th>1:00-3:00</th>
            <th>3:00-5:00</th>
        </tr>
        <tr>
            <th>MONDAY</th>
            <td bgcolor="red">FREE</td>
            <td>MATH (19MA201)</td>
            <th>L</th>
            <td>C PROG (19AI304)</td>
            <td bgcolor="red">FREE</td>
        </tr>
        <tr>
            <th>TUESDAY</th>
            <td>FWAD (19AI414)</td>
            <td bgcolor="red">FREE</td>
            <th>U</th>
            <td>MATH (19MA201)</td>
            <td>DE (19EE404)</td>
        </tr>
        <tr>
            <th>WEDNESDAY</th>
            <td bgcolor="red">FREE</td>
            <td>CHEM (19CY205)</td>
            <th>N</th>
            <td>MENTOR MEET</td>
            <td bgcolor="red">FREE</td>
        </tr>
        <tr>
            <th>THURSDAY</th>
            <td>UHV (SH7801)</td>
            <td>CDS (19EY708)</td>
            <th>C</th>
            <td>DE (19EE404)</td>
            <td bgcolor="red">FREE</td>
        </tr>
        <tr>
            <th>FRIDAY</th>
            <td bgcolor="red">FREE</td>
            <td>CHEM(19CY205)</td>
            <th>H</th>
            <td>FWAD(19AI414)</td>
            <td bgcolor="red">FREE</td>
        </tr>
        <tr>
            <th>SATURDAY</th>
            <td bgcolor="red">FREE</td>
            <td>C PROG (19AI304)</td>
            <th align="center">HOUR</th>
            <td>FWAD (19AI414)</td>
            <td bgcolor="red">FREE</td>
        </tr>
    </table>
    <br>
    <br>
    <br>
    <table border="1" cellspacing="2" cellpadding="2" align="center">
        <caption style="color: blue;"><b>COURSE NAME</b> <p>      </p></caption>
        <tr>
            <th>S.NO</th>
            <th>COURSE CODE</th>
            <th>COURSE NAME</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI304</td>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19AI414</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19CY205</td>
            <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19EE404</td>
            <td>DIGITAL ELECTRONICS</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19EY708</td>
            <td>CAREER DEVELOPMENT SKILLS</td>
        </tr>
        <tr>
            <td>6</td>
            <td>19MA201</td>
            <td>CALCULUS AND MATRIX ALGEBRA</td>
        </tr>
        <tr>
            <td>7</td>
            <td>SH7801</td>
            <td>HUMAN VALUES & PROFESSIONAL ETHICS</td>
        </tr>
        <tr>
            <td>8</td>
            <td>ECA-M SCOFT</td>
            <td>MENTOR MEET</td>
        </tr>
    </table>
</html>

```

## OUTPUT

![alt text](<Screenshot (29).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
