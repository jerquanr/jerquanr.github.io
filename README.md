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
        #about, #skills, #proficiency {
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
        <p>Profile description here...</p>
    </div>
    <div id="skills">
        <h2>Skills</h2>
        <canvas id="skillsChart"></canvas>
    </div>
    <div id="proficiency">
        <h2>Proficiency</h2>
        <div class="proficiency-grid">
            <div class="proficiency-item"></div>
            <div class="proficiency-item"></div>
            <div class="proficiency-item"></div>
            <div class="proficiency-item"></div>
            <div class="proficiency-item"></div>
            <div class="proficiency-item"></div>
            <div class="proficiency-item"></div>
            <div class="proficiency-item"></div>
            <div class="proficiency-item"></div>
            <div class="proficiency-item"></div>
            <div class="proficiency-item"></div>
            <div class="proficiency-item"></div>
            <div class="proficiency-item"></div>
            <div class="proficiency-item"></div>
            <div class="proficiency-item"></div>
            <div class="proficiency-item"></div>
            <div class="proficiency-item"></div>
            <div class="proficiency-item"></div>
            <div class="proficiency-item"></div>
        </div>
    </div>
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
                    data: [90, 90, 90, 90, 90, 90, 90] // Example data
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
</body>
</html>
