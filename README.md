# Ex09 Event Registration Web Application
# Date: 27.05.2026
# AIM:
To design, develop and deploy a web application for event registration. 

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:

```
HOME PAGE 

<div style="width: 360px; height: 800px; position: relative; background: #FFF1E6; overflow: hidden;">
  <img style="width: 360px; height: 800px; left: 0px; top: 0px; position: absolute; object-fit: cover;" src="https://placeholder.com" alt="Cultural Festival Background" />
  <div style="width: 300px; height: 150px; left: 30px; top: 80px; position: absolute; text-align: center;">
    <div style="color: #E63946; font-size: 36px; font-family: 'Arial Black', sans-serif; font-weight: 900; letter-spacing: 2px; text-transform: uppercase;">Cultural</div>
    <div style="color: #1D3557; font-size: 36px; font-family: 'Arial Black', sans-serif; font-weight: 900; letter-spacing: 2px; text-transform: uppercase; margin-top: -5px;">Festival</div>
  </div>
  <div style="width: 150px; height: 45px; left: 105px; top: 410px; position: absolute; background: #D84B76; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25); border-radius: 4px; display: flex; align-items: center; justify-content: center;">
    <div style="color: white; font-size: 20px; font-family: 'Georgia', serif; font-weight: bold; letter-spacing: 1px; text-transform: uppercase;">Login</div>
  </div>
  <div style="width: 220px; height: 85px; left: 70px; top: 480px; position: absolute; background: #803254; border: 1px solid #5A1F39; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25); display: flex; align-items: center; justify-content: center;">
    <div style="color: white; font-size: 26px; font-family: 'Georgia', serif; font-weight: normal; letter-spacing: 2px; text-transform: uppercase;">Register</div>
  </div>
  <div style="width: 360px; height: 160px; left: 0px; top: 640px; position: absolute; background: linear-gradient(transparent, rgba(0,0,0,0.7)); display: flex; align-items: flex-end;">
    <!-- You can replace this placeholder div with an actual SVG/PNG silhouette of the crowd -->
  </div>
</div>
```

```
LIST OF EVENTS PAGE

<div style="width: 360px; height: 800px; position: relative; background: #FFF5F5; overflow: hidden;">
  <!-- Background Image Placeholder (Clouds and Gradient) -->
  <img style="width: 360px; height: 800px; left: 0px; top: 0px; position: absolute; object-fit: cover;" src="https://placeholder.com" alt="Events Background" />
  <div style="width: 320px; left: 20px; top: 65px; position: absolute; color: #D6336C; font-size: 26px; font-family: 'Georgia', serif; font-weight: 900; letter-spacing: 1px; text-transform: uppercase;">
    List of Events :
  </div>
  <div style="width: 320px; left: 45px; top: 190px; position: absolute; display: flex; align-items: flex-start;">
    <div style="color: #E63946; font-size: 28px; margin-right: 15px; margin-top: -2px;">★</div>
    <div style="color: #5C1D36; font-size: 24px; font-family: 'Georgia', serif; font-weight: bold; line-height: 1.2;">
      Painting<br/>Competition
    </div>
  </div>
  <div style="width: 320px; left: 45px; top: 325px; position: absolute; display: flex; align-items: flex-start;">
    <div style="color: #E63946; font-size: 28px; margin-right: 15px; margin-top: -2px;">★</div>
    <div style="color: #5C1D36; font-size: 24px; font-family: 'Georgia', serif; font-weight: bold; line-height: 1.2;">
      Solo Singing<br/>Competition
    </div>
  </div>
  <div style="width: 320px; left: 45px; top: 460px; position: absolute; display: flex; align-items: flex-start;">
    <div style="color: #E63946; font-size: 28px; margin-right: 15px; margin-top: -2px;">★</div>
    <div style="color: #5C1D36; font-size: 24px; font-family: 'Georgia', serif; font-weight: bold; line-height: 1.2;">
      Classical<br/>Dance<br/>Performance
    </div>
  </div>
  <div style="width: 360px; height: 160px; left: 0px; top: 640px; position: absolute;">
  </div>
</div>
```

```
REGISTRATION PAGE 

<div style="width: 360px; height: 800px; position: relative; background: #C5B4E3; overflow: hidden;">
  <div style="width: 320px; left: 20px; top: 50px; position: absolute; color: #2C1A4D; font-size: 24px; font-family: 'Georgia', serif; font-weight: 900; letter-spacing: 1px; text-transform: uppercase; text-align: center;">
    Registration Form
  </div>
  <div style="width: 320px; height: 40px; left: 20px; top: 115px; position: absolute; background: #E2D9F3; box-shadow: inset 0px 2px 4px rgba(0,0,0,0.1); border-radius: 2px; display: flex; align-items: center; padding-left: 10px; box-sizing: border-box;">
    <div style="color: #4A2E80; font-size: 16px; font-family: 'Georgia', serif; font-weight: bold; text-transform: uppercase;">Name :</div>
  </div>
  <div style="width: 320px; height: 40px; left: 20px; top: 170px; position: absolute; background: #E2D9F3; box-shadow: inset 0px 2px 4px rgba(0,0,0,0.1); border-radius: 2px; display: flex; align-items: center; padding-left: 10px; box-sizing: border-box;">
    <div style="color: #4A2E80; font-size: 16px; font-family: 'Georgia', serif; font-weight: bold; text-transform: uppercase;">Reg No :</div>
  </div>
  <div style="width: 320px; height: 40px; left: 20px; top: 225px; position: absolute; background: #E2D9F3; box-shadow: inset 0px 2px 4px rgba(0,0,0,0.1); border-radius: 2px; display: flex; align-items: center; padding-left: 10px; box-sizing: border-box;">
    <div style="color: #4A2E80; font-size: 16px; font-family: 'Georgia', serif; font-weight: bold; text-transform: uppercase;">Gender :</div>
  </div>
  <div style="width: 320px; height: 40px; left: 20px; top: 295px; position: absolute; background: #B4A0E6; box-shadow: inset 0px 2px 4px rgba(0,0,0,0.1); border-radius: 2px; display: flex; align-items: center; padding-left: 10px; box-sizing: border-box;">
    <div style="color: #4A2E80; font-size: 16px; font-family: 'Georgia', serif; font-weight: bold; text-transform: uppercase;">Mob No :</div>
  </div>
  <div style="width: 320px; height: 40px; left: 20px; top: 350px; position: absolute; background: #B4A0E6; box-shadow: inset 0px 2px 4px rgba(0,0,0,0.1); border-radius: 2px; display: flex; align-items: center; padding-left: 10px; box-sizing: border-box;">
    <div style="color: #4A2E80; font-size: 16px; font-family: 'Georgia', serif; font-weight: bold; text-transform: uppercase;">Email Id :</div>
  </div>
  <div style="width: 320px; height: 40px; left: 20px; top: 415px; position: absolute; background: #967BB6; box-shadow: inset 0px 2px 4px rgba(0,0,0,0.15); border-radius: 2px; display: flex; align-items: center; padding-left: 10px; box-sizing: border-box;">
    <div style="color: #2C1A4D; font-size: 16px; font-family: 'Georgia', serif; font-weight: bold; text-transform: uppercase;">Event To Reg :</div>
  </div>
</div>
```

```
CONTACT US PAGE 

<div style="width: 360px; height: 800px; position: relative; background: #E0F2F1; overflow: hidden;">
  <div style="width: 320px; height: 160px; left: 20px; top: 160px; position: absolute; display: flex; flex-direction: column; align-items: center; justify-content: center;">
    <div style="color: #FF7043; font-size: 54px; font-family: 'Brush Script MT', cursive, sans-serif; font-weight: bold; line-height: 1;">thank</div>
    <div style="color: #26A69A; font-size: 54px; font-family: 'Brush Script MT', cursive, sans-serif; font-weight: bold; line-height: 1; margin-top: -10px;">you</div>
  </div>
  <div style="width: 320px; left: 20px; top: 350px; position: absolute; color: #004D40; font-size: 22px; font-family: 'Georgia', serif; font-weight: bold; text-align: center; line-height: 1.4;">
    We are excited to welcome you to the event
  </div>
  <div style="width: 320px; left: 20px; top: 520px; position: absolute; color: #004D40; font-size: 22px; font-family: 'Georgia', serif; font-weight: 900; text-transform: uppercase; text-align: center; letter-spacing: 1px;">
    Contact Us
  </div>
  <div style="width: 340px; height: 45px; left: 10px; top: 580px; position: absolute; background: rgba(128, 203, 196, 0.6); display: flex; align-items: center; justify-content: center; backdrop-filter: blur(2px);">
    <div style="color: #004D40; font-size: 18px; font-family: 'Georgia', serif; font-weight: bold; text-transform: uppercase; letter-spacing: 1px;">
      Phone : 1234567890
    </div>
  </div>
</div>
```

# OUTPUT:
![alt text](<Screenshot (112).png>)

![alt text](<Screenshot (113).png>)

![alt text](<Screenshot (114).png>)

![alt text](<Screenshot (115).png>)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
