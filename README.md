# Ex09 Event Registration Web Application
# Date:
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
## Home
~~~

<div style="margin: 30px auto; width: 375px; height: 667px; background: #111111 url('background.jpg') center/cover no-repeat; border: 12px solid #222222; border-radius: 40px; box-shadow: 0 10px 25px rgba(0,0,0,0.8); overflow: hidden; box-sizing: border-box; font-family: Arial, sans-serif; text-align: center; color: #ffffff;">
    <div style="width: 120px; height: 18px; background: #222222; margin: 0 auto; border-bottom-left-radius: 10px; border-bottom-right-radius: 10px;"></div>
    <img style="width: 100%; height: 50px; object-fit: contain; background: #ffffff; margin-top: 5px;" src="saveetha_banner.png" alt="College Banner">
    <div style="padding: 20px 15px;">
        <img style="width: 80px; height: auto; margin: 15px 0;" src="event_logo.jpg" alt="Event Emblem">
        <div style="font-size: 19px; font-weight: bold; color: #ffffff; margin: 10px 0;">ANNUAL ATHLETIC MEET</div>
        <div style="width: 85%; padding: 12px; margin: 15px auto; background-color: #e6004c; color: #ffffff; border-radius: 6px; font-size: 15px; font-weight: bold; cursor: pointer;">USER LOGIN</div>
        <div style="width: 85%; padding: 12px; margin: 15px auto; background-color: #e6004c; color: #ffffff; border-radius: 6px; font-size: 15px; font-weight: bold; cursor: pointer;">NEW REGISTRATION</div>
        <div style="font-size: 13px; margin-top: 25px; color: #cccccc; font-weight: 600;">STRICTLY SECURE YOUR SPOT</div>
    </div>
</div>
~~~
## Event
~~~

<div style="margin: 30px auto; width: 375px; height: 667px; background: #111111 url('background.jpg') center/cover no-repeat; border: 12px solid #222222; border-radius: 40px; box-shadow: 0 10px 25px rgba(0,0,0,0.8); overflow: hidden; box-sizing: border-box; font-family: Arial, sans-serif; text-align: center; color: #ffffff;">
    <div style="width: 120px; height: 18px; background: #222222; margin: 0 auto; border-bottom-left-radius: 10px; border-bottom-right-radius: 10px;"></div>
    <img style="width: 100%; height: 50px; object-fit: contain; background: #ffffff; margin-top: 5px;" src="saveetha_banner.png" alt="College Banner">
    <div style="padding: 15px;">
        <div style="font-size: 18px; font-weight: bold; color: #ffffff; margin: 10px 0 15px 0;">AVAILABLE SPORTS DISCIPLINES</div>
        <div style="text-align: left; font-size: 14px; font-weight: 600; color: #dddddd; margin: 0 40px; line-height: 1.8;">
            1. CRICKET MATCH<br>
            2. FOOTBALL TOURNAMENT<br>
            3. VOLLEYBALL LEAGUE<br>
            4. BASKETBALL CUP<br>
            5. 4x100M RELAY RACE<br>
            6. BADMINTON SINGLES<br>
            7. 100M DASH<br>
            8. 400M SPRINT<br>
            9. FIELD HOCKEY<br>
            10. LAWN TENNIS
        </div>
        <img src="sports_image.png" alt="Sports Gear" style="width: 100px; height: auto; margin-top: 15px;">
    </div>
</div>
~~~
## Register
~~~

<div style="margin: 30px auto; width: 375px; height: 667px; background: #111111 url('background.jpg') center/cover no-repeat; border: 12px solid #222222; border-radius: 40px; box-shadow: 0 10px 25px rgba(0,0,0,0.8); overflow: hidden; box-sizing: border-box; font-family: Arial, sans-serif; text-align: center; color: #ffffff;">
    <div style="width: 120px; height: 18px; background: #222222; margin: 0 auto; border-bottom-left-radius: 10px; border-bottom-right-radius: 10px;"></div>
    <img style="width: 100%; height: 50px; object-fit: contain; background: #ffffff; margin-top: 5px;" src="saveetha_banner.png" alt="College Banner">
    <div style="padding: 10px 15px;">
        <div style="font-size: 17px; font-weight: bold; color: #ffffff; margin-bottom: 8px;">CANDIDATE REGISTRATION</div>
        <div style="background-color: rgba(255, 255, 255, 0.85); border: 1px solid #bbb; border-radius: 4px; padding: 6px; width: 85%; margin: 4px auto; text-align: left; color: #333; font-size: 12px;">Applicant Name</div>
        <div style="background-color: rgba(255, 255, 255, 0.85); border: 1px solid #bbb; border-radius: 4px; padding: 6px; width: 85%; margin: 4px auto; text-align: left; color: #333; font-size: 12px;">Candidate Age</div>
        <div style="background-color: rgba(255, 255, 255, 0.85); border: 1px solid #bbb; border-radius: 4px; padding: 6px; width: 85%; margin: 4px auto; text-align: left; color: #333; font-size: 12px;">Gender Category</div>
        <div style="background-color: rgba(255, 255, 255, 0.85); border: 1px solid #bbb; border-radius: 4px; padding: 6px; width: 85%; margin: 4px auto; text-align: left; color: #333; font-size: 12px;">Roll / Reg Number</div>
        <div style="background-color: rgba(255, 255, 255, 0.85); border: 1px solid #bbb; border-radius: 4px; padding: 6px; width: 85%; margin: 4px auto; text-align: left; color: #333; font-size: 12px;">Academic Branch</div>
        <div style="background-color: rgba(255, 255, 255, 0.85); border: 1px solid #bbb; border-radius: 4px; padding: 6px; width: 85%; margin: 4px auto; text-align: left; color: #333; font-size: 12px;">Mobile Contact</div>
        <div style="background-color: rgba(255, 255, 255, 0.85); border: 1px solid #bbb; border-radius: 4px; padding: 6px; width: 85%; margin: 4px auto; text-align: left; color: #333; font-size: 12px;">Email Address</div>
        <div style="background-color: rgba(255, 255, 255, 0.85); border: 1px solid #bbb; border-radius: 4px; padding: 6px; width: 85%; margin: 4px auto; text-align: left; color: #333; font-size: 12px;">Selected Sport</div>
        <div style="background-color: #e6004c; color: #ffffff; padding: 8px; width: 85%; margin: 10px auto 0 auto; border-radius: 5px; font-size: 14px; font-weight: bold; cursor: pointer;">SUBMIT APPLICATION</div>
    </div>
~~~
## Contact
~~~
<!-- CONTACT US PAGE (contact.html) -->
<div style="margin: 30px auto; width: 375px; height: 667px; background: #111111 url('background.jpg') center/cover no-repeat; border: 12px solid #222222; border-radius: 40px; box-shadow: 0 10px 25px rgba(0,0,0,0.8); overflow: hidden; box-sizing: border-box; font-family: Arial, sans-serif; text-align: center; color: #ffffff;">
    <div style="width: 120px; height: 18px; background: #222222; margin: 0 auto; border-bottom-left-radius: 10px; border-bottom-right-radius: 10px;"></div>
    <img style="width: 100%; height: 50px; object-fit: contain; background: #ffffff; margin-top: 5px;" src="saveetha_banner.png" alt="College Banner">
    <div style="padding: 20px 15px;">
        <div style="font-size: 24px; color: #ffffff; font-weight: bold; margin-top: 25px; margin-bottom: 15px;">ACKNOWLEDGEMENT</div>
        <div style="font-size: 14px; color: #dddddd; margin-bottom: 30px; line-height: 1.5; font-weight: 600;">We look forward to seeing<br> your active involvement in <br> the upcoming sports events.</div>
        <div style="font-size: 18px; font-weight: bold; color: #00ff66; margin-top: 25px;">Help & Enquiries</div>
        <div style="font-size: 13px; color: #eeeeee; margin-top: 10px;">Official Email<br>SaveethaEngineeringCollege@gmail.com</div>
        <div style="font-size: 13px; color: #eeeeee; margin-top: 15px;">Desk Numbers<br>8249763553<br>9878964646</div>
    </div>
</div>
~~~
# OUTPUT:
## Home

![alt text](image.png)

## Event

![alt text](image-1.png)

## Register

![alt text](image-2.png)

## Contact

![alt text](image-3.png)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
