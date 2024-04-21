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
        #about, #resume, #skills, #proficiency, #reflection, #contact {
            background-color: #87CEEB; /* Light blue background */
            color: white;
            padding: 20px;
            margin-top: 50px;
        }
        #skills h2, #about h2, #proficiency h2, #resume h2, #reflection h2 {
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
        <a href="#resume">Resume</a>
        <a href="#skills">Skills</a>
        <a href="#proficiency">Proficiency</a>
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
<br><br>Ever since I was a young boy I was always interested in technology. Ever since my dad 
introduced me to the family computer in the guest bedroom. This was in the early days back 
when you could only get internet via those linksy sticks. I remember spending countless hours 
on that computer, usually just to play games, mostly minesweeper and wizard101. I remember 
that since you couldn't progress in that game past a certain point without spending money I 
used to make several accounts just to play all the classes and waste countless hours. Or back 
when CD roms were prevalent I remember that my dad used to purchase a bunch of CD roms 
that would try to teach you about things. At the time all I saw were just fun games and a way to 
spend my time but looking back on it really does bring back a lot of nostalgia. Then I got into 
elementary school and they started introducing us to these small little typing machines. They 
weren’t quite computers in the traditional sense but they were used to introduce the concept of 
typing to small children so that we could get integrated with technology. Then one day I got into 
middle school and there they introduced me to chromebooks. You have to understand that at 
the time any interaction I had with computers was limited because I needed to focus on other 
things that weren’t computer related. So giving a child a laptop and allowing them free access to 
do almost anything they wanted to was like realizing that we aren’t the only ones in the 
universe. It was that big of a revelation that it warped my world view and way of thinking. Not 
only did I have unlimited information at my fingertips specifically for me but I had unlimited 
access to it. It was mind blowing and I can’t even count the amount of hours I spent using those 
chromebooks. It was an extremely life changing experience and leads me to the decision that I 
made next. 
<br>
<br><b>High School</b>
<br><br>Specifically in my school district I had the opportunity to go to different schools if I 
wanted to based on a program called the speciality center. Basically the speciality center would 
allow me to study alongside like minded students as well as have classes focused around that 
specific specialty. Now the school that I was originally sent to was the speciality center for 
Information Technology or IT and with the experience and joy I had for computers I of course 
applied and got accepted to the speciality center. While I was in the speciality center I met so 
many talented individuals with ambitions far greater than I realized at the time who helped me to 
grow and experience the wonder of IT. All of the classes with the exception of electives were 
focused on the core subjects like math, english, social studies, and science but the only 
difference is that it was heavily computer based. This gave me a lot of experience with 
computers in general as well as completing work using computers. It was a wonderful 
experience that I enjoyed thoroughly that only helped to foster my love for computers. Now 
when I was able to freely pick my electives I chose the basics for computer science and 
networking just because they were computer related and I love computers. When I got into 
those classes and actually got to experience the content I really enjoyed every part of it. 
Everything was so fun to me, how computers interacted with each other, the fact that code 
made things work with a few sentences, the many different softwares that people used daily. I 
wanted to learn more about all of these things. So as the years went by I continued doing all of 
the computer based classes my school had to offer and I got to experience a fair amount of 
information technology. As a result of this experience, the most interesting concepts to me were 
definitely programming and cybersecurity. With the end of my required schooling drawing near I 
had to make a drastic decision, which was the major I would pursue going forward. After a lot of 
thinking I decided that the potential gains were higher on the side of computer science so I 
decided to apply for several different colleges and I was accepted by George Mason University.
<br>
<br><b>College</b>
<br><br>Accepted by George Mason University I was thrilled to begin a new chapter in my life. I 
would be able to experience college life and pursue my bachelor’s in computer science. The first 
semester went extremely well. I had two roommates and I was enjoying every part of college. 
Being able to do things on your own time was such a different experience than what I had at 
home and it's cliche to say but I had a little freedom and unfortunately I went overboard with it. I 
spent my time hanging out with my new friends and going to all the school events and I realize 
that my grade suffered as a part of it. I had completely forgotten about the main reason why I 
was at George Mason to begin with. However, I realized much too late that I had made a 
mistake and into my second year of college I had managed to fail a class and lose interest in the 
very major I was working so hard to pursue. Fail is also a strong word to describe this situation 
as it was more so a result of me letting my grades slip by not doing assignments since I didn't 
find them interesting any more. Nevertheless my grades slipped as a result and I desperately 
wanted to change majors. Unfortunately, the requirements to change majors would require me 
to take a class over the summer and increase my GPA by acing that class, a feat I was not 
capable of with my mindset back then. So I transferred here to Old Dominion University where I 
was able to pursue my Bachelor of Science in Cybersecurity. Finally, I was on track to pursue a 
degree in a field that I’m passionate about. During my time at Old Dominion I have taken many 
classes related to cyber security and I have thoroughly enjoyed every second of them. I have 
never thought that the decision to change my major would have been a bad one but I didn't 
realize just how much of a good decision it actually was until I did it. The most prominent of my 
classes was definitely any class that allowed me to actually do hands-on work like labs or 
projects. It was in these classes that I thrived and where I enjoyed my experiences the most. 
Specifically in CYSE301 an introductory class about ethical hacking every week we would do a 
different lab that I collaborated with a few of my peers around every tuesday. It was a wonderful 
experience that made me appreciate team work and the field that I chose. I also had the 
pleasure of taking up a job while at Old Dominion. It was a food service job but I enjoyed it all 
the same and the pay was quite reasonable while allowing me to earn customer service skills. 
However, in the most recent summer I was trying to get an internship because I realized that I 
need to start preparing for life after college rather than just pursuing my interests. There I had 
the big realization that things won’t always turn out the way that you want. Even though I 
thought I put forth a lot of effort I didn’t get any internship and I settled for a rough labor job 
working at Sam’s Club. I wasn’t a fan of the hours or working conditions that they had me to 
operate but nevertheless I did my job, slept, and repeated the cycle. However, it was through 
the experience that summer that I realized I needed to put forth a lot more effort or this same 
situation could happen next summer. So this past semester and this current semester I have 
been working extremely hard to not only participate in more events to put on my resume but 
also to get connections that may be able to lead to job opportunities. Now I’ve started getting 
interviews for actual professional jobs which is something I’ve never done before and it leads 
into what’s next for my future. 
<br>
<br><b>Conclusion and Future Endeavors</b>
<br><br>Now obviously I don’t know what the future holds for me but going back to that ethical 
hacking class I talked about earlier I’m currently thinking about eventually climbing the ranks to 
get an ethical hacking job. I’m currently waiting for some interviews to give me their response on 
my status but if I do get an internship that would make getting a job after graduation much 
easier and it would help to build out my resume even more. As it stands I am set to graduate in 
the fall of 2024 and I have thoroughly enjoyed every step in the process that helped to create 
the current version of myself that now exists.</p>
</div>

<section id="resume">
    <h2>Resume</h2>
    <p>Jerquan Brabble</p>
    <p>Norfolk, Virginia</p>
    <p>(804) 661-3259</p>
    <a href="mailto:jbrab002@odu.edu">jbrab002@odu.edu</a><br>
    <br><h2>Objective</h2>
    <p>A dedicated and skilled student with a proven track record in ethical hacking, penetration testing, data analysis, real-time incident response, and firewall administration. Leveraging experience gained through participation in multiple Capture the Flag events and a solid educational background in cybersecurity, I am seeking opportunities to contribute my expertise to your company in enhancing cybersecurity measures and safeguarding critical assets.</p>
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
        <li>Ethical Hacking and Penetration Testing</li>
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
</section>
    <div id="skills">
        <h2>Skills</h2>
        <canvas id="skillsChart"></canvas>
    </div>
        <div id="proficiency">
        <h2>Proficiency</h2>
        <div class="proficiency-grid">
            <div class="proficiency-item" ><img src="https://logos.flamingtext.com/Word-Logos/writing-design-sketch-name.png" alt="Image 1"></div>
            <div class="proficiency-item" ><img src="https://icons.iconarchive.com/icons/iconsmind/outline/512/Paper-icon.png" alt="Image 2"></div>
            <div class="proficiency-item" ><img src="https://static.thenounproject.com/png/2473397-200.png" alt="Image 3"></div>
            <div class="proficiency-item" ><img src="https://png.pngtree.com/png-vector/20221010/ourmid/pngtree-paper-icon-png-image_6294297.png" alt="Image 4"></div>
            <div class="proficiency-item" ><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQJ4X2zYfSztRV5Ou6CSJ5pnsrzGjaEp3Sg7tSL_HBdDA&s" alt="Image 5"></div>
            <div class="proficiency-item" ><img src="https://static.thenounproject.com/png/2216968-200.png" alt="Image 6"></div>
            <div class="proficiency-item" ><img src="https://static-00.iconduck.com/assets.00/malware-detected-icon-426x512-kbw42at9.png" alt="Image 7"></div>
            <div class="proficiency-item" ><img src="https://cdn-icons-png.flaticon.com/512/6463/6463383.png" alt="Image 8"></div>
            <div class="proficiency-item" ><img src="https://i.ytimg.com/vi/tTtjETjGDFY/maxresdefault.jpg" alt="Image 9"></div>
            <div class="proficiency-item" ><img src="https://p7.hiclipart.com/preview/569/605/184/internet-icon-internet-access-web-browser-circle-with-line-through-it.jpg" alt="Image 10"></div>
            <div class="proficiency-item" ><img src="https://deow9bq0xqvbj.cloudfront.net/ep-logo/pbblog8987066/EP55_CTF_Iconbdemd.png" alt="Image 11"></div>
            <div class="proficiency-item" ><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/68/Video_camera_icon.svg/1200px-Video_camera_icon.svg.png" alt="Image 12"></div>
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
 <section id="reflection">
        <h2>Reflection</h2>
        <p>This section will explore my personal insights and reflections on my professional journey and growth.</p>
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
