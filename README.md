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
        }
        nav a:hover, nav a:focus {
            color: #087F23;
        }
        .centered-content {
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            height: 100vh;
            background: linear-gradient(to bottom, #4CAF50 0%, #087F23 100%);
            color: white;
        }
        .centered-content > div {
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        #about, #skills, #proficiency {
            background-color: #181823;
            color: white;
            padding: 20px;
            margin-top: 50px;
        }
        #skills h2, #about h2, #proficiency h2 {
            margin-top: 0;
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
        <img src="https://via.placeholder.com/100" style="width: 100px; height: 100px; float: left; margin-right: 20px;">
        <p>Description about the user here...</p>
    </div>
    <div id="skills">
        <h2>Skills</h2>
        <canvas id="skillsChart"></canvas>
    </div>
    <div id="proficiency">
        <h2>Proficiency</h2>
        <p>This section is under construction. Check back soon!</p>
    </div>
    <script>
        var ctx = document.getElementById('skillsChart').getContext('2d');
        var myRadarChart = new Chart(ctx, {
            type: 'radar',
            data: {
                labels: ['Hacking', 'Creativity', 'Writing', 'Coding', 'System Analysis', 'Customer Service', 'Professionalism'],
                datasets: [{
                    label: 'Skill Level',
                    backgroundColor: 'rgba(52, 152, 219, 0.5)', // Example: semi-transparent blue
                    borderColor: '#3498db', // Solid blue
                    pointBackgroundColor: '#2980b9',
                    data: [90, 90, 90, 90, 90, 90, 90] // Example data
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
        });
    </script>
</body>
</html>
