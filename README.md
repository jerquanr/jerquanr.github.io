<html>
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
        #about, #resume, #skills, #best-work, #reflection, #contact {
            background-color: #87CEEB; /* Light blue background */
            color: white;
            padding: 20px;
            margin-top: 50px;
        }
        #skills h2, #about h2, #best-work h2, #resume h2, #reflection h2 {
            margin-top: 0;
        }
        #best-work {
            display: flex; /* Set proficiency section to flex */
            justify-content: space-between; /* Space between header and grid */
            align-items: start; /* Align items to start vertically */
        }
        .best-work-grid {
            display: grid;
            margin-left: -200px;
            grid-template-columns: repeat(4, 50px); /* Four columns each 50px wide */
            grid-template-rows: repeat(5, 50px); /* Five rows each 50px high */
            grid-gap: 0; /* No space between grid items */
            justify-self: end; /* Align grid to the end of the flex container */
        }
        .best-work-item {
            border: 1px solid black;
            background-color: #fff; /* White background for grid items */
            width: 50px; /* Width to maintain cube shape */
            height: 50px; /* Height to maintain cube shape */
        }
        .best-work-item img {
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
        #instruction-text {
    margin: 10px 0;
    padding: 10px;
    background-color: #f7f7f7;
    border: 1px solid #ccc;
    border-radius: 5px;
    color: #333;
    font-size: 16px;
    text-align: center;
}
    </style>
</head>
<body>
    <nav>
        <a href="#welcome">Welcome</a>
        <a href="#about">About</a>
        <a href="#resume">Resume</a>
        <a href="#skills">Skills</a>
        <a href="#best-work">Best Work</a>
        <a href="#reflection">Reflection</a>
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
    <p><b>Detailing events of my past that transformed me into the person of today.</b></p>
      by Jerquan Brabble
        <br>Old Dominion University
        <br><br><b>Early Life</b>
</p>
</div>

<section id="resume">
    <h2>Resume</h2>
    <p>Jerquan Brabble</p>
    <p>Norfolk, Virginia</p>
    <p>(804) 661-3259</p>
    <a href="mailto:jbrab002@odu.edu">jbrab002@odu.edu</a><br>
    <br><h2>Objective</h2>
    <p>A dedicated and skilled student with a proven track record in ethical hacking, network testing, data analysis, real-time incident response, and firewall administration. Leveraging experience gained through participation in multiple Capture the Flag events and a solid educational background in cybersecurity, I am seeking opportunities to contribute my expertise to your company in enhancing cybersecurity measures and safeguarding critical assets.</p>
    <h2>Education</h2>
    <p><strong>Bachelor of Science in Cybersecurity</strong><br>Old Dominion University, Norfolk, VA<br>August 2022 – Present<br>GPA: 3.68; Dean’s List<br>Expected Graduation: December 2024</p>
    <h3>Relevant Courses:</h3>
    <ul>
        <li>Introduction to Networking and Security</li>
        <li>Linux System for Cybersecurity</li>
        <li>Introduction to Cybersecurity</li>
        <li>Intro Computer Programming</li>
        <li>Essentials of Computer Science</li>
        <li>Intro to Information Systems</li>
        <li>Cybersecurity, Technology, and Society</li>
        <li>Cybersecurity Fundamentals</li>
        <li>Cybersecurity Ethics</li>
        <li>Cyber Techniques and Operations</li>
        <li>Digital Forensics</li>
        <li>Ethical Hacking and Network Testing</li>
    </ul>
    <h2>Professional Experience</h2>
        <h3>Capture the Flag Team Member</h3>
        <p>Old Dominion University, Norfolk, VA<br>September 2023 – Present</p>
        <ul>
            <li>Served as a team member in Capture the Flag events, honing skills in various areas of cybersecurity.</li>
            <li>Participated in various Capture The Flag (CTF) events, including picoCTF, HackTheBox, and Hacker101.</li>
            <li>Achieved fourth place in Summit CTF, hosted by Virginia Tech.</li>
            <li>Participated in Cyberforge conference and CTF competition.</li>
            <li>Demonstrated proficiency in ethical hacking, penetration testing, and data analysis.</li>
        </ul>
    <h3>Customer and Food Service Worker</h3>
        <p>Aramark, Norfolk, VA<br>September 2022 – Present</p>
        <ul>
            <li>Offered friendly and efficient service to customers, handled challenging situations with ease.</li>
            <li>Proficient in operating a cash register and processing payments.</li>
            <li>Maintained high personal grooming standards and uniform presentation.</li>
            <li>Proved successful working within tight deadlines and fast-paced atmosphere.</li>
        </ul>
    <h2>Key Competencies</h2>
    <ul>
        <li>Familiar with basic concepts of Linux operating system.</li>
        <li>Understanding of fundamental cybersecurity principles.</li>
        <li>Foundational knowledge of computer programming with Java.</li>
        <li>In-depth knowledge of networking and security principles.</li>
        <li>Skilled in using Metasploit for penetration testing.</li>
        <li>Proficient in Microsoft Office Suite.</li>
    </ul>
    <h2>Memberships</h2>
    <p>Cybersecurity Student Association</p>
</section>
    <div id="skills">
        <h2>Skills</h2>
        <canvas id="skillsChart"></canvas>
    </div>
        <div id="best-work">
        <h2>Best Work</h2>
        <p id="instruction-text">
        Click on one of the items in the grid below to take a look at some of my best work.
    </p>
        <div class="best-work-grid">
            <div class="best-work-item" ><img src="https://logos.flamingtext.com/Word-Logos/writing-design-sketch-name.png" alt="Image 1"></div>
            <div class="best-work-item" ><img src="https://icons.iconarchive.com/icons/iconsmind/outline/512/Paper-icon.png" alt="Image 2"></div>
            <div class="best-work-item" ><img src="https://static.thenounproject.com/png/2473397-200.png" alt="Image 3"></div>
            <div class="best-work-item" ><img src="https://png.pngtree.com/png-vector/20221010/ourmid/pngtree-paper-icon-png-image_6294297.png" alt="Image 4"></div>
            <div class="best-work-item" ><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQJ4X2zYfSztRV5Ou6CSJ5pnsrzGjaEp3Sg7tSL_HBdDA&s" alt="Image 5"></div>
            <div class="best-work-item" ><img src="https://static.thenounproject.com/png/2216968-200.png" alt="Image 6"></div>
            <div class="best-work-item" ><img src="https://static-00.iconduck.com/assets.00/malware-detected-icon-426x512-kbw42at9.png" alt="Image 7"></div>
            <div class="best-work-item" ><img src="https://cdn-icons-png.flaticon.com/512/6463/6463383.png" alt="Image 8"></div>
            <div class="best-work-item" ><img src="https://i.ytimg.com/vi/tTtjETjGDFY/maxresdefault.jpg" alt="Image 9"></div>
            <div class="best-work-item" ><img src="https://p7.hiclipart.com/preview/569/605/184/internet-icon-internet-access-web-browser-circle-with-line-through-it.jpg" alt="Image 10"></div>
            <div class="best-work-item" ><img src="https://deow9bq0xqvbj.cloudfront.net/ep-logo/pbblog8987066/EP55_CTF_Iconbdemd.png" alt="Image 11"></div>
            <div class="best-work-item" ><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/68/Video_camera_icon.svg/1200px-Video_camera_icon.svg.png" alt="Image 12"></div>
        </div>
        <div class="document-viewer">
        <iframe id="docFrame" style="width:100%; height:400px; border:none;"></iframe>
    </div>
</div>
 <section id="reflection">
<h2>Reflection</h2>
<p>
<p>Culmination of Hard Work: Reflecting on my academic career for the future</p>
<p>Jerquan Brabble</p>
<p>Old Dominion University</p>
<p>IDS 493: Electronic Portfolio Project</p>
<p>CARIN ANDREWS</p>
<p>April 20, 2024</p>
     </p>
    </section>
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
                    data: [3, 3, 3, 1.95, 1.95, 3, 2.4] 
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
        "",
        "https://docs.google.com/document/d/1WZH5B6aItXKE8ihS81jdUY_ioEn1GWq1f8DX_5iVMLc/preview",
        "https://docs.google.com/document/d/1YXou0obL6sYkMLV3wvjSvBN3xb9ixDpqx8hQaySkfvQ/preview",
        "https://docs.google.com/document/d/1egzmSV451-ghXOxiewqQe5YuNNZGvlNx7Ib27HyzbQA/preview",
        "",
        "https://docs.google.com/document/d/1S7egU7lZyhHS8qlxWgLZBmhUuDl0HuLK9DnDNLSve8o/preview",
        "https://docs.google.com/document/d/1cEE27k02XaVxyBxXn1Vkjgb0241npYf9kdw26selwlU/preview",
        "https://docs.google.com/document/d/1MuOIBRh_hMzdB0wmjO9COb9QpQNyeXQ9nnZ9NWIfl2I/preview",
        "",
        "https://jerquanr.github.io/#welcome",
        "https://summitctf.org/"
    ];
    const bestworkItems = document.querySelectorAll('#best-work .best-work-item');
    bestworkItems.forEach((item, index) => {
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
