<html lang="en">
<head>
    <meta charset="UTF-8">
	@@ -33,21 +34,18 @@
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
	@@ -59,27 +57,25 @@
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
        #contact {
            display: grid;
	@@ -126,65 +122,43 @@
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
            <div class="proficiency-item"></div>
        </div>
    </div>
        <div id="contact">
        <h2>Contact</h2>
        <form action="submit_form.php" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email">
            <label for="subject">Subject:</label>
            <input type="text" id="subject" name="subject">
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4"></textarea>
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
