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
        #about, #resume, #skills, #best-work, #internship, #contact {
            background-color: #87CEEB; /* Light blue background */
            color: white;
            padding: 20px;
            margin-top: 50px;
        }
        #skills h2, #about h2, #best-work h2, #resume h2, #internship h2 {
            margin-top: 0;
        }
        #best-work {
            padding: 20px;
            border-radius: 5px;
        }
        #best-work h2 {
            margin-bottom: 10px; /* Ensures spacing between the header and instruction text */
        }
        .best-work-grid {
            display: grid;
            margin-left: 0px;
            border-top: none;
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
            margin: 0;
            padding: 10px;
            background-color: #f7f7f7;
            border: 1px solid #ccc;
            border-radius: 5px;
            border-bottom: 2px solid #ccc;
            color: #333;
            font-size: 16px;
            text-align: center;
        
        }
        #gridclickers2 {
          cursor: pointer;
        }
        #gridclickers3 {
          cursor: pointer;
        }
        #gridclickers4 {
          cursor: pointer;
        }
        #gridclickers6 {
          cursor: pointer;
        }
        #gridclickers7 {
          cursor: pointer;
        }
        #gridclickers8 {
          cursor: pointer;
        }
        #gridclickers10 {
          cursor: pointer;
        }
        #gridclickers11 {
          cursor: pointer;
        }
        #video-trigger {
            cursor: pointer;
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
        <a href="#internship">Internship</a>
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
            <div class="best-work-item" ><img src="https://logos.flamingtext.com/Word-Logos/writing-design-sketch-name.png" alt="Image 1" id="gridclickers1"></div>
            <div class="best-work-item" ><img src="https://icons.iconarchive.com/icons/iconsmind/outline/512/Paper-icon.png" alt="Image 2" id="gridclickers2"></div>
            <div class="best-work-item" ><img src="https://static.thenounproject.com/png/2473397-200.png" alt="Image 3" id="gridclickers3"></div>
            <div class="best-work-item" ><img src="https://png.pngtree.com/png-vector/20221010/ourmid/pngtree-paper-icon-png-image_6294297.png" alt="Image 4" id="gridclickers4"></div>
            <div class="best-work-item" ><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQJ4X2zYfSztRV5Ou6CSJ5pnsrzGjaEp3Sg7tSL_HBdDA&s" alt="Image 5" id="gridclickers5"></div>
            <div class="best-work-item" ><img src="https://static.thenounproject.com/png/2216968-200.png" alt="Image 6" id="gridclickers6"></div>
            <div class="best-work-item" ><img src="https://static-00.iconduck.com/assets.00/malware-detected-icon-426x512-kbw42at9.png" alt="Image 7" id="gridclickers7"></div>
            <div class="best-work-item" ><img src="https://cdn-icons-png.flaticon.com/512/6463/6463383.png" alt="Image 8" id="gridclickers8"></div>
            <div class="best-work-item" ><img src="https://i.ytimg.com/vi/tTtjETjGDFY/maxresdefault.jpg" alt="Image 9" id="gridclickers9"></div>
            <div class="best-work-item" ><img src="https://p7.hiclipart.com/preview/569/605/184/internet-icon-internet-access-web-browser-circle-with-line-through-it.jpg" alt="Image 10" id="gridclickers10"></div>
            <div class="best-work-item" ><img src="https://deow9bq0xqvbj.cloudfront.net/ep-logo/pbblog8987066/EP55_CTF_Iconbdemd.png" alt="Image 11" id="gridclickers11"></div>
            <div class="best-work-item" ><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/68/Video_camera_icon.svg/1200px-Video_camera_icon.svg.png" alt="Video 1" id="video-trigger"></div>
        </div>
        <div class="document-viewer">
        <iframe id="docFrame" style="width:100%; height:400px; border:none;"></iframe>
    </div>
</div>
 <section id="internship">
<h2>Reflection</h2>
<p>
<p>System Analyst for the City of Virginia Beach</p>
<p>Supervisor: Brittany Jennings</p>
<p>Class: CYSE 368</p>
<p>Date: 7/27/2024</p>
<p>Term: Summer 2024</p>
<p>Jerquan Brabble</p>
<p>Intro + Learning Objectives</p>

<p>It is common knowledge that cyber security, while a highly respected field, isn’t the easiest field to secure a job in with no experience. It’s a field that is integral to a company’s overall success and accounts for a company’s security. With this in mind it is imperative that each individual in this field be properly trained and vetted so that they can perform their tasks efficiently and effectively. This is why even with a degree in cyber security it may not be possible to achieve an immediate position in cyber security. This is where the need for entry level IT and computer science jobs come in. In order to achieve an ideal position in cyber security it is first necessary to receive experience in a similar field to show potential employers that you’re familiar with computer information systems and how to effectively work in a business environment. The reason I set my sights on system analysis in particular is because my mother was a system analyst before she retired a few years ago. As for the reason I chose this particular agency, I simply decided that they would be able to provide me with the best benefits for the amount of work that I would need to put in. They were also keen in working with a hybrid environment, a saving grace, as I did not have access to solid transportation at the time. Before starting this internship, I set out a list of four objectives to accomplish in my time working there. The first objective I hoped to achieve was learning about system analysis. I wanted to know what exactly the job entailed, what responsibilities would be required to accomplish the job and learn about various concepts and integral to system analysis. The second objective I hoped to achieve was gaining experience in system analysis. I expected to receive weekly hands-on training with different systems and how to properly manage them. My third objective was to gain experience in the IT field. As stated earlier, having a job in IT would be incredible for my resume at this time and it's one of the main reasons I decided to take this internship. My fourth and final objective is to gain experience working with clients. Ideally I would be the central point of contact for a small period of time and clients could come to me in order to resolve their issues. Hello, my name is Jerquan Brabble and this is my experience working for the City of Virginia Beach as a System Analyst. 

<p>Beginning of Internship</p>
</p>First, it’s important to understand two key points before continuing, who my company is and what exactly a system analyst is. I am employed by the City of Virginia Beach meaning that I work for public services under the government. To get even more specific, my position allows for me to be stationed at any number of locations including but not limited to the Virginia Aquarium and the Meyera E. Oberndorf Public Library otherwise referred to as “central library”. So far, the City of Virginia Beach has stationed me at both locations for a significant amount of time at each location. However, for the purposes of this paper I will be exclusively referring to the Meyera Public Library as the main place of employment since that is where I was stationed the most during my internship. The objective of the Virginia Beach Public Library is to “serve residents regardless of race, color, religion, national origin, sex, age, physical or mental disability, pregnancy, sexual orientation, or gender identity. They wish to help residents feel welcome in our buildings and that they can find the resources they want and need to achieve their goals and enjoy the highest quality of life.”An interesting thing to note is that Virginia Beach is considered the largest state in Virginia which makes the impressive size of their official city buildings all the more reasonable. Before I get into my first day I would just like to share a couple of things that either bothered me or gave me some issues getting to my first day. Before I received the offer for this internship I was concerned that many of the other companies that I had applied for weren’t going to even get me to the next stage so receiving the message that this job wanted to give me an interview was a sigh of relief. After the interview and being able to give off a good initial impression it was an extremely long time before I actually received my offer letter. I was sent an email telling me that they would like to move forward with and actually hire me if I was interested in the position. After responding it took me emailing them 2 days before my actual scheduled first day in order to receive my official offer letter. It was a little annoying but in hindsight I can kind of understand how this happened. There was actually a major incident involving a previous employee that warranted extra security in all future employment. Before starting the job I was told that I would need to do an I-9 and fingerprinting as well. I completed the I-9 but as this was my first time ever doing fingerprinting I was blissfully unaware of how the whole process worked. As such I left without being fingerprinted that day. Now we move on to the first day. These are my initial thoughts and experiences on my first day. I was originally told that I was to be stationed at the courthouse so I was a little bit nervous. Immediately I had a bit of trouble trying to find the place as I was told to report to building 19 but the building I had to report for my I-9 was building 18 yet 19 wasn’t near it. However, I was able to find it after some time even with a little bit of confusion. As I arrived each and every building was guarded via an RFID reader or keycard scanner. I initially had trouble getting inside the building but in true human error fashion, the doors were unlocked. Once walking inside the building I was greeted by beautiful scenery and I started my quest to find a person. After finding someone I then introduced myself and they were able to lead me to an office upstairs. The person that led me upstairs tried to find my supervisor so they could notify them that I was here. Keep in mind that this was about 30 minutes into my assigned start period. After a few more minutes of calling around they told me that actually I needed to be somewhere else and that was where I would continue work from now on. No big deal, mixup on the location but it's perfectly fine. I head on over to the central library which is the actual place that I work. Once I arrive there I head around back and I meet Trinika, who I would later come to know as the Team Lead, who was able to lead me around and teach me about the responsibilities of the position and so on and so forth. It was a pretty basic first day getting accustomed to things. It was a lot of information to take in however, and I didnt remember all of it. The most important thing I did retain was just how extravagant and incredible this library was. I’ve never seen such a technologically advanced library before then. Even different sections for different age groups. There was a separate section for adults, teens, the elderly, and children. It was all extremely impressive. I was introduced to my fellow coworkers and my own working station. I was told about the numerous projects that they had completed alongside the numerous projects they planned to complete. The main thing that I got from this is that they have a LOT of work and responsibilities to do. I then was told that I needed to do fingerprinting which I would later come to understand I had no understanding of. I got to sit in on one of their meetings and to finish off the day I pretty much just stood around organizing cables. It was a very very very different experience to the fast food and busy work that I have previously experienced. You could tell that these people are professionals and it was a little bit intimidating. It was also intimidating knowing that everyone on the floor I worked was a female. There were no guys or dudes that I could relate to which I have just never encountered before. Overall it was a successful first day and I learned a lot just about working in a professional work environment. In the coming days my training consisted of a multitude of experiences. I started off my first time by having a wonderful one on one slide presentation with the head of the training department Jennifer Gey. In the presentation which lasted approximately forty five minutes they explained basic things about the position and who everyone was as well as Jennifer’s experience in the company so far. The next of my training was me receiving a company issue laptop from Brittany Jennings who was considered my supervisor for the purposes of this internship and also was my point of contact should anything happen that I needed help getting resolved. The next day they had me doing basic security training on my laptop which was all things that I had been taught at ODU. This was pretty much the extent of the training that I needed in order to effectively do my job. 
<p>Major Work Duties</p>
<p>Eddie was another system analyst who for the purposes of this internship could be considered a mentor and the person I spent the most time with. As far as my day to day activities I mostly just checked in with my mentor Eddie and he gave me different tasks to work on. Anytime I checked in with him after completing a task he was quick to give me another one to work on. The dynamic of my activities was that on the days I did come in person I mostly worked on an assignment Eddie gave me at home. However, when I did come in person, I worked on any additional tasks that the people at the library needed help with. There was such a large amount of tasks that I got assigned that it would be difficult to list based solely on my memory. Thankfully, I documented all of my important tasks inside of a small notebook that the city gave to me. The first of my tasks that I was assigned to work on was assisting Brittany by completing an ADA compliance form. The ADA compliance form was in order to help with the City of Virginia Beach’s mission goals of allowing for accommodations of people with disabilities. Essentially what I was asked to do was to go through a list of the central library’s websites and I had to put into a spreadsheet what was on each website and several other various factors like if it had a payment screen, could you login, did it lead to other sites, and many other things. It was a relatively easy task and it took me all of one afternoon to complete it. However, it was important to note because it shows that I have experience in complying with civil rights law. The next most notable project I worked on was software testing in which I helped to verify which applications and softwares were up and running on several different computers. This was a task that I was asked to help a coworker named Jordan with. She was a software support engineer and I got to interact with her a number of times over the course of the summer. For the task at hand all that I needed to do was verify that the software in the list I was sent worked correctly. It did not take long but it was important because it allowed me to do software testing. There were a couple of other tasks that I was asked to do but that mainly consisted of repeatable tasks that I continued to do week after week. There was wifi hotspot testing that I was helping Jade, a coworker with. She was in the same department with Jordan and all I needed to do was turn on wifi hotspots and verify that they worked correctly. Another thing that I needed to do with Jordan was organize files based on alphabetical order. The only other task that I helped at the Central Library with was the various meetings that we had throughout the internship, they were mostly about maintaining the computer cart that we used to lend out various laptops out to several different clients in the library. The first few weeks focused mainly on the tasks but the majority of the internship was spent remote and in person at the Central Library helping Eddie with whatever he needed. As I discussed earlier Eddie is my mentor and the person that I spent most of my time with. He was the person that would give me my tasks and the person that I could rely on whenever I needed help with those tasks. There were a number of projects that he wanted me to know about but firstly I’ll talk about the projects that Eddie came up with before I actually started working. There were three key projects to note at the time: Project Lazarus, Project River Otter, and a Generative AI chatbot at the library. Project Lazarus was his proposal to use generative AI to allow for exhibits at one of our museums to have talking dead people in short. In short, how this could possibly work would be that we would set up a generative AI prompt where people could come and ask questions about who a person shown in the exhibit was. However, this could create legal issues because they would be actual people that were actually deceased. Project River Otter seeks to do this same thing but it would be at the Aquarium and it would be River Otters talking. There would also just be an AI chatbot at the Library with no special theme. It was a very interesting first impression that I got from just listening to these projects. The reason that it was important that these projects be implemented was because the city’s objectives required that AI be implemented in the near future. The first official project that he wanted me to work on was generating an official AI guideline for what to and what not to do when using AI. I was able to make a pretty good first draft according to his own words but he said I should expand more on legal, ethical, and moral concerns. This was the most difficult part of the guidelines as I needed to think outside of the box to create moral situations in which someone could misuse generative AI. I actually got stuck on AI bias which I never considered before. It's important to ask the question that if the results of an AI query isn’t necessarily false then is it really a biased result. After that we went back and forth making small little changes and having a review session. The next and longest project of my internship focused on Copilot which is a generative AI that can integrate into Microsoft office products. Eddie wanted me to get a good understanding of Microsoft Copilot so that I could properly make an APM analysis of it as well as an EARTH document for it. Firstly, the APM analysis. An APM analysis is application performance monitoring, its where we put information about what the actual application or software we’re trying to add. In it we’ll describe what the application is, why we need it, who would be the head of it, who we need to contact in order to purchase or acquire it, how much it would initially cost us and how much it would cost after that, and who would use it. The APM analysis was fairly simple and I completed it with some help from Eddie. The only thing was that it took a while to complete because of the amount of research I had to put into it. The other document that I needed to work on was the EARTH document. It was pretty much the same information as the APM document but with the addition of how the software aligns with the city’s business objectives. I completed it in a reasonable amount of time and I was able to move onto gathering information about LTSC. LTSC stands for Long Term Servicing channel and it's a way for people and agencies to keep systems on a specific version without having to update to a later version.  Eddie wanted me to learn and research LTSC so that we could figure out when support for it ended. This would help us in deciding whether or not we wanted to purchase a new version. There was also Copilot Studio which he also wanted an APM and EARTH document for. Copilot Studio is another application that allows you to create custom AI chatbots or copilots that employees can then use for their own purpose to help them in their work. We wanted these copilots because it would allow employees to be more efficient and productive in theory. Getting those two documents completed took me a couple of weeks. The final and most recent project I worked on was researching different scanners that we could use going forward. It had to be a reasonable price and fulfill all of our criteria. Throughout my experience in this internship I employed a number of different skills in my work.</p>
<p>Skill Usage</p>
<p>When I was working on many of the physical tasks at Central Library I was forced to use my technical know-how and knowledge of wifi settings. While I was working with Eddie there wasn’t too much that I needed to know beforehand in order to complete this internship. ODU did help prepare me for this internship with all the papers they had tasked me with writing over the years. Specifically, PHIL355E a philosophy class I took here at ODU allowed me to think about situations in different ethical styles and that helped me to come up with different moral concerns. My criminology class helped me to think about various legal concerns to think about when crafting reports. One of the most interesting things to note is that I also learned while on the job. One of the main things that Eddie tried to introduce me to was the process of change management. However, even after he explained and showed it to me I wasn’t able to fully understand the concept. Thankfully, in my own independent studies I was studying for the Security+ and one of the subdomains was focused solely on the process of change management. Through studying this I was able to fully understand change management and I was able to make my first change. Change Management in the process that one must go through in order to make a change in a big organization. This is because in such a big organization even making a small change incorrectly can completely change or ruin a vast amount of services. I’d say ODU best prepared me for this line of work by allowing me to practice writing so many papers. There were of course other concepts that ODU prepared me for that I didn’t get to experience during my small time here. Switches and the management of them was a big one that we unfortunately didn’t get a chance to interact with. Also a lot of the security concepts were relevant in the initial security training they had me participate in. On the topic of whether I feel I fulfilled the objectives I initially set out for the answer would be a clear yes. There were four objectives that I set out to complete and I feel I hit three of them. To refresh your memory the four objectives that I wanted to complete during my time at this internship were: learning about system analysis, gaining experience in system analysis, gaining experience in the IT field, and gaining experience working with clients. </p>
<p>Objective Fulfillment</p>
<p>On the topic of learning about System Analysis I would say I most certainly accomplished that task. During my time shadowing Eddie and learning about several of his different projects I feel confident that I have a firm grasp of what a system analyst is. A system analyst is someone who not only diagnoses what’s wrong with a system but also finds ways to make that system better. On the topic of whether I gained experience in system analysis I would say that I also accomplished this task. In accordance with the second part of my own definition of a system analyst I was able to help create documents which helps in the process of implementing valuable changes that would change systems for the better. On the topic of whether I gained experience in the IT field I would say I spectacularly accomplished this task as well. Throughout my time in this internship I participated in many tasks a typical employee would consider IT. The software testing and update testing is direct testament to that. On the topic of whether I gained experience working with clients I would say I unfortunately failed in this regard. Unfortunately even though there were so many projects and tasks I got to work on none of them involved me directly interacting with a customer or client. However, next week Eddie is going to be absent for the whole of the week and he is putting me as the point of contact for all tasks next week. So I would be directly interacting with many of the clients. So this is technically fulfilled if we’re talking about the entirety of the internship but not if we’re only talking about the hours I have worked so far. Either way I do get to gain experience with dealing with clients. So in conclusion to the question of whether I feel I fulfilled my goals the answer would mostly be a yes. Next, I would like to talk about the most exciting and motivating parts of the internship. During my entire time there whenever I had a problem someone was always eager to help me. Not one time during the entirety of the internship was the work ever too overwhelming or something I didn't have the capability to do. There wasn’t a lot of pressure to get my work done and they were never “breathing down my neck” so to speak. The work was quite enjoyable and relatively simple to complete. Everyone in each department was so friendly and welcoming.  It was such a heartwarming experience to be there. They weren't treating me like a new hire they could shove all their work onto but as a valued member of their team they could teach so many new things too. It's almost like they knew exactly what my objectives were and tailored my experience to that. Also the fact that I can be hybrid was such a positive to this entire experience. I had never experienced remote work before this and I was so impressed with everything. From how they spoke with passion during every meeting to how they spoke in casual conversation it was such a positive experience. Eddie also was willing to pay for lunch twice during my experience. Also just being at such an impressive library was such a joy to me. When it comes to working there I have nothing but good things to say about it. Now, the most motivating parts of this internship would have to be when I learned of them being able to provide training and cover the cost of my certifications. During this summer I only had two objectives that I wanted to accomplish before I went back to school. I wanted to excel in this internship and receive an excellent recommendation from them that I could then use going forward to help get a job in cybersecurity. And I also wanted to successfully pass the security+ and obtain my certification. When I learned that I could possibly receive a $400 test just for working with them, my motivation skyrocketed. There were some downsides to this internship though. Whenever I had to go in I was set back $50 a day as I needed to lyft there to make it on time. This combined with the fact that I was struggling at the time made for a horrible experience in the first few weeks. However, it did get better once I received my laptop. The other downside was the process I had to go through in order to actually start working. It took multiple emails between multiple departments before I was even able to step into the building where I worked. Also, the fact that I had to make multiple trips back and forth to do fingerprinting and correct my I-9 was frustrating. I had to go back to the municipal center/courthouse three separate times which cost me my own money. Other than that there wasn’t really anything frustrating or annoying that I had to deal with. In my eyes there wasn't really a downside to this job. On the topic of the most challenging aspects of my internship, that would have to be the amount of research I had to do for some of these projects but in my personal opinion it wasn't that bad. There wasn’t really anything too challenging other than the first AI guidelines I had to draft up. That was just time consuming and it allowed me to think outside the box. </p>
<p>Recommendation</p>
<p>As for my own personal recommendation for any future interns that wish to try out this specific position. Go ahead and do it, it's a great way to get your foot in the door and if you sit in on many of the meetings you’ll get to learn a lot about IT in general. You’ll learn about the structure of a company and how they hire outside help in order to assist with specific projects. In regards to what you need to know I’d mainly like to suggest making sure you know how to research and complete writing assignments in a timely manner. They don’t like for you to stall or wait until the last minute.</p>
<p>Conclusion</p>
<p>In conclusion, let's discuss what exactly it is that I gained from this internship. I learned how to work as a team and communicate on a companywide scale. I learned how to get assistance from people especially if I feel that I can’t do it on my own. I learned how to apply my classroom book knowledge and translate that into real world situations. I learned how to collaborate my efforts with others and mesh my writing with their styles. I learned how to be independent without always being nagged to get work done. I learned how to complete assignments ahead of a deadline. I learned how to think outside of the box. I learned how to problem solve and appeal to different groups and types of people. Lastly, I learned that everything moves at the speed of government, which is to say it moves incredibly slow. On the topic of how I plan to use this experience moving forward in my studies. This fall will of course be my final semester at ODU and while I have thoroughly enjoyed my time here I am ready for a new chapter in my life. With the completion of this internship I am now confident that I can find a permanent job after college. There have been talks to extend my internship past this summer semester and even to offer me more of a part time job in the fall. I don't have any additional words on this but nevertheless it is something to be aware of. I will use the experience that I gained from this internship to properly demonstrate and showcase my skills to potential employers. After this semester I immediately plan to update my resume and Linkedin as well as begin putting in applications for a more permanent position. I believe that this is only the beginning of my career and I hope to use the experiences I have gained here to propel me further into a professional career not just in IT but in cybersecurity as well.</p>


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
        "https://summitctf.org/",
        "https://streamable.com/sffvjy"
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
