# Ex09 Event Registration Web Application
## Date:28.05.2026

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.


## CODE:

index.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Event Registration</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="container page1">

    <div class="header">
        <img src="logo.png" class="logo">

        <div class="college">
            <h2>SAVEETHA<br>ENGINEERING COLLEGE</h2>
            <p>AFFILIATED TO <b>ANNA UNIVERSITY</b></p>
        </div>

        <div class="auto">AUTONOMOUS</div>
    </div>

    <h2 class="welcome">WELCOME TO THE EVENT</h2>

    <button class="btn">REGISTER</button>

    <img src="event.png" class="event-img">

</div>

</body>
</html>
```
style.css
```
body{
    margin:0;
    padding:0;
    font-family:Arial;
    background:#e5e5e5;
}

.container{
    width:300px;
    height:640px;
    margin:20px auto;
    position:relative;
    padding:10px;
}

.page1{
    background:gold;
}

.header{
    display:flex;
    align-items:center;
}

.logo{
    width:40px;
    height:40px;
}

.college h2{
    font-size:15px;
    color:white;
    margin:0;
}

.college p{
    font-size:8px;
    margin:0;
}

.auto{
    background:red;
    color:white;
    padding:3px 8px;
    font-size:10px;
    margin-left:5px;
}

.welcome{
    text-align:center;
    margin-top:150px;
    font-style:italic;
}

.btn{
    display:block;
    margin:60px auto;
    padding:15px 40px;
    background:lightblue;
    border:none;
    font-size:25px;
    font-weight:bold;
}

.event-img{
    width:190px;
    display:block;
    margin:0 auto;
}
```
Page 2 – Event List
events.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Events</title>
    <link rel="stylesheet" href="events.css">
</head>
<body>

<div class="container page2">

    <div class="header">
        <img src="logo.png" class="logo">

        <div class="college">
            <h2>SAVEETHA<br>ENGINEERING COLLEGE</h2>
            <p>AFFILIATED TO <b>ANNA UNIVERSITY</b></p>
        </div>

        <div class="auto">AUTONOMOUS</div>
    </div>

    <h2 class="title">...LIST OF EVENTS...</h2>

    <ol>
        <li>Industrial Visit</li>
        <li>Hackathon</li>
        <li>Workshop</li>
        <li>Quiz</li>
        <li>Cerebro Quest</li>
        <li>SDG Goals</li>
        <li>Non-Technical Events</li>
        <li>Alumni Talk</li>
    </ol>

</div>

</body>
</html>
```
events.css
```
body{
    background:#e5e5e5;
    font-family:Arial;
}

.container{
    width:300px;
    height:640px;
    background:#b9d8c0;
    margin:20px auto;
    padding:10px;
}

.header{
    display:flex;
    align-items:center;
}

.logo{
    width:40px;
    height:40px;
}

.college h2{
    color:white;
    margin:0;
    font-size:15px;
}

.college p{
    margin:0;
    font-size:8px;
}

.auto{
    background:red;
    color:white;
    padding:3px 8px;
    font-size:10px;
}

.title{
    text-align:center;
    margin-top:120px;
}

ol{
    margin-top:50px;
    color:blue;
    font-weight:bold;
    line-height:40px;
}
```
Page 3 – Registration Form
register.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Register</title>
    <link rel="stylesheet" href="register.css">
</head>
<body>

<div class="container page3">

    <div class="header">
        <img src="logo.png" class="logo">

        <div class="college">
            <h2>SAVEETHA<br>ENGINEERING COLLEGE</h2>
            <p>AFFILIATED TO <b>ANNA UNIVERSITY</b></p>
        </div>

        <div class="auto">AUTONOMOUS</div>
    </div>

    <h1>PERSONAL DETAILS</h1>

    <form>

        <label>FULL NAME</label>
        <input type="text">

        <label>GENDER</label>
        <input type="text">

        <label>AGE</label>
        <input type="number">

        <label>DEPARTMENT</label>
        <input type="text">

        <label>MOBILE.NO</label>
        <input type="text">

        <label>EMAIL.ID</label>
        <input type="email">

        <button type="submit">REGISTER</button>

    </form>

</div>

</body>
</html>
```
register.css
```
body{
    background:#e5e5e5;
    font-family:Arial;
}

.container{
    width:300px;
    height:640px;
    background:#e5c8ea;
    margin:20px auto;
    padding:10px;
}

.header{
    display:flex;
    align-items:center;
}

.logo{
    width:40px;
}

.college h2{
    color:white;
    margin:0;
    font-size:15px;
}

.college p{
    margin:0;
    font-size:8px;
}

.auto{
    background:red;
    color:white;
    padding:3px 8px;
    font-size:10px;
}

h1{
    text-align:center;
    margin-top:40px;
}

form{
    margin-top:40px;
}

label{
    display:block;
    margin-top:20px;
    font-weight:bold;
}

input{
    width:100%;
    padding:10px;
    margin-top:5px;
    border:none;
    background:#9ed0e0;
}

button{
    width:100%;
    padding:10px;
    margin-top:30px;
    background:#cfcfcf;
    border:none;
    font-weight:bold;
}
```
Page 4 – Success Page
success.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Success</title>
    <link rel="stylesheet" href="success.css">
</head>
<body>

<div class="container page4">

    <div class="header">
        <img src="logo.png" class="logo">

        <div class="college">
            <h2>SAVEETHA<br>ENGINEERING COLLEGE</h2>
            <p>AFFILIATED TO <b>ANNA UNIVERSITY</b></p>
        </div>

        <div class="auto">AUTONOMOUS</div>
    </div>

    <div class="tick">✔</div>

    <h1>SUCCESSFULLY<br>REGISTERED</h1>

    <div class="contact">
        <h2>CONTACT US:</h2>
        <p>987654321</p>
    </div>

</div>

</body>
</html>
```
success.css
```
body{
    background:#e5e5e5;
    font-family:Arial;
}

.container{
    width:300px;
    height:640px;
    background:#efc4d1;
    margin:20px auto;
    padding:10px;
    text-align:center;
}

.header{
    display:flex;
    align-items:center;
}

.logo{
    width:40px;
}

.college h2{
    color:white;
    margin:0;
    font-size:15px;
}

.college p{
    margin:0;
    font-size:8px;
}

.auto{
    background:red;
    color:white;
    padding:3px 8px;
    font-size:10px;
}

.tick{
    width:150px;
    height:150px;
    background:green;
    color:white;
    font-size:100px;
    border-radius:50%;
    margin:80px auto 20px;
    line-height:150px;
}

.contact{
    margin-top:100px;
}
```

## OUTPUT:
<img width="1316" height="774" alt="Screenshot 2026-05-28 220921" src="https://github.com/user-attachments/assets/cab38be6-8f17-4542-9dc3-2d42764f263a" />



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
