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

<!DOCTYPE html>
<html>
<head>
    <title>Event Registration</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="phone">
        <img class="banner" src="saveetha_banner.png" alt="College Banner">

        <img class="logo" src="event_logo.jpg" alt="Event Logo">

        <h2>ANNUAL ATHLETIC MEET</h2>

        <a class="button" href="event.html">VIEW EVENTS</a>
        <a class="button" href="register.html">NEW REGISTRATION</a>
        <a class="button" href="contact.html">CONTACT US</a>

        <p>STRICTLY SECURE YOUR SPOT</p>
    </div>
</body>
</html>
~~~
## Event
~~~

<!DOCTYPE html>
<html>
<head>
    <title>Sports Events</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="phone">
        <img class="banner" src="saveetha_banner.png" alt="College Banner">

        <h2>AVAILABLE SPORTS DISCIPLINES</h2>

        <div class="sports">
            1. Cricket Match<br>
            2. Football Tournament<br>
            3. Volleyball League<br>
            4. Basketball Cup<br>
            5. Relay Race<br>
            6. Badminton<br>
            7. 100M Dash
        </div>

        <img class="logo" src="sports_image.png" alt="Sports Equipment">

        <a class="button" href="index.html">HOME</a>
    </div>
</body>
</html>
~~~
## Register
~~~

<!DOCTYPE html>
<html>
<head>
    <title>Register</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="phone">
        <img class="banner" src="saveetha_banner.png" alt="College Banner">

        <h2>CANDIDATE REGISTRATION</h2>

        <form>
            <input type="text" placeholder="Applicant Name" required>
            <input type="number" placeholder="Candidate Age" required>

            <select required>
                <option value="">Select Gender</option>
                <option>Male</option>
                <option>Female</option>
            </select>

            <input type="text" placeholder="Roll Number" required>
            <input type="text" placeholder="Academic Branch" required>
            <input type="tel" placeholder="Mobile Number" required>
            <input type="email" placeholder="Email Address" required>

            <select required>
                <option value="">Select Sport</option>
                <option>Cricket</option>
                <option>Football</option>
                <option>Badminton</option>
            </select>

            <button class="button" type="submit">SUBMIT APPLICATION</button>
        </form>
    </div>
</body>
</html>
~~~
## Contact
~~~
<!DOCTYPE html>
<html>
<head>
    <title>Contact Us</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="phone">
        <img class="banner" src="saveetha_banner.png" alt="College Banner">

        <h1>ACKNOWLEDGEMENT</h1>

        <p>
            We look forward to seeing your active involvement
            in the upcoming sports events.
        </p>

        <h3>Help & Enquiries</h3>

        <p>
            Official Email<br>
            SaveethaEngineeringCollege@gmail.com
        </p>

        <p>
            Desk Numbers<br>
            8249763553<br>
            9878964646
        </p>

        <a class="button" href="home.html">HOME</a>
    </div>
</body>
</html>
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
