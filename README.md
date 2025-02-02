<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ElectraSol Solutions | Solar & Automation Experts</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        /* Reset CSS */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        /* Header/Navbar */
        .navbar {
            background: #fff;
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            background: linear-gradient(45deg, #2ecc71, #1abc9c);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            display: flex;
            align-items: center;
        }

        .logo i {
            margin-right: 0.5rem;
            font-size: 2rem;
            color: #2ecc71;
        }

        .nav-links a {
            margin: 0 1rem;
            text-decoration: none;
            color: #333;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), 
                        url('https://images.unsplash.com/photo-1509391366360-2e959784a276?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            height: 80vh;
            background-size: cover;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: #fff;
            padding: 2rem;
        }

        /* Design Services Section */
        .design-services {
            padding: 5rem 5%;
            background: #fff;
        }

        .design-card {
            background: #f9f9f9;
            padding: 2rem;
            border-radius: 10px;
            margin: 1rem;
            text-align: center;
            transition: transform 0.3s;
        }

        .design-card:hover {
            transform: translateY(-5px);
        }

        /* Video Section */
        .video-section {
            padding: 5rem 5%;
            background: #f9f9f9;
            text-align: center;
        }

        .video-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .video-wrapper {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 aspect ratio */
            height: 0;
        }

        .video-wrapper iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: none;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar">
        <div class="logo">
            <i class="fas fa-solar-panel"></i>
            ElectraSol Solutions
        </div>
        <div class="nav-links">
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#designs">Designs</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div>
            <h1>Smart Energy Solutions for Tomorrow</h1>
            <p>Solar Power | Automation | CAD Designs</p>
            <button class="btn">Schedule a Free Audit</button>
        </div>
    </section>

    <!-- Design Services Section -->
    <section class="design-services" id="designs">
        <h2>Design Services</h2>
        <div class="design-card">
            <i class="fas fa-bolt fa-3x" style="color: #2ecc71;"></i>
            <h3>Converter Systems</h3>
            <p>Custom DC/AC converter designs for solar integration.</p>
        </div>
        <div class="design-card">
            <i class="fas fa-cogs fa-3x" style="color: #2ecc71;"></i>
            <h3>Home Automation</h3>
            <p>Smart energy management systems for residences.</p>
        </div>
        <div class="design-card">
            <i class="fas fa-drafting-compass fa-3x" style="color: #2ecc71;"></i>
            <h3>AutoCAD Designs</h3>
            <p>Commercial solar layout plans & structural CAD models.</p>
        </div>
    </section>

    <!-- Video Section -->
    <section class="video-section">
        <h2>See Us in Action</h2>
        <div class="video-container">
            <div class="video-wrapper">
                <iframe src="https://www.youtube.com/embed/VIDEO_ID_1" allowfullscreen></iframe>
            </div>
            <div class="video-wrapper">
                <iframe src="https://www.youtube.com/embed/VIDEO_ID_2" allowfullscreen></iframe>
            </div>
        </div>
    </section>
</body>
</html>
