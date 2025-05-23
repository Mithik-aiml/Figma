# Ex09 Event Registration Web Application
## Date:23-05-2025
## Name:G.Mithik jain
## Ref no:212224240087

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
```
Frontpage 
HTML 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Saveetha Engineering College</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <div class="container">
    <div class="header">
      <img src="logo-header.png" alt="Saveetha Engineering College" class="header-logo" />
    </div>
    <div class="logo">
      <img src="college-logo.png" alt="College Logo" />
    </div>
    <div class="buttons">
      <button class="btn">Register</button>
      <p class="or-text">Or</p>
      <button class="btn">Login</button>
    </div>
  </div>
</body>
</html>
CSS
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #58a6d1;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.container {
  text-align: center;
  width: 100%;
  max-width: 400px;
  padding: 20px;
}

.header-logo {
  width: 100%;
  max-width: 400px;
  margin-bottom: 30px;
}

.logo img {
  width: 200px;
  margin: 30px 0;
}

.buttons {
  margin-top: 20px;
}

.btn {
  background-color: white;
  color: black;
  font-weight: bold;
  font-size: 18px;
  padding: 10px 20px;
  margin: 10px 0;
  border: none;
  cursor: pointer;
  width: 200px;
  border-radius: 5px;
}

.or-text {
  font-size: 18px;
  font-weight: bold;
  margin: 10px 0;
}
Cultural Event page
HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Cultural Events</title>
  <link rel="stylesheet" href="cultural-events.css" />
</head>
<body>
  <div class="container">
    <div class="header">
      <div class="title-oval">
        <h1>CULTURAL<br>EVENTS</h1>
      </div>
    </div>
    <ul class="events-list">
      <li>➜ <span>SOLO SINGING</span></li>
      <li>➜ <span>DANCE</span></li>
      <li>➜ <span>MIME</span></li>
      <li>➜ <span>FASHION WALK</span></li>
      <li>➜ <span>DJ</span></li>
      <li>➜ <span>FILM FEST</span></li>
      <li>➜ <span>SOLO DANCING</span></li>
      <li>➜ <span>GAME NIGHTS</span></li>
    </ul>
  </div>
</body>
</html>
CSS
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #58a6d1;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.container {
  width: 100%;
  max-width: 400px;
  text-align: center;
  padding: 20px;
}

.title-oval {
  background-color: white;
  border-radius: 50px;
  padding: 10px 0;
  width: 70%;
  margin: 20px auto;
}

.title-oval h1 {
  margin: 0;
  font-size: 20px;
  font-weight: bold;
  line-height: 1.2;
}

.events-list {
  list-style-type: none;
  padding: 0;
  margin-top: 30px;
  text-align: left;
  padding-left: 20px;
}

.events-list li {
  font-size: 18px;
  color: white;
  margin-bottom: 15px;
  display: flex;
  align-items: center;
  gap: 10px;
  font-style: italic;
}

.events-list span {
  font-weight: 500;
}
Registration form 
HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Registration Form</title>
  <link rel="stylesheet" href="registration-form.css" />
</head>
<body>
  <div class="container">
    <h2>REGISTRATION FORM<br><span>BOOK NOW</span></h2>
    <form>
      <div class="form-group">
        <label for="name">NAME</label>
        <input type="text" id="name" />
      </div>
      <div class="form-group">
        <label for="refno">REF NO</label>
        <input type="text" id="refno" />
      </div>
      <div class="form-group">
        <label for="dept">DEPT</label>
        <input type="text" id="dept" />
      </div>
      <div class="form-group">
        <label for="email">EMAIL ID</label>
        <input type="email" id="email" />
      </div>
      <div class="form-group">
        <label for="phone">PHONE NO</label>
        <input type="tel" id="phone" />
      </div>
      <div class="form-group">
        <label for="age">AGE</label>
        <input type="number" id="age" />
      </div>
    </form>
  </div>
</body>
</html>
CSS
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #58a6d1;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.container {
  width: 100%;
  max-width: 400px;
  padding: 20px;
}

h2 {
  text-align: center;
  font-size: 20px;
  font-weight: bold;
  color: black;
  margin-bottom: 30px;
}

h2 span {
  display: block;
  font-weight: bold;
}

form {
  display: flex;
  flex-direction: column;
  gap: 15px;
}

.form-group {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

label {
  flex: 1;
  font-weight: bold;
  font-size: 16px;
  color: black;
  text-align: left;
}

input {
  flex: 1.5;
  padding: 8px;
  font-size: 16px;
  background-color: #eee;
  border: none;
  border-radius: 4px;
}
Contact page
HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Thank You</title>
  <link rel="stylesheet" href="thank-you.css" />
</head>
<body>
  <div class="header">
    <img src="saveetha-logo.png" alt="College Logo" class="logo"/>
    <div class="header-text">
      <h1>SAVEETHA <span>AUTONOMOUS</span><br>ENGINEERING COLLEGE</h1>
      <h2>AFFILIATED TO ANNA UNIVERSITY</h2>
    </div>
    <div class="code">TNEA CODE<br><strong>1216</strong></div>
  </div>

  <div class="main-message">
    “<strong>THANK YOU</strong> ”
  </div>

  <div class="contact-info">
    <p><strong>FOR FURTHER INFORMATION<br>PLEASE CONTACT<br>9363563757</strong></p>
  </div>
</body>
</html>
CSS
body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  background-color: #58a6d1;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  height: 100vh;
  text-align: center;
}

.header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 95%;
  padding: 10px 20px;
}

.logo {
  height: 50px;
}

.header-text h1 {
  font-size: 14px;
  font-weight: bold;
  color: #000;
  margin: 0;
}

.header-text span {
  background-color: red;
  color: white;
  padding: 0 4px;
  font-size: 10px;
  margin-left: 5px;
}

.header-text h2 {
  font-size: 10px;
  background-color: yellow;
  display: inline-block;
  padding: 2px 5px;
  margin-top: 2px;
}

.code {
  text-align: right;
  font-size: 12px;
  font-weight: bold;
  color: #000;
}

.main-message {
  font-size: 32px;
  font-weight: bold;
  color: black;
  margin-top: 60px;
}

.contact-info {
  font-size: 16px;
  font-weight: bold;
  color: black;
  margin-bottom: 30px;
}
```

## OUTPUT:
![Screenshot 2025-05-22 231156](https://github.com/user-attachments/assets/06f983a1-f786-481f-b5d5-a4ec99d84013)
![Screenshot 2025-05-22 232727](https://github.com/user-attachments/assets/12e97cd9-7b98-4cbb-9862-08cbf29ad871)
![Screenshot 2025-05-22 232742](https://github.com/user-attachments/assets/7512a0a6-fa06-459b-927e-7414226b7c3c)
![Screenshot 2025-05-22 232756](https://github.com/user-attachments/assets/a460642a-e54d-4747-9df4-58a75e5a7610)
![Screenshot 2025-05-22 232809](https://github.com/user-attachments/assets/9f44c636-db0a-4332-a7a0-e1a93db7c474)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
