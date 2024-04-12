<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome Page</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            width: 100%;
            background-color: #E0F7FA; /* Base background color remains very light blue */
            overflow-x: hidden; /* Prevents horizontal scroll */
        }
        .centered-content {
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            height: 100vh;
            width: 100%; /* Ensures full viewport width */
            background: linear-gradient(to bottom, #4CAF50 0%, #087F23 100%); /* Transition from light to darker green */
            color: white; /* Making text color white for better contrast */
        }
        .centered-content > div {
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .about-section, .skills-section {
            display: flex;
            margin: 20px auto;
            width: 90%;
            align-items: center;
            position: relative;
            background-color: #311b92; /* Dark bluish-purple */
            color: #FFFFFF; /* White text for readability */
        }
        .about-img {
            flex-basis: 50%;
            max-width: 50%;
        }
        .about-text, .skills-text {
            flex: 1;
            padding-left: 20px;
            font-size: 1.2em;
        }
        .about-img img, .skills-img img {
            width: 100%;
            height: auto;
        }
        /* Navigation Links */
        nav {
            text-align: center;
            background: #E0F7FA; /* Light blue background for the navigation bar */
            padding: 10px 0;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 1000;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        nav a {
            margin: 0 10px;
            text-decoration: none;
            color: #4CAF50; /* Green text to match the Welcome section */
            border: 2px solid;
            padding: 5px 10px;
            border-radius: 5px;
        }
        nav a:hover {
            color: #087F23; /* Darker green on hover */
        }
        nav a:nth-child(1) { border-color: #e91e63; }
        nav a:nth-child(2) { border-color: #9c27b0; }
        nav a:nth-child(3) { border-color: #3f51b5; }
        nav a:nth-child(4) { border-color: #009688; }
        nav a:nth-child(5) { border-color: #ff5722; }
    </style>
</head>
<body>
    <!-- Navigation Links -->
    <nav>
        <a href="#">Welcome</a>
        <a href="#">About</a>
        <a href="#">Skills</a>
        <a href="#">Proficiency</a>
        <a href="#">Contact</a>
    </nav>
    <div class="centered-content">
        <div>
            <h1>Welcome User</h1>
            <p>Welcome to my website. Feel free to look around at my life's achievements and aspirations.</p>
            <a href="#" class="confirm-btn">Confirm</a>
        </div>
    </div>
    <!-- About Section -->
    <div class="about-section">
        <div class="about-img">
            <img src="https://media.licdn.com/dms/image/D4E03AQFQjimbIykhSw/profile-displayphoto-shrink_200_200/0/1699579434374?e=2147483647&v=beta&t=YhfAaccuy1WIWXMbZyzFQBLAybPg8KN2rTa3UrWyKhQ" alt="About Me">
        </div>
        <div class="about-text">
            <p>I'm a cybersecurity practitioner who plays CTFs as a hobby and loves to learn more about cybersecurity. I have a variety of skill sets when it comes to cybersecurity including, Metasploit, Kali Linux, Wireshark, and even Steghide. I am extremely adaptable in many situations and I'm not afraid to try something new. I enrolled at George Mason University with the intended major of BS in Computer Science due to my interest in programming and computers. I then transferred to Old Dominion University where I plan to obtain a BS in Cybersecurity due to my interest in penetration testing and all things CTF.</p>
        </div>
    </div>
    <!-- Skills Section -->
    <div class="skills-section">
        <!-- No text, ready for future content -->
    </div>
</body>
</html>
