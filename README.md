<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
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
        .about-section {
            display: flex;
            margin: 20px auto 0;
            width: 80%;
            align-items: center;
            position: relative;
            flex-wrap: wrap; /* Allow items to wrap if needed */
        }
        .about-img {
            flex-basis: 60%; /* Adjusts the base size of the image container for enlargement */
            max-width: 60%;
            position: absolute;
            left: -200px; /* Moves further to the left */
            border: 2px solid #000; /* Ensuring the border encapsulates the larger image */
        }
        .about-text {
            flex: 1;
            padding-left: 20px;
            margin-left: 55%; /* Adjusted to accommodate the larger image */
            padding: 20px;
        }
        .about-img img {
            width: 100%; /* Ensures the image fills its container */
            height: auto;
        }
        /* Style for the confirm button */
        .confirm-btn {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #007BFF;
            color: #FFFFFF;
            text-decoration: none;
            border-radius: 5px;
            cursor: pointer;
        }
        /* Hover effect for button */
        .confirm-btn:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="centered-content">
        <div>
            <h1>Welcome User</h1>
            <p>Welcome to my website. Feel free to look around at my life's achievements and aspirations.</p>
            <a href="#" class="confirm-btn">Confirm</a>
        </div>
    </div>
    <!-- About Section -->
    <div class="about-section">
        <div class="about-img">
            <img src="https://media.licdn.com/dms/image/D4E03AQFQjimbIykhSw/profile-displayphoto-shrink_200_200/0/1699579434374?e=2147483647&v=beta&t=YhfAaccuy1WIWXMbZyzFQBLAybPg8KN2rTa3UrWyKhQ" alt="About Me"> <!-- Increased image size -->
        </div>
        <div class="about-text">
            <p>Hey, this is my about me and here I will put words about me explaining my life and how we got here.</p>
        </div>
    </div>
</body>
</html>
