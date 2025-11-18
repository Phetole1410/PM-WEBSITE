<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README – Paul's Pub & Grill Picnic Site</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 30px;
            background: #f7f7f7;
        }

        h1, h2, h3 {
            color: #333;
        }

        .section {
            background: white;
            padding: 20px;
            margin-bottom: 25px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        code {
            background: #eee;
            padding: 3px 6px;
            border-radius: 4px;
        }
    </style>
</head>

<body>

    <h1>README – Paul's Pub & Grill Picnic Site Website</h1>
    <p>This README file explains the structure, features, and functionality of the website created for <strong>Paul's Pub & Grill Picnic Site</strong>.</p>

    <!-- ABOUT PROJECT -->
    <div class="section">
        <h2>1. Project Overview</h2>
        <p>This website was designed to showcase the services, menu, and reservation options for Paul's Pub & Grill Picnic Site. It includes the following pages:</p>
        <ul>
            <li><strong>Home Page</strong> – Introduction to the picnic site.</li>
            <li><strong>About Us</strong> – History and purpose of the business.</li>
            <li><strong>Menu</strong> – Food and drinks offered, including images.</li>
            <li><strong>Contact Page</strong> – Phone, email, location, and map.</li>
            <li><strong>Reservation Page</strong> – A form for customers to make bookings.</li>
        </ul>
    </div>

    <!-- RESPONSIVE IMAGES -->
    <div class="section">
        <h2>2. Responsive Images & Zoom Feature</h2>
        <p>
            All images on the website were made fully <strong>responsive</strong> using CSS to ensure they adjust smoothly on both mobile and desktop screens.
        </p>
        <p>
            A <strong>click-to-zoom</strong> feature was added using JavaScript. When a user clicks an image, it opens in a larger view on a dark overlay.
        </p>

        <h3>Zoom JavaScript Function Used:</h3>
        <code>
            function zoomImage(img) {<br>
            &nbsp;&nbsp;document.getElementById("zoomedImg").src = img.src;<br>
            &nbsp;&nbsp;document.getElementById("zoomOverlay").style.display = "flex";<br>
            }<br><br>
            function closeZoom() {<br>
            &nbsp;&nbsp;document.getElementById("zoomOverlay").style.display = "none";<br>
            }
        </code>
    </div>

    <!-- CONTACT -->
    <div class="section">
        <h2>3. Contact Page</h2>
        <p>The contact page includes the following information:</p>
        <ul>
            <li><strong>Phone:</strong> 066 079 7579</li>
            <li><strong>Email:</strong> info@paulspubgrill.com</li>
            <li><strong>Location:</strong> Tzaneen, Morapalala Village</li>
            <li>A map image that can be zoomed when clicked.</li>
        </ul>
    </div>

    <!-- RESERVATION -->
    <div class="section">
        <h2>4. Reservation Form</h2>
        <p>The reservation page allows customers to submit booking information. The form includes fields for:</p>
        <ul>
            <li>Name</li>
            <li>Email</li>
            <li>Identity / Passport Number</li>
            <li>Date</li>
            <li>Time</li>
        </ul>
        <p>All fields use <strong>required input validation</strong>.</p>
    </div>

    <!-- MENU -->
    <div class="section">
        <h2>5. Menu Page Details</h2>
        <p>The menu page displays:</p>
        <ul>
            <li>London Beef Plate & Boerewors</li>
            <li>Rose Fries</li>
            <li>London Drinks</li>
            <li>Cathy Braai Chicken</li>
        </ul>
        <p>Each item includes an image and description, and the images are zoomable.</p>
    </div>

    <!-- TECHNOLOGIES -->
    <div class="section">
        <h2>6. Technologies Used</h2>
        <ul>
            <li><strong>HTML5</strong> – Structure of the pages</li>
            <li><strong>CSS3</strong> – Styling and responsiveness</li>
            <li><strong>JavaScript</strong> – Image zoom functionality</li>
        </ul>
    </div>

    <!-- FILE STRUCTURE -->
    <div class="section">
        <h2>7. File Structure</h2>
        <p>Your project should follow a structure similar to:</p>
        <ul>
            <li><code>index.html</code></li>
            <li><code>about us.html</code></li>
            <li><code>menu.html</code></li>
            <li><code>contact.html</code></li>
            <li><code>css/style.css</code></li>
            <li><code>images/</code> (all images stored here)</li>
            <li><code>readme.html</code></li>
        </ul>
    </div>

    <div class="section">
        <h2>8. Credits</h2>
        <p>Website created for <strong>Paul's Pub & Grill Picnic Site</strong>.</p>
        <p>All images and content belong to their respective owners.</p>
    </div>

</body>
</html>