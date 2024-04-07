<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome Page</title>
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

        /* New styles for the About section */
        .about-section {
            display: flex; /* Using Flexbox for the layout */
            margin: 20px auto 0; /* Adds margin on top and centers horizontally */
            width: 80%; /* Adjust based on preference */
            align-items: center; /* Aligns items vertically center */
        }

        .about-img {
            flex: 1; /* Takes up 1/2 of the flex container */
            max-width: 50%; /* Limits image container width */
        }

        .about-text {
            flex: 1; /* Takes up the remaining space */
            padding-left: 20px; /* Adds some space between the image and the text */
        }

        /* Responsive Image */
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
            <img src="https://i.pinimg.com/736x/2d/e5/84/2de584ca0fd15ac96551fc8e08422bee.jpg" alt="About Me">
        </div>
        <div class="about-text">
            <p>Made last it seen went no just when of by. Occasional entreaties comparison me difficulty so themselves. At brother inquiry of offices without do my service. As particular to companions at sentiments. Weather however luckily enquire so certain do. Aware did stood was day under ask. Dearest affixed enquire on explain opinion he. Reached who the mrs joy offices pleased. Towards did colonel article any parties.</p>
        </div>
    </div>
</body>
</html>
