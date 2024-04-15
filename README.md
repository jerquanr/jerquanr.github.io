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
            background-color: #181823; /* Very dark blue */
            overflow-x: hidden; /* Prevents horizontal scroll */
        }
        nav {
            text-align: center;
            background: #181823; /* Dark blue background for the navigation bar */
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
            color: #4CAF50; /* Green text */
            border: 1px solid;
            padding: 5px 10px;
            border-radius: 5px;
            transition: color 0.3s; /* Smooth transition for hover and focus */
        }
        nav a:focus {
            color: #087F23; /* Dark green on focus */
            outline: none;
        }
        nav a:hover {
            color: #087F23; /* Dark green on hover */
        }
        .centered-content {
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            height: 100vh;
            width: 100%;
            background: linear-gradient(to bottom, #4CAF50 0%, #087F23 100%); /* Gradient green background */
            color: white;
        }
        .centered-content > div {
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        #about, #skills, #proficiency, #contact {
            background-color: #87CEEB; /* Light blue background */
            color: white;
            padding: 20px;
            margin-top: 50px;
        }
        #skills h2, #about h2, #proficiency h2 {
            margin-top: 0;
        }
        #proficiency {
            display: flex; /* Set proficiency section to flex */
            justify-content: space-between; /* Space between header and grid */
            align-items: start; /* Align items to start vertically */
        }
        .proficiency-grid {
            display: grid;
            margin-left: -200px;
            grid-template-columns: repeat(4, 50px); /* Four columns each 50px wide */
            grid-template-rows: repeat(5, 50px); /* Five rows each 50px high */
            grid-gap: 0; /* No space between grid items */
            justify-self: end; /* Align grid to the end of the flex container */
        }
        .proficiency-item {
            border: 1px solid black;
            background-color: #fff; /* White background for grid items */
            width: 50px; /* Width to maintain cube shape */
            height: 50px; /* Height to maintain cube shape */
        }
        .proficiency-item img {
          width: 100%; /* Ensure the image covers the full grid cell */
          height: 100%;
          object-fit: cover; /* Ensures the image covers the area without distorting aspect ratio */
          display: block; /* Removes bottom space/gap */
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
            <button id="goToAbout">Confirm</button>
        </div>
    </div>
    <div id="about">
        <h2>About</h2>
        <img src="https://media.licdn.com/dms/image/D4E03AQFQjimbIykhSw/profile-displayphoto-shrink_200_200/0/1699579434374?e=2147483647&v=beta&t=YhfAaccuy1WIWXMbZyzFQBLAybPg8KN2rTa3UrWyKhQ" style="width: 200px; height: 200px; float: left; margin-right: 20px;">
        <p>I'm a cybersecurity practitioner who plays CTFs as a hobby and loves to learn more about cybersecurity. I have a variety of skill sets when it comes to cybersecurity including, Metasploit, Kali Linux, Wireshark, and even Steghide. I am extremely adaptable in many situations and I'm not afraid to try something new. I enrolled at George Mason University with the intended major of BS in Computer Science due to my interest in programming and computers. I then transferred to Old Dominion University where I plan to obtain a BS in Cybersecurity due to my interest in penetration testing and all things CTF.</p>
    </div>
    <div id="skills">
        <h2>Skills</h2>
        <canvas id="skillsChart"></canvas>
    </div>
    <div id="proficiency">
        <h2>Proficiency</h2>
        <div class="proficiency-grid">
            <div class="proficiency-item" ><img src="https://png.pngtree.com/png-vector/20221010/ourmid/pngtree-paper-icon-png-image_6294297.png" alt="Image 1"></div>
            <div class="proficiency-item" ><img src="https://icons.iconarchive.com/icons/iconsmind/outline/512/Paper-icon.png" alt="Image 2"></div>
            <div class="proficiency-item" ><img src="https://static.thenounproject.com/png/2473397-200.png" alt="Image 3"></div>
            <div class="proficiency-item"></div>
            <div class="proficiency-item" ><img src="https://cdn-icons-png.flaticon.com/512/6463/6463383.png" alt="Image 4"></div>
            <div class="proficiency-item" ><img src="https://static.thenounproject.com/png/2216968-200.png" alt="Image 5"></div>
            <div class="proficiency-item" ><img src="https://static-00.iconduck.com/assets.00/malware-detected-icon-426x512-kbw42at9.png" alt="Image 6"></div>
            <div class="proficiency-item" ></div>
            <div class="proficiency-item" ><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/68/Video_camera_icon.svg/1200px-Video_camera_icon.svg.png" alt="Image 7"></div>
            <div class="proficiency-item" ><img src="https://p7.hiclipart.com/preview/569/605/184/internet-icon-internet-access-web-browser-circle-with-line-through-it.jpg" alt="Image 8"></div>
            <div class="proficiency-item" ><img src="https://deow9bq0xqvbj.cloudfront.net/ep-logo/pbblog8987066/EP55_CTF_Iconbdemd.png" alt="Image 9"></div>
            <div class="proficiency-item" ></div>
            <div class="proficiency-item" ></div>
            <div class="proficiency-item" ></div>
            <div class="proficiency-item" ></div>
            <div class="proficiency-item" ></div>
            <div class="proficiency-item" ></div>
            <div class="proficiency-item" ></div>
            <div class="proficiency-item" ></div>
            <div class="proficiency-item" ></div>
        </div>
        <div class="document-viewer">
        <iframe id="docFrame" style="width:100%; height:400px; border:none;"></iframe>
    </div>
</div>
    </div>
<div id="contact">
        <h2>Contact</h2>
        <form action="submit_form.php" method="POST">
            <div style="display: grid; grid-template-columns: auto auto; align-items: center;">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email">
                <label for="subject">Subject:</label>
                <input type="text" id="subject" name="subject">
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4"></textarea>
                <button id="submit" type="button">Submit</button>
            </div>
        </form>
    <script>
        var ctx = document.getElementById('skillsChart').getContext('2d');
        var myRadarChart = new Chart(ctx, {
            type: 'radar',
            data: {
                labels: ['Hacking', 'Creativity', 'Writing', 'Coding', 'System Analysis', 'Customer Service', 'Professionalism'],
                datasets: [{
                    label: 'Skill Level',
                    backgroundColor: 'rgba(52, 152, 219, 0.5)', // Semi-transparent blue
                    borderColor: '#2980b9', // Solid blue
                    pointBackgroundColor: '#2980b9',
                    data: [3, 3, 3, 1.95, 1.95, 3, 2.4] // Example data
                }]
            },
            options: {
                scale: {
                    angleLines: {
                        display: true
                    },
                    ticks: {
                        suggestedMin: 50,
                        suggestedMax: 100
                    }
                }
            }
        });
    </script>
    <script>
    document.getElementById('goToAbout').addEventListener('click', function() {
        window.location.href = '#about';
    });
    document.getElementById('submit').addEventListener('click', function() {
        window.location.href = '#welcome';
    });
</script>
<script>
document.addEventListener("DOMContentLoaded", function() {
    var docUrls = [
        "https://docs.google.com/document/d/1egzmSV451-ghXOxiewqQe5YuNNZGvlNx7Ib27HyzbQA/preview",
        "https://docs.google.com/document/d/1WZH5B6aItXKE8ihS81jdUY_ioEn1GWq1f8DX_5iVMLc/preview",
        "https://docs.google.com/document/d/1YXou0obL6sYkMLV3wvjSvBN3xb9ixDpqx8hQaySkfvQ/preview",
        "",
        "https://docs.google.com/document/d/1MuOIBRh_hMzdB0wmjO9COb9QpQNyeXQ9nnZ9NWIfl2I/preview",
        "https://docs.google.com/document/d/1S7egU7lZyhHS8qlxWgLZBmhUuDl0HuLK9DnDNLSve8o/preview",
        "https://docs.google.com/document/d/1cEE27k02XaVxyBxXn1Vkjgb0241npYf9kdw26selwlU/preview",
        "",
        "", // Other content
        "https://jerquanr.github.io/#welcome",
        "https://summitctf.org/"
    ];
    const proficiencyItems = document.querySelectorAll('#proficiency .proficiency-item');
    proficiencyItems.forEach((item, index) => {
        item.addEventListener('click', function() {
            const docFrame = document.getElementById('docFrame');
            if (docUrls[index]) {
                docFrame.src = docUrls[index];
            } else {
                docFrame.src = ''; // Clear the iframe if no document is associated
            }
        });
    });
});
// Existing scripts for chart and navigation buttons
var ctx = document.getElementById('skillsChart').getContext('2d');
var myRadarChart = new Chart(ctx, {
    type: 'radar',
    data: {
        labels: ['Hacking', 'Creativity', 'Writing', 'Coding', 'System Analysis', 'Customer Service', 'Professionalism'],
        datasets: [{
            label: 'Skill Level',
            backgroundColor: 'rgba(52, 152, 219, 0.5)', // Semi-transparent blue
            borderColor: '#2980b9', // Solid blue
            pointBackgroundColor: '#2980b9',
            data: [3, 3, 3, 1.95, 1.95, 3, 2.4] // Example data
        }]
    },
    options: {
        scale: {
            angleLines: {
                display: true
            },
            ticks: {
                suggestedMin: 50,
                suggestedMax: 100
            }
        }
    }
});
document.getElementById('goToAbout').addEventListener('click', function() {
    window.location.href = '#about';
});
document.getElementById('submit').addEventListener('click', function() {
    window.location.href = '#welcome';
});
</script>
