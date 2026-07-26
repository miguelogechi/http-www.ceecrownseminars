# http-www.ceecrownseminars
Words have the power to inspire, influence, heal, and transform lives.
The Power of Speech is an insightful seminar designed to help participants understand the impact of effective communication in personal relationships, leadership, business, education, and everyday life.
Through practical lessons and engaging discussions, attendees will learn how to communicate with confidence, speak with purpose, and use their words to create positive change.
Whether you are a student, professional, entrepreneur, leader, or anyone seeking to improve communication skills, this seminar will equip you with practical tools to make your voice count.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Power of Speech 2026</title>

    <link rel="stylesheet" href="css/style.css">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
</head>

<body>

<header>

    <div class="logo">
        <img src="images/logo.png" alt="CEE-CROWN Logo">
    </div>

    <nav>
        <a href="index.html">Home</a>
        <a href="register.html">Register</a>
        <a href="#speakers">Speakers</a>
        <a href="#contact">Contact</a>
    </nav>

</header>


<section class="hero">

<h1>THE POWER OF SPEECH</h1>

<h2>Your Voice Is Your Greatest Asset</h2>

<p>
Organized by
<strong>CEE-CROWN EDUCOM SERVICES LIMITED</strong>
</p>

<a href="register.html" class="button">
Register Now
</a>

</section>


<section class="event">

<h2>Event Details</h2>

<p><strong>Date:</strong> 9 September 2026</p>

<p><strong>Time:</strong> 10:00 AM</p>

<p><strong>Venue:</strong><br>

CEE-CROWN EDUCOM SERVICES LIMITED Office

</p>

<p><strong>Registration Fee</strong></p>

<ul>

<li>Early Bird (First 10): ₦3,500</li>

<li>Regular: ₦4,000</li>

</ul>

</section>


<section class="countdown">

<h2>Countdown To Seminar</h2>

<div id="timer">

00 Days :
00 Hours :
00 Minutes :
00 Seconds

</div>

</section>


<section class="seats">

<h2>Available Seats</h2>

<h1>50</h1>

<p>Only 50 seats are available.</p>

</section>


<section class="early">

<h2>Early Bird</h2>

<h1>10 Slots Remaining</h1>

<p>Register early and pay only ₦3,500.</p>

</section>


<section id="speakers">

<h2>Speakers</h2>

<div class="speaker">

<h3>Mr. Celestine Chibudo Ekpo</h3>

<p>Guest Speaker</p>

</div>

<div class="speaker">

<h3>Mr. Nasir Olarenwaju</h3>

<p>Guest Speaker</p>

</div>

</section>


<section class="about">

<h2>About The Seminar</h2>

<p>

Words have the power to inspire,
influence,
heal
and transform lives.

The Power of Speech is an insightful seminar designed to help participants understand the impact of effective communication in personal relationships,
leadership,
business,
education
and everyday life.

</p>

</section>


<section class="buttons">

<a href="register.html" class="button">

Register Now

</a>

<a href="verify-payment.html" class="button">

Verify My Payment

</a>

</section>


<footer id="contact">

<h2>Contact Us</h2>

<p>

Phone:
07064445199

</p>

<p>

Email:
Ceecrownedu@gmail.com

</p>

<p>

Speaking in the Right Way

</p>

<p>

© 2026 CEE-CROWN EDUCOM SERVICES LIMITED

</p>

</footer>

<script src="js/countdown.js"></script>

</body>

</html>
/* ==========================
   THE POWER OF SPEECH 2026
   CEE-CROWN EDUCOM SERVICES LIMITED
========================== */

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Poppins',sans-serif;
    background:#f5f7fa;
    color:#333;
    line-height:1.6;
}

/* Header */

header{
    display:flex;
    justify-content:space-between;
    align-items:center;
    background:#0B4F6C;
    padding:15px 40px;
    position:sticky;
    top:0;
    z-index:1000;
}

.logo img{
    width:70px;
}

nav a{
    color:#fff;
    text-decoration:none;
    margin-left:20px;
    font-weight:600;
}

nav a:hover{
    color:#FFD700;
}

/* Hero */

.hero{
    background:linear-gradient(rgba(11,79,108,.8),
                rgba(11,79,108,.8)),
                url("../images/flyer.jpg");
    background-size:cover;
    background-position:center;
    color:white;
    text-align:center;
    padding:100px 20px;
}

.hero h1{
    font-size:52px;
    margin-bottom:20px;
}

.hero h2{
    font-size:28px;
    color:#FFD700;
    margin-bottom:20px;
}

.hero p{
    font-size:20px;
    margin-bottom:30px;
}

/* Button */

.button{
    display:inline-block;
    background:#FFD700;
    color:#000;
    text-decoration:none;
    padding:15px 35px;
    border-radius:40px;
    font-weight:bold;
    transition:.3s;
}

.button:hover{
    background:#fff;
    transform:translateY(-3px);
}

/* Sections */

section{
    padding:70px 10%;
}

section h2{
    text-align:center;
    margin-bottom:30px;
    color:#0B4F6C;
}

/* Event */

.event{
    background:white;
}

.event ul{
    margin-top:15px;
    padding-left:20px;
}

/* Countdown */

.countdown{
    background:#0B4F6C;
    color:white;
    text-align:center;
}

#timer{
    font-size:40px;
    font-weight:bold;
    margin-top:25px;
}

/* Seats */

.seats{
    text-align:center;
}

.seats h1{
    font-size:70px;
    color:green;
}

/* Early Bird */

.early{
    background:#fff8dc;
    text-align:center;
}

.early h1{
    font-size:50px;
    color:#d35400;
}

/* Speakers */

#speakers{
    background:white;
}

.speaker{
    background:#f2f2f2;
    margin:20px auto;
    padding:25px;
    border-radius:10px;
    max-width:700px;
    text-align:center;
}

/* About */

.about{
    background:#eef4f8;
    text-align:center;
}

/* Buttons */

.buttons{
    text-align:center;
}

.buttons .button{
    margin:10px;
}

/* Footer */

footer{
    background:#0B4F6C;
    color:white;
    text-align:center;
    padding:50px 20px;
}

/* Mobile */

@media(max-width:768px){

header{
    flex-direction:column;
}

nav{
    margin-top:15px;
}

nav a{
    display:block;
    margin:10px 0;
}

.hero h1{
    font-size:36px;
}

.hero h2{
    font-size:22px;
}

#timer{
    font-size:28px;
}

.seats h1{
    font-size:50px;
}

.early h1{
    font-size:36px;
}

}
// =====================================
// THE POWER OF SPEECH 2026
// Countdown Timer
// =====================================

// Event Date
const eventDate = new Date("September 9, 2026 10:00:00").getTime();

// Update every second
const timer = setInterval(function () {

    const now = new Date().getTime();

    const distance = eventDate - now;

    // Time calculations
    const days = Math.floor(distance / (1000 * 60 * 60 * 24));

    const hours = Math.floor(
        (distance % (1000 * 60 * 60 * 24)) /
        (1000 * 60 * 60)
    );

    const minutes = Math.floor(
        (distance % (1000 * 60 * 60)) /
        (1000 * 60)
    );

    const seconds = Math.floor(
        (distance % (1000 * 60)) / 1000
    );

    // Display countdown
    document.getElementById("timer").innerHTML =
        days + " Days : " +
        hours + " Hours : " +
        minutes + " Minutes : " +
        seconds + " Seconds";

    // When seminar starts
    if (distance < 0) {

        clearInterval(timer);

        document.getElementById("timer").innerHTML =
        "THE SEMINAR HAS STARTED";

    }

}, 1000);
<h1 id="seatCounter">50</h1>
<h1>10 Slots Remaining</h1>
<h1 id="earlyBirdCounter">10 Slots Remaining</h1>
// ====================================
// Seat Counter
// ====================================

// Total Seats
let totalSeats = 50;

// Registered Participants
let registered = 0;

// Early Bird Slots
let earlyBird = 10;

// Update display
function updateSeats(){

    document.getElementById("seatCounter").innerHTML =
        totalSeats - registered;

    document.getElementById("earlyBirdCounter").innerHTML =
        earlyBird + " Slots Remaining";

}

// Example Registration
function registerParticipant(){

    if(registered < totalSeats){

        registered++;

        if(earlyBird > 0){
            earlyBird--;
        }

        updateSeats();

    }

}

updateSeats();
<script src="js/seats.js"></script>
