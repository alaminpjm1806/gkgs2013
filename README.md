<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our School</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background: linear-gradient(90deg, #0d47a1, #1976d2);
            color: white;
            padding: 1.5rem 0;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        header img {
            height: 50px;
            margin-right: 15px;
        }
        nav {
            background-color: #1565c0;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
            transition: background-color 0.3s;
        }
        nav a:hover {
            background-color: #1e88e5;
        }
        .container {
            padding: 2rem;
            max-width: 1200px;
            margin: auto;
        }
        section {
            margin-bottom: 2rem;
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        section h2 {
            color: #1565c0;
            margin-bottom: 1rem;
        }
        .slider {
            display: flex;
            overflow: hidden;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .slider img {
            width: 100%;
            animation: slide 15s infinite;
        }
        @keyframes slide {
            0% { transform: translateX(0); }
            20% { transform: translateX(-100%); }
            40% { transform: translateX(-200%); }
            60% { transform: translateX(-100%); }
            80% { transform: translateX(0); }
            100% { transform: translateX(-100%); }
        }
        .teachers, .news, .events {
            display: flex;
            gap: 2rem;
        }
        .card {
            flex: 1;
            padding: 1rem;
            border-radius: 8px;
            background-color: #e3f2fd;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #1565c0;
            color: white;
            text-align: center;
            padding: 1rem;
            position: relative;
            width: 100%;
            box-shadow: 0 -4px 8px rgba(0, 0, 0, 0.1);
        }
        iframe {
            width: 100%;
            height: 300px;
            border: 0;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <header>
        <img src="https://via.placeholder.com/50" alt="School Logo">
        <h1>Our School</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Us</a>
        <a href="#courses">Courses</a>
        <a href="#teachers">Teachers</a>
        <a href="#news">News</a>
        <a href="#events">Events</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <section id="home">
            <h2>Welcome</h2>
            <div class="slider">
                <img src="https://via.placeholder.com/1200x400/0d47a1/ffffff?text=Welcome+to+Our+School" alt="Welcome to Our School">
                <img src="https://via.placeholder.com/1200x400/1976d2/ffffff?text=High+Quality+Education" alt="High Quality Education">
                <img src="https://via.placeholder.com/1200x400/0d47a1/ffffff?text=Join+Us+Today" alt="Join Us Today">
            </div>
        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>Established in 1990, our school is dedicated to creating the best learning environment for our students.</p>
        </section>

        <section id="courses">
            <h2>Courses</h2>
            <p>We offer a variety of courses including Science, Arts, Commerce, and more.</p>
        </section>

        <section id="teachers">
            <h2>Teachers</h2>
            <div class="teachers">
                <div class="card">
                    <h3>John Doe</h3>
                    <p>Science Teacher</p>
                </div>
                <div class="card">
                    <h3>Jane Smith</h3>
                    <p>Math Teacher</p>
                </div>
                <div class="card">
                    <h3>Emily Johnson</h3>
                    <p>History Teacher</p>
                </div>
            </div>
        </section>

        <section id="news">
            <h2>News</h2>
            <div class="news">
                <div class="card">
                    <h3>School Wins Award</h3>
                    <p>Our school has been awarded the best school in the district.</p>
                </div>
                <div class="card">
                    <h3>New Library Opening</h3>
                    <p>We are excited to announce the opening of our new library.</p>
                </div>
            </div>
        </section>

        <section id="events">
            <h2>Events</h2>
            <div class="events">
                <div class="card">
                    <h3>Science Fair</h3>
                    <p>Join us for our annual science fair on June 15th.</p>
                </div>
                <div class="card">
                    <h3>Sports Day</h3>
                    <p>Come and participate in our sports day events on July 20th.</p>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Contact us: Our School, New York, USA. Phone: 123-456-7890</p>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3021.9271657842327!2d-74.0060!3d40.7128!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zNDAlNzAnNDYuMCJOIDc0wrAwMSczNy4xIlc!5e0!3m2!1sen!2sus!4v1628784986392!5m2!1sen!2sus" allowfullscreen="" loading="lazy"></iframe>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Our School. All rights reserved.</p>
    </footer>
</body>
</html>

