<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Brian's Profile</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f4f8;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background-color: #ffffff;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #333;
        }
        nav {
            display: flex;
            gap: 20px;
        }
        nav a {
            text-decoration: none;
            color: #333;
        }
        .hero {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 50px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .hero-text {
            max-width: 500px;
        }
        .hero-text h1 {
            font-size: 36px;
            margin: 0;
        }
        .hero-text p {
            margin: 10px 0 20px;
            color: #666;
        }
        .features {
            display: flex;
            gap: 30px;
            margin: 20px 0;
        }
        .feature {
            background-color: #ffffff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            flex: 1;
        }
        .buttons {
            display: flex;
            gap: 20px;
        }
        .button {
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            color: #ffffff;
            background-color: #007bff;
            transition: background-color 0.3s;
        }
        .button:hover {
            background-color: #0056b3;
        }
        .images {
            display: flex;
            gap: 20px;
        }
        .image-container {
            position: relative;
            width: 300px;
            height: 400px;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        .image-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        .achievement {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background-color: rgba(0, 0, 0, 0.7);
            color: #ffffff;
            padding: 10px;
            text-align: center;
        }
        .profile {
            display: flex;
            align-items: center;
            padding: 20px;
            max-width: 800px;
            margin: 20px auto;
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        .profile img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            margin-right: 20px;
        }
        .profile-info {
            max-width: 600px;
        }
        .profile-info h2 {
            margin: 0;
            font-size: 24px;
        }
        .profile-info p {
            margin: 5px 0;
            color: #666;
        }
        .academic-journey {
            max-width: 800px;
            margin: 20px auto;
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
        }
        .academic-journey h3 {
            margin: 0 0 10px;
            font-size: 24px;
        }
        .course {
            margin-bottom: 20px;
        }
        .course h4 {
            margin: 0;
            font-size: 20px;
        }
        .course p {
            margin: 5px 0;
            color: #666;
        }
        .relevant-coursework {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
        }
        .course-item {
            background-color: #e7f1ff;
            border-radius: 5px;
            padding: 5px 10px;
            font-size: 14px;
        }
    </style>
</head>
<body>

<header>
    <div class="logo">Logo</div>
    <nav>
        <a href="#">Home</a>
        <a href="#">Portfolio</a>
        <a href="#">About</a>
    </nav>
    <button class="button">Contact us</button>
</header>

<section class="hero">
    <div class="hero-text">
        <h1>Welcome to Brian's Creations</h1>
        <p>Dive into a world of creativity and innovation. Explore Brian's portfolio to uncover unique designs and remarkable achievements.</p>
        <div class="features">
            <div class="feature">INNOVATIVE IDEAS</div>
            <div class="feature">EXPERT EXECUTION</div>
            <div class="feature">COLLABORATIVE APPROACH</div>
        </div>
        <div class="buttons">
            <button class="button">EXPLORE PORTFOLIO</button>
            <button class="button">CONTACT BRIAN</button>
        </div>
        <p>Follow on <a href="#" style="color: #007bff;">X</a></p>
    </div>
    <div class="images">
        <div class="image-container">
            <img src="https://media.istockphoto.com/id/1458679553/photo/group-of-high-school-students-using-laptop-in-library.jpg?s=1024x1024&w=is&k=20&c=wusTnR0DnuasxfYXh2YaHzPE9DcmaXzSdsFxcz3oFeQ=" alt="Students using laptop">
            <div class="achievement">Achievements
Recognized for excellence</div>
        </div>
        <div class="image-container">
            <img src="https://media.istockphoto.com/id/1057767656/photo/young-woman-working-at-home.jpg?s=612x612&w=0&k=20&c=zTEJ8ZL2f-_xCYyOAlhyMoV-Iggg4bTuS6EQDZklVJg=" alt="Woman working at home">
            <div class="achievement">Achievements
Recognized for excellence</div>
        </div>
    </div>
</section>

<section class="profile">
    <img src="https://via.placeholder.com/150" alt="Brian Keya">
    <div class="profile-info">
        <h2>Brian Keya</h2>
        <p>Creative Innovator</p>
        <p>With a passion for transforming ideas into impactful creations, I specialize in blending data-driven insights with artistic flair to craft compelling visual narratives and innovative solutions.</p>
        <p>Nairobi, Kenya</p>
        <p>+254 712 345 678</p>
        <p>brian@brianscreations.com</p>
        <p><a href="https://brianscreations.com" style="color: #007bff;">https://brianscreations.com</a></p>
    </div>
</section>

<section class="academic-journey">
    <h3>ACADEMIC JOURNEY</h3>
    <div class="course">
        <h4>BSc in Biostatistics</h4>
        <p>Jomo Kenyatta University of Agriculture & Technology (JKUAT)</p>
        <p>2023-2027</p>
        <p>Developed a strong foundation in statistical analysis, research methodology, and epidemiology.</p>
        <div class="relevant-coursework">
            <div class="course-item">Statistical Analysis</div>
            <div class="course-item">Research Methodology</div>
            <div class="course-item">Epidemiology</div>
            <div class="course-item">Data Visualization</div>
        </div>
    </div>
    <div class="course">
        <h4>ALX Data Analytics Program</h4>
        <p>ALX</p>
        <p>2025
