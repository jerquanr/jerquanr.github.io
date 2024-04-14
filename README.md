<!DOCTYPE html>
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
            background-color: #181823;
            overflow-x: hidden;
        }
        nav {
            text-align: center;
            background: #181823;
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
            color: #4CAF50;
            border: 1px solid;
            padding: 5px 10px;
            border-radius: 5px;
            transition: color 0.3s;
        }
        nav a:focus, nav a:hover {
            color: #087F23;
            outline: none;
        }
        .centered-content {
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            height: 100vh;
            width: 100%;
            background: linear-gradient(to bottom, #4CAF50 0%, #087F23 100%);
            color: white;
        }
        .centered-content > div {
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        #about, #skills, #proficiency, #contact {
            background-color: #87CEEB;
            color: white;
            padding: 20px;
            margin-top: 50px;
            border: 1px solid #4CAF50;
        }
        #proficiency {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .grid-container {
            display: grid;
            grid-template-columns: repeat(5, 20px);
            grid-template-rows: repeat(4, 20px);
            gap: 5px;
            justify-content: flex-start;
        }
        .grid-item {
            background-color: white;
            border: 1px solid black;
            width: 20px;
            height: 20px;
            cursor: pointer; /* Changes cursor to pointer when hovering over grid items */
        }
        #contact {
            display: grid;
            grid-template-columns: auto auto;
            grid-row-gap: 10px;
            align-items: center;
        }
        #contact label {
            justify-self: end;
            padding-right: 10px;
        }
        #contact input, #contact textarea {
            padding: 5px;
            width: 100%;
            max-width: 300px;
        }
        textarea {
            resize: vertical;
        }
        .proficiency-image-container {
            flex: 1;
            padding-left: 20px;
            display: flex;
            flex-direction: column;
            align-items: flex-end;
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
        <div>
            <h1>Welcome User</h1>
            <p>Welcome to my website. Feel free to look around at my life's achievements and aspirations.</p>
        </div>
    </div>
    <div id="about">
        <h2>About</h2>
        <img id="profilePic" src="https://media.licdn.com/dms/image/D4E03AQFQjimbIykhSw/profile-displayphoto-shrink_200_200/0/1699579434374?e=2147483647&v=beta&t=YhfAaccuy1WIWXMbZyzFQBLAybPg8KN2rTa3UrWyKhQ" style="width: 100px; height: 100px; float: left; margin-right: 20px;">
        <p>I'm a cybersecurity practitioner who plays CTFs as a hobby and loves to learn more about cybersecurity. I have a variety of skill sets when it comes to cybersecurity including, Metasploit, Kali Linux, Wireshark, and even Steghide. I am extremely adaptable in many situations and I'm not afraid to try something new. I enrolled at George Mason University with the intended major of BS in Computer Science due to my interest in programming and computers. I then transferred to Old Dominion University where I plan to obtain a BS in Cybersecurity due to my interest in penetration testing and all things CTF.</p>
    </div>
    <div id="skills">
        <h2>Skills</h2>
        <canvas id="skillsChart"></canvas>
    </div>
    <div id="proficiency">
        <h2>Proficiency</h2>
        <div class="grid-container">
            <!-- Fill each grid item (20 total) -->
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div the="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
        </div>
        <div class="proficiency-image-container"></div>
    </div>
    <div id="contact">
        <h2>Contact</h2>
        <form action="submit_form.php" method="POST">
            <div style="display: grid; grid-template-columns: auto auto; align-items: center;">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email">
                <label for="subject">Subject:</label
                <input type="text" id="subject" name="subject">
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4"></textarea>
            </div>
        </form>
    </div>
    <script>
        document.querySelectorAll('.grid-item').forEach(item => {
            item.addEventListener('click', function() {
                const imageContainer = document.querySelector('.proficiency-image-container');
                const newImg = document.createElement('img');
                newImg.src = document.getElementById('profilePic').src;
                newImg.style.width = '100px';
                newImg.style.height = '100px';
                imageContainer.appendChild(newImg);
            });
        });
    </script>
</body>
</html
