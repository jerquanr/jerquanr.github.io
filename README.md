<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome Page</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            width: 100%;
            background-color: #E0F7FA; /* Very light blue */
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
            width: 100%;
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
            background: #4CAF50; /* Green background */
            color: white;
        }
        .centered-text {
            width: 100vw;
            position: relative;
        }
        nav a {
            color: #4CAF50; /* Green text for navigation */
            border: 1px solid randomColor(); /* Randomly colored border */
            padding: 10px;
            margin-right: 10px;
        }
        #about {
            background-color: darkslateblue;
            color: white;
            padding: 20px;
        }
        #skills {
            background-color: darkslateblue;
            color: white;
            padding: 20px;
        }
    </style>
</head>
<body>
    <nav>
        <a href="#welcome">Welcome</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#proficiency">Proficiency</a>
        <a href="#contact">Contact</a>
    </nav>
    <div id="welcome" class="centered-content">
        <div class="centered-text">
            <h1>Welcome User</h1>
            <p>Welcome to my website. Feel free to look around at my life's achievements and aspirations.</p>
        </div>
    </div>
    <div id="about">
        <h2>About</h2>
        <img src="https://media.licdn.com/dms/image/D4E03AQFQjimbIykhSw/profile-displayphoto-shrink_200_200/0/1699579434374?e=2147483647&v=beta&t=YhfAaccuy1WIWXMbZyzFQBLAybPg8KN2rTa3UrWyKhQ" style="width: 100px; height: 100px; float: left; margin-right: 20px;">
        <p>I'm a cybersecurity practitioner who plays CTFs as a hobby and loves to learn more about cybersecurity. I have a variety of skill sets when it comes to cybersecurity including, Metasploit, Kali Linux, Wireshark, and even Steghide. I am extremely adaptable in many situations and I'm not afraid to try something new. I enrolled at George Mason University with the intended major of BS in Computer Science due to my interest in programming and computers. I then transferred to Old Dominion University where I plan to obtain a BS in Cybersecurity due to my interest in penetration testing and all things CTF.</p>
    </div>
    <div id="skills">
        <h2>Skills</h2>
        <canvas id="skillsChart"></canvas>
    </div>
    <script>
        var ctx = document.getElementById('skillsChart').getContext('2d');
        var myRadarChart = new Chart(ctx, {
            type: 'radar',
            data: {
                labels: ['Hacking', 'Creativity', 'Writing', 'Coding', 'System Analysis', 'Customer Service', 'Professionalism'],
                datasets: [{
                    label: 'Skill Level',
                    backgroundColor: 'rgba(135, 206, 235, 0.2)', // Light blue with transparency
                    borderColor: 'rgba(135, 206, 235, 1)', // Solid light blue
                    pointBackgroundColor: 'rgba(135, 206, 235, 1)',
                    data: [65, 59, 90, 81, 56, 55, 40] // Example data
                }]
            },
            options: {
                scale: {
                ticks: {
                    beginAtZero: true,
                    max: 100
                }
            }
        }
    });
    </script>

</body>
</html>
