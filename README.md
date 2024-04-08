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
<html>
    <head>
        <title>SLOT TIMETABLE-ARIVAZHAGAN G R</title>
</head>
<body bgcolor="yellow">
    <center>
    <img src="/static/logo.png" height="100" width="540">
    </center>
<table border="3" cellspacing="4" cellpadding="6" align="center" bgcolor="lightgrey">
<caption>SLOT TIMETABLE-ARIVAZHAGAN G R(212223040020)</caption>
            <tr>
               <th bgcolor="pink">Day/Time</th>
               <th bgcolor="pink">Monday</th>
               <th bgcolor="pink">Tuesday</th>
               <th bgcolor="pink">Wednesday</th>
               <th bgcolor="pink">Thursday</th>
               <th bgcolor="pink">Friday</th>
               <th bgcolor="pink">Saturday</th>
          </tr>
           <tr>
               <td>8:00-10:00</td>
               <td>CREATIVE SKILL</td>
               <td>D.E</td>
               <td>Fundamentals of web applications</td>
               <td>D.E</td>
               <td>FREE SLOT</td>
               <td>PROBABILITY</td>
          </tr>
          <tr>
               <td>10:00-12:00</td>
               <td>Free Slot</td>
               <td>Fundamentals of web applications</td>
               <td>FREE SLOT</td>
               <td>PROBABILITY</td>
               <td>Fundamental of C</td>
               <td>FREE SLOT</td>
          </tr>
          <tr>
               <td>12:00-1:00</td>
               <td colspan="6" align="center" bgcolor="skyblue">Lunch</td>
          </tr>
          <tr>
               <td>1:00-3:00</td>
               <td>Fundamentals of web applications</td>
               <td>FREE SLOT</td>
               <td>STATS</td>
               <td>Free Slot</td>
               <td>CN</td>
               <td>STATS</td>

          </tr>
          <tr>
               <td>3:00-5:00</td>
               <td>Fundamentals of C</td>
               <td>Free Slot</td>
               <td>CN</td>
               <td>FREE SLOT</td>
               <td>FREE SLOT</td>
               <td>Free Slot</td>
         
          </tr>
<table border="3" cellspacing="4" cellpadding="6" align="center" bgcolor="lightgrey">
<caption>SUBJECT DETAILS</caption>
          <tr>
               <th bgcolor="pink">S.no</th>
               <th bgcolor="pink">Subject Code</th>
               <th bgcolor="pink">Subject Name</th>
               
          </tr>
          <tr>
               <td>01</td>
               <td>19EE404</td>
               <td>Digital Electronics</td>
           </tr>
            <tr>
               <td>02</td>
               <td>19AI304</td>
               <td>Fundamental of C programming</td>
           </tr> <tr>
               <td>03</td>
               <td>19AI414</td>
               <td>Fundamentals of web</td>
           </tr>
            <tr>
               <td>04</td>
               <td>19CS406</td>
               <td>Computer Networks</td>
           </tr>
             <tr>
               <td>05</td>
               <td>19MA211</td>
               <td>statistics</td>
           </tr>
            <tr>
               <td>06</td>
               <td>19MA222</td>
               <td>Probability</td>
           </tr>
            <tr>
               <td>07</td>
               <td>19EY702</td>
               <td>CREATIVE Skill</td>
           </tr>
            <tr>
               <td>08</td>
               <td>19AI303</td>
               <td>EMPD</td>
           </tr>
          
</body>
</html>0

## OUTPUT


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
