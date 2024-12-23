<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tree Service Academy</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }
        header {
            background: linear-gradient(to right, #004d40, #00796b);
            color: white;
            padding: 50px 20px;
            text-align: center;
        }
        header h1 {
            font-size: 2.5rem;
            margin: 0;
        }
        header p {
            font-size: 1.2rem;
            margin-top: 10px;
        }
        nav {
            background-color: #00251a;
            display: flex;
            justify-content: space-around;
            padding: 10px 0;
        }
        nav a {
            color: white;
            font-size: 1rem;
            text-decoration: none;
            text-transform: uppercase;
            margin: 0 10px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            text-align: center;
            padding: 40px 20px;
            background: url('https://via.placeholder.com/1200x400') center/cover no-repeat;
            color: white;
        }
        .hero h2 {
            font-size: 2rem;
            margin-bottom: 15px;
        }
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }
        .hero .cta-button {
            background-color: #00796b;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 1rem;
            cursor: pointer;
        }
        .hero .cta-button:hover {
            background-color: #004d40;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
        }
        .section-title {
            text-align: center;
            margin-bottom: 30px;
            color: #004d40;
        }
        .courses {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .course-box {
            background-color: white;
            width: 30%;
            margin-bottom: 20px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .course-box img {
            width: 100%;
            border-radius: 8px;
            margin-bottom: 15px;
        }
        .course-box h3 {
            color: #004d40;
            margin-bottom: 10px;
        }
        .course-box p {
            font-size: 1rem;
            color: #666;
        }
        .course-box .cta-button {
            margin-top: 10px;
        }
        footer {
            background-color: #004d40;
            color: white;
            text-align: center;
            padding: 20px;
        }
        footer a {
            color: #80cbc4;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            nav {
                flex-wrap: wrap;
                justify-content: center;
            }
            .hero {
                padding: 20px;
            }
            .hero h2 {
                font-size: 1.8rem;
            }
            .hero p {
                font-size: 1rem;
            }
            .features, .courses {
                flex-direction: column;
                align-items: center;
            }
            .feature-box, .course-box {
                width: 90%;
            }
        }
    </style>
</head>
<body>

<!-- Navigation -->
<nav>
    <a href="#about">About</a>
    <a href="#courses">Courses</a>
    <a href="#contact">Contact</a>
</nav>

<!-- Header -->
<header>
    <h1>Tree Service Academy</h1>
    <p>Your path to a successful tree service business starts here.</p>
</header>

<!-- Hero Section -->
<section class="hero">
    <h2>Learn, Grow, and Build Your Tree Service Business</h2>
    <p>Our academy offers comprehensive courses to turn your tree service skills into a thriving business.</p>
    <button class="cta-button" onclick="window.location.href='#courses'">Explore Courses</button>
</section>

<!-- Main Content -->
<div class="container">
    <!-- Courses Section -->
    <section id="courses">
        <h2 class="section-title">Our Courses</h2>
        <div class="courses">
            <div class="course-box">
                <img src="https://via.placeholder.com/300x200" alt="Tree Climbing">
                <h3>Tree Climbing Mastery</h3>
                <p>Learn advanced climbing techniques and how to use climbing gear safely and effectively.</p>
                <button class="cta-button">Enroll Now</button>
            </div>
            <div class="course-box">
                <img src="https://via.placeholder.com/300x200" alt="Bucket Truck Operations">
                <h3>Bucket Truck Operations</h3>
                <p>Master the use of bucket trucks for efficient and safe tree access and trimming.</p>
                <button class="cta-button">Enroll Now</button>
            </div>
            <div class="course-box">
                <img src="https://via.placeholder.com/300x200" alt="Business Growth">
                <h3>Starting a Tree Service Business</h3>
                <p>Learn how to start, market, and grow a profitable tree service business.</p>
                <button class="cta-button">Enroll Now</button>
            </div>
        </div>
    </section>
</div>

<!-- Footer -->
<footer>
    <p>&copy; 2024 Tree Service Academy. All rights reserved. <a href="#privacy-policy">Privacy Policy</a></p>
</footer>

</body>
</html>
