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
            font-size: 2.8rem;
            margin: 0;
        }
        header p {
            font-size: 1.2rem;
            margin-top: 10px;
        }
        nav {
            background-color: #00251a;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            color: white;
            margin: 0 15px;
            font-size: 1rem;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            padding: 20px;
            background: url('https://via.placeholder.com/1200x400') center/cover no-repeat;
            color: white;
        }
        .hero h2 {
            font-size: 2.5rem;
            margin: 0;
        }
        .hero p {
            font-size: 1.2rem;
            margin-top: 15px;
        }
        .hero .cta-button {
            background-color: #00796b;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 1rem;
            cursor: pointer;
            transition: background-color 0.3s ease;
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
        .features {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .feature-box {
            background-color: white;
            width: 30%;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .feature-box i {
            font-size: 2rem;
            color: #00796b;
            margin-bottom: 10px;
        }
        .feature-box h3 {
            font-size: 1.3rem;
            color: #004d40;
            margin-bottom: 10px;
        }
        .testimonials, .faculty {
            background-color: #e8f5e9;
            padding: 30px 20px;
            border-radius: 8px;
        }
        .testimonial, .faculty-member {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }
        .testimonial img, .faculty-member img {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            margin-right: 15px;
        }
        .testimonial p, .faculty-member p {
            font-size: 1rem;
            color: #333;
        }
        .pricing {
            text-align: center;
            margin-top: 30px;
        }
        .pricing .price {
            font-size: 2rem;
            color: #00796b;
            font-weight: bold;
        }
        footer {
            background-color: #004d40;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
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
            .features {
                flex-direction: column;
                align-items: center;
            }
            .feature-box {
                width: 90%;
            }
            .hero {
                flex-direction: column;
                text-align: center;
            }
            .hero img {
                width: 100%;
                margin-top: 20px;
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
    <div>
        <h2>Learn, Grow, and Build Your Tree Service Business</h2>
        <p>Our academy offers comprehensive courses to turn your tree service skills into a thriving business.</p>
        <button class="cta-button" onclick="window.location.href='#courses'">Explore Courses</button>
    </div>
</section>

<!-- Main Content -->
<div class="container">
    <!-- Features Section -->
    <h2 class="section-title">Why Choose Us?</h2>
    <div class="features">
        <div class="feature-box">
            <i class="fas fa-tree"></i>
            <h3>Expert Training</h3>
            <p>Learn from professionals with years of experience in the tree service industry.</p>
        </div>
        <div class="feature-box">
            <i class="fas fa-chart-line"></i>
            <h3>Proven Strategies</h3>
            <p>Get insights and strategies that guarantee business growth and success.</p>
        </div>
        <div class="feature-box">
            <i class="fas fa-handshake"></i>
            <h3>Business Support</h3>
            <p>Receive ongoing support to help you scale your business effectively.</p>
        </div>
    </div>

    <!-- Testimonials Section -->
    <div class="testimonials">
        <h2 class="section-title">What Our Students Say</h2>
        <div class="testimonial">
            <img src="https://via.placeholder.com/80" alt="Student">
            <p>"Tree Service Academy changed my life. I went from struggling to running a profitable business in less than a year!" - John D.</p>
        </div>
        <div class="testimonial">
            <img src="https://via.placeholder.com/80" alt="Student">
            <p>"The course is packed with practical advice and tools. Highly recommended!" - Sarah P.</p>
        </div>
    </div>

    <!-- Faculty Section -->
    <div class="faculty">
        <h2 class="section-title">Meet Our Instructors</h2>
        <div class="faculty-member">
            <img src="https://via.placeholder.com/80" alt="Instructor">
            <p><strong>Mark Johnson</strong> - Certified Arborist with 15 years of field experience.</p>
        </div>
        <div class="faculty-member">
            <img src="https://via.placeholder.com/80" alt="Instructor">
            <p><strong>Emily Smith</strong> - Business strategist and marketing expert specializing in tree services.</p>
        </div>
    </div>

    <!-- Pricing Section -->
    <div class="pricing">
        <h2 class="section-title">Course Pricing</h2>
        <p>Get lifetime access to all modules, resources, and updates.</p>
        <div class="price">$997 or 3 payments of $349</div>
        <button class="cta-button" onclick="window.location.href='https://www.paypal.com/paypalme/YourPayPalLinkHere'">
            Pay with PayPal
        </button>
        <button class="cta-button" onclick="window.location.href='https://buy.stripe.com/test_XXXXXXX'">
            Pay with Stripe
        </button>
    </div>
</div>

<!-- Footer -->
<footer>
    <p>&copy; 2024 Tree Service Academy. All rights reserved. <a href="#privacy-policy">Privacy Policy</a></p>
</footer>

</body>
</html>
