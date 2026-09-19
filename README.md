<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Web Design</title>
    <style>
        /* CSS Styling */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f7f6;
            color: #333;
            line-height: 1.6;
        }

        /* Navigation Bar */
        header {
            background-color: #ffffff;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 1000;
        }

        .nav-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #007bff;
        }

        .nav-links {
            list-style: none;
            display: flex;
        }

        .nav-links li {
            margin-left: 20px;
        }

        .nav-links a {
            text-decoration: none;
            color: #555;
            font-weight: 500;
            transition: color 0.3s;
        }

        .nav-links a:hover {
            color: #007bff;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #007bff, #00c6ff);
            color: white;
            height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 0 20px;
            margin-top: 60px;
        }

        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 20px;
            margin-bottom: 30px;
            max-width: 600px;
        }

        .btn {
            background-color: white;
            color: #007bff;
            padding: 12px 30px;
            border: none;
            border-radius: 25px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            text-decoration: none;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }

        /* Features/Services Section */
        .services {
            max-width: 1200px;
            margin: 80px auto;
            padding: 0 20px;
            text-align: center;
        }

        .services h2 {
            font-size: 36px;
            margin-bottom: 40px;
            position: relative;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .card {
            background: white;
            padding: 40px 20px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            transition: transform 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card h3 {
            margin-bottom: 15px;
            color: #007bff;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 14px;
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <header>
        <div class="nav-container">
            <div class="logo">MyWebsite</div>
            <ul class="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Khush Amdeed Hamari Website Par</h1>
        <p>Hum aapke business ke liye behtareen aur responsive web designs banate hain jo har device par perfect chalti hain.</p>
        <a href="#" class="btn">Shuru Karen</a>
    </section>

    <!-- Services Section -->
    <section class="services">
        <h2>Hamari Khidmaat</h2>
        <div class="services-grid">
            <div class="card">
                <h3>Web Design</h3>
                <p>Khubsoorat aur modern layouts jo users ko pasand aayen.</p>
            </div>
            <div class="card">
                <h3>Development</h3>
                <p>Fast aur secure coding taake aapki website smooth chale.</p>
            </div>
            <div class="card">
                <h3>SEO Optimization</h3>
                <p>Google par top rank haasil karne ke liye behtareen SEO.</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 MyWebsite. All Rights Reserved.</p>
    </footer>

</body>
</html>
