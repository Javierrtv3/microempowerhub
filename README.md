# microempowerhub
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>MicroEmpowerHub</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        section {
            padding: 2rem;
            text-align: center;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        .freelancers, .micro-business {
            display: flex;
            justify-content: space-around;
            margin-top: 2rem;
        }
        .freelancers div, .micro-business div {
            background-color: #fff;
            padding: 1rem;
            width: 45%;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .blog, .social-media {
            margin-top: 2rem;
            padding: 2rem;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .social-links a {
            margin: 0 10px;
            color: #4CAF50;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to MicroEmpowerHub</h1>
        <p>Empowering Freelancers and Microentrepreneurs Together</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#freelancers">Freelancers</a>
        <a href="#micro-business">Micro Business</a>
        <a href="#blog">Blog</a>
        <a href="#social-media">Social Media</a>
    </nav>

    <section id="home">
        <div class="container">
            <h2>About MicroEmpowerHub</h2>
            <p>MicroEmpowerHub is a platform where skilled freelancers can donate their time and expertise to help microentrepreneurs grow their businesses. It's all about giving back and making a difference in the entrepreneurial ecosystem.</p>
        </div>
    </section>

    <section id="freelancers">
        <div class="container freelancers">
            <div>
                <h3>For Freelancers</h3>
                <p>Donate your time and skills to help small business owners overcome challenges. Your expertise can make a significant impact in the growth of microenterprises.</p>
                <button>Join as a Freelancer</button>
            </div>
            <div>
                <img src="freelancers.jpg" alt="Freelancers collaborating" width="100%">
            </div>
        </div>
    </section>

    <section id="micro-business">
        <div class="container micro-business">
            <div>
                <img src="micro-business.jpg" alt="Microentrepreneurs at work" width="100%">
            </div>
            <div>
                <h3>For Micro Businesses</h3>
                <p>If you're a microentrepreneur looking for guidance, request the help you need to overcome hurdles in areas like marketing, finance, operations, and more. We are here to support you!</p>
                <button>Request Help</button>
            </div>
        </div>
    </section>

    <section id="blog">
        <div class="container blog">
            <h3>Blog</h3>
            <p>Stay updated with success stories, tips for freelancers, and insights on how microentrepreneurs are changing the world with your help.</p>
        </div>
    </section>

    <section id="social-media">
        <div class="container social-media">
            <h3>Follow Us</h3>
            <p>Connect with us on social media to stay informed and be part of our community.</p>
            <div class="social-links">
                <a href="https://facebook.com">Facebook</a>
                <a href="https://twitter.com">Twitter</a>
                <a href="https://instagram.com">Instagram</a>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2024 MicroEmpowerHub. All rights reserved.</p>
    </footer>

</body>
</html>
