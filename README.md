<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
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
        display: flex; /* Using Flexbox for the layout */
        margin: 20px auto 0; /* Adds margin on top and centers horizontally */
        width: 80%; /* Adjust based on preference */
        align-items: center; /* Aligns items vertically center */
        position: relative; /* To position the image absolutely within */
    }
    .about-img {
        flex: 1; /* Takes up 1/2 of the flex container */
        max-width: 50%; /* Limits image container width */
        position: absolute; /* Absolute positioning */
        left: -100px; /* Move to the left by a large margin */
    }
    .about-text {
        flex: 1; /* Takes up the remaining space */
        padding-left: 20px; /* Adds some space between the image and the text */
        margin-left: 50%; /* Ensure text doesn't overlap the image */
    }
    .about-img img {
        width: 100%; /* Makes the image responsive */
        height: auto;
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
            <!-- Placeholder image, replace with your own -->
            <img src="https://media.licdn.com/dms/image/D4E03AQFQjimbIykhSw/profile-displayphoto-shrink_200_200/0/1699579434374?e=2147483647&v=beta&t=YhfAaccuy1WIWXMbZyzFQBLAybPg8KN2rTa3UrWyKhQ" alt="About Me">
        </div>
        <div class="about-text">
            <p>I'm a cybersecurity practitioner who plays CTFs as a hobby and loves to learn more about cybersecurity. I have a variety of skill sets when it comes to cybersecurity including, Metasploit, Kali Linux, Wireshark, and even Steghide. I am extremely adaptable in many situations and I'm not afraid to try something new. I enrolled at George Mason University with the intended major of BS in Computer Science due to my interest in programming and computers. I then transferred to Old Dominion University where I plan to obtain a BS in Cybersecurity due to my interest in penetration testing and all things CTF.I'm a cybersecurity practitioner who plays CTFs as a hobby and loves to learn more about cybersecurity. I have a variety of skill sets when it comes to cybersecurity including, Metasploit, Kali Linux, Wireshark, and even Steghide. I am extremely adaptable in many situations and I'm not afraid to try something new. I enrolled at George Mason University with the intended major of BS in Computer Science due to my interest in programming and computers. I then transferred to Old Dominion University where I plan to obtain a BS in Cybersecurity due to my interest in penetration testing and all things CTF.</p>
        </div>
    </div>
</body>
</html>
