# Ex09 Event Registration Web Application
## Date:15/10/2025

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

## DESIGN TOOL:
Figma

## CODE:
page1 html:
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sports Day Events - Saveetha Engineering College</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<div class="container">
    <div class="header">
        <h2 class="college-name">
            <span class="blue">SAVEETHA</span> 
            <span class="red">AUTONOMOUS</span><br>
            ENGINEERING COLLEGE
        </h2>
        <p class="subtext">Approved by AICTE | Affiliated to Anna University</p>
        <div class="tnea">TNEA CODE<br><span>1216</span></div>
    </div>

    <h2 class="event-title">SPORTS DAY EVENTS</h2>

    <div class="logo">
        <img src="https://www.saveetha.ac.in/images/sec-logo.png" alt="College Logo">
    </div>

    <div class="buttons">
        <button class="btn login">LOGIN</button>
        <button class="btn register">REGISTER</button>
    </div>

    <div class="track">
        <img src="https://img.freepik.com/free-vector/athletics-track-running-background_1017-17687.jpg" alt="Track Background">
    </div>
</div>

</body>
</html>
page2 css:
body {
    font-family: Arial, sans-serif;
    text-align: center;
    background: linear-gradient(to bottom, #ffffff, #cce5ff);
    margin: 0;
    padding: 0;
}

.container {
    width: 356px;
    height: 512px;
    margin: 20px auto;
    border: 2px solid #ccc;
    border-radius: 8px;
    background-color: #fff;
    overflow: hidden;
    position: relative;
}

.header {
    padding: 10px;
    position: relative;
}

.college-name {
    font-size: 18px;
    font-weight: bold;
    margin: 0;
    line-height: 1.2;
}

.blue {
    color: #0072bc;
}

.red {
    color: #e60000;
}

.subtext {
    font-size: 10px;
    color: #333;
    margin-top: 5px;
}

.tnea {
    position: absolute;
    top: 5px;
    right: 10px;
    background-color: #0a1c75;
    color: white;
    font-size: 10px;
    font-weight: bold;
    border-radius: 4px;
    padding: 5px;
    width: 60px;
}

.tnea span {
    font-size: 20px;
    display: block;
}

.event-title {
    margin-top: 10px;
    font-weight: bold;
    color: black;
}

.logo img {
    width: 120px;
    height: auto;
    margin: 10px 0;
}

.buttons {
    margin-top: 15px;
}

.btn {
    display: block;
    width: 60%;
    margin: 10px auto;
    padding: 10px;
    font-size: 18px;
    font-weight: bold;
    border: none;
    cursor: pointer;
}

.login {
    background-color: #00ff00;
    color: red;
}

.register {
    background-color: #ffff00;
    color: green;
}

.track img {
    width: 100%;
    height: auto;
    position: absolute;
    bottom: 0;
    left: 0;
}
page2 html:
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sports Day Events</title>
<link rel="stylesheet" href="sports.css">
</head>
<body>

<div class="poster">
    <h2 class="title">SPORTS DAY EVENTS</h2>
    <ul class="events">
        <li><em>*BASKETBALL</em></li>
        <li><em>*CRICKET</em></li>
        <li><em>*KABADDI</em></li>
        <li><em>*KHO-KHO</em></li>
        <li><em>*VOLLEYBALL</em></li>
    </ul>

    <img src="https://pngimg.com/uploads/football/football_PNG52795.png" alt="Football" class="football">
</div>

</body>
</html>
page4 css:
body {
    margin: 0;
    padding: 0;
    background-color: #c8f7c5;
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.poster {
    width: 373px;
    height: 512px;
    background: linear-gradient(135deg, #5bbf3a, #b5f28a);
    border: 4px solid #0d6600;
    border-radius: 10px;
    position: relative;
    text-align: center;
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.3);
    background-image: linear-gradient(135deg, #a5f28a 30%, #5abf3a 100%);
}

.title {
    margin-top: 40px;
    color: black;
    font-weight: bold;
    font-size: 20px;
}

.events {
    list-style: none;
    padding: 0;
    margin-top: 30px;
    color: #ff4ee0;
    font-size: 20px;
    text-align: left;
    width: 200px;
    margin-left: auto;
    margin-right: auto;
    line-height: 2;
    font-style: italic;
}

.football {
    width: 100px;
    position: absolute;
    bottom: 20px;
    left: 30px;
}
page3 html:
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Event Registration Form</title>
<link rel="stylesheet" href="register.css">
</head>
<body>

<div class="form-container">
    <h2 class="title">EVENT REGISTRATION FORM</h2>

    <form class="event-form">
        <input type="text" placeholder="NAME" required>
        <input type="number" placeholder="AGE" required>
        <input type="text" placeholder="REG NO" required>
        <input type="text" placeholder="DEPT" required>
        <input type="tel" placeholder="MOB NO" required>
        <button type="submit" class="register-btn">REGISTER</button>
    </form>
</div>

</body>
</html>
page3 css:
body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    background-image: url('https://img.freepik.com/free-vector/blue-soccer-football-background-with-hexagon-pattern_1017-44034.jpg');
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.form-container {
    width: 361px;
    height: 512px;
    background-color: rgba(0, 0, 50, 0.3);
    border-radius: 10px;
    text-align: center;
    padding: 20px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.4);
}

.title {
    color: #00ff00;
    font-size: 18px;
    font-weight: bold;
    margin-bottom: 30px;
}

.event-form input {
    display: block;
    width: 80%;
    margin: 10px auto;
    padding: 10px;
    border: none;
    border-radius: 4px;
    font-size: 16px;
    text-align: center;
}

.event-form input::placeholder {
    font-weight: bold;
    color: black;
}

.register-btn {
    background-color: #00ff00;
    color: red;
    border: none;
    border-radius: 5px;
    padding: 12px 20px;
    margin-top: 20px;
    width: 60%;
    font-size: 18px;
    font-weight: bold;
    cursor: pointer;
    transition: 0.3s;
}

.register-btn:hover {
    background-color: #00cc00;
}
page4 html:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Saveetha Engineering College Sports Event</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="poster">
    <header>
      <img src="college-logo.png" alt="Saveetha Engineering College Logo" class="logo">
      <div class="college-info">
        <h1>SAVEETHA ENGINEERING COLLEGE (AUTONOMOUS)</h1>
        <p>Approved by AICTE | Affiliated to Anna University</p>
      </div>
      <div class="tnea-code">TNEA Code: <span>1216</span></div>
    </header>

    <main>
      <h2>THANK YOU</h2>
      <p>We are anticipating your participation<br>in the upcoming sports events</p>
    </main>

    <footer>
      <h3>Contact Us</h3>
      <p>Email: <a href="mailto:eventsec@gmail.com">eventsec@gmail.com</a></p>
    </footer>
  </div>
</body>
</html>
page4 css:
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: linear-gradient(to bottom right, #f0f8ff, #dbe9ff);
  color: #333;
}

.poster {
  max-width: 800px;
  margin: 40px auto;
  padding: 30px;
  background: white;
  border-radius: 12px;
  box-shadow: 0 0 20px rgba(0,0,0,0.1);
  text-align: center;
}

header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  border-bottom: 2px solid #ccc;
  padding-bottom: 20px;
}

.logo {
  height: 80px;
}

.college-info h1 {
  font-size: 1.5em;
  margin: 0;
}

.college-info p {
  font-size: 0.9em;
  color: #555;
}

.tnea-code {
  background-color: #007bff;
  color: white;
  padding: 10px 15px;
  border-radius: 8px;
  font-weight: bold;
}

main h2 {
  font-size: 2em;
  margin-top: 40px;
  color: #007bff;
}

main p {
  font-size: 1.2em;
  margin-top: 10px;
}

footer {
  margin-top: 40px;
  border-top: 1px solid #ccc;
  padding-top: 20px;
}

footer h3 {
  margin-bottom: 10px;
}

footer a {
  color: #007bff;
  text-decoration: none;
}




## OUTPUT:
<img width="1920" height="1080" alt="Screenshot (65)" src="https://github.com/user-attachments/assets/0c073c09-b87f-46f8-ab18-f30c8d4cade0" />


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
