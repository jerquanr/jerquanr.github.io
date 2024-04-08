<!DOCTYPE html>
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
            background-color: #E0F7FA; /* Very light blue background */
        }
        .centered-content {
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            height: 100vh;
        }
        .centered-content > div, .about-section {
            border: 2px solid #000;
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .about-section {
            display: flex;
            margin: 20px auto 0;
            width: 80%;
            align-items: center;
            position: relative;
            flex-wrap: wrap; /* Allow items to wrap if needed */
        }
        .about-img {
            flex-basis: 40%; /* Adjusts the base size of the image container */
            max-width: 40%;
            position: absolute;
            left: -100px;
        }
        .about-text {
            flex: 1;
            padding-left: 20px;
            margin-left: 45%; /* Increased to widen the gap */
            border: 2px solid #000; /* Extends the border around the text */
            padding: 20px; /* Added padding inside the border */
        }
        /* Style for the confirm button */
        .confirm-btn {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #007BFF;
            color: #FFFFFF;
            text-decoration: none;
            border-radius: 5px;
            cursor: pointer;
        }
        /* Hover effect for button */
        .confirm-btn:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="centered-content">
        <div>
            <h1>Welcome User</h1>
            <p>Welcome to my website. Feel free to look around at my life's achievements and aspirations.</p>
        </div>
    </div>
    <!-- About Section -->
    <div class="about-section">
        <div class="about-img">
            <img src="https://media.licdn.com/dms/image/D4E03AQFQjimbIykhSw/profile-displayphoto-shrink_200_200/0/1699579434374?e=2147483647&v=beta&t=YhfAaccuy1WIWXMbZyzFQBLAybPg8KN2rTa3UrWyKhQ" alt="About Me">
        </div>
        <div class="about-text">
            <p>I'm a cybersecurity practitioner who plays CTFs as a hobby and loves to learn more about cybersecurity. I have a variety of skill sets when it comes to cybersecurity including, Metasploit, Kali Linux, Wireshark, and even Steghide. I am extremely adaptable in many situations and I'm not afraid to try something new. I enrolled at George Mason University with the intended major of BS in Computer Science due to my interest in programming and computers. I then transferred to Old Dominion University where I plan to obtain a BS in Cybersecurity due to my interest in penetration testing and all things CTF.I'm a cybersecurity practitioner who plays CTFs as a hobby and loves to learn more about cybersecurity. I have a variety of skill sets when it comes to cybersecurity including, Metasploit, Kali Linux, Wireshark, and even Steghide. I am extremely adaptable in many situations and I'm not afraid to try something new. I enrolled at George Mason University with the intended major of BS in Computer Science due to my interest in programming and computers. I then transferred to Old Dominion University where I plan to obtain a BS in Cybersecurity due to my interest in penetration testing and all things CTF.</p>
            <!-- Confirm button -->
            <a href="#" class="confirm-btn">Confirm</a>
        </div>
    </div>
</body>
</html>
