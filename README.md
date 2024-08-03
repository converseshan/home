<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ravi Ramaseshan</title>
    <style>
        body {
            font-family: century-gothic, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            width: 80%;
            margin: 0 auto;
        }
        header {
            background-color: #f8f8f8;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            margin: 20px 0;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
        }
        section {
            padding: 20px 0;
        }
        footer {
            background-color: #f8f8f8;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ravi Ramaseshan</h1>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>Ravi is currently a Director of SaaS & Digital Operations at ServiceNow. He has around 18 years of industry experience and a track record of leading growth strategies and driving large-scale enterprise initiatives cross-functionally across GTM, product, operations, and finance. He has an extensive background in Cloud & SaaS and lead-to-cash lifecycles and his career includes stints at Atlassian and VMware, where he was responsible for the strategy, planning, and execution of several complex end-to-end transformations, M&A integrations, and product launches.</p>
            <p>Ravi has a bachelor's degree in engineering with an MBA from Rice University and is based in San Jose, CA. Outside of work, he loves traveling, hiking, and experimenting with cooking. He advises early growth startups on product & GTM strategy and helps a non-profit learning initiative for immigrant kids.</p>
        </section>
        <section id="blog">
            <h2>Blog</h2>
            <p>My old blog is in <a href="https://medium.com/@converseshan">Medium</a>. A new blog is coming soon...</p>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>The best way to reach me is via <a href="https://www.linkedin.com/in/raviramaseshan/">Linkedin</a>. You can also use the form below
            </p>
            <form action="https://formspree.io/f/mldrbavy" method="POST">
                <div>
                    <label for="name">Your Name </label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div>
                    <label for="email">Your Email </label>
                    <input type="email" id="email" name="email" required>
                </div>
                 <div>
                    <label for="subject">Your Subject </label>
                    <textarea id="subject" name="subject" rows="1" required></textarea>
                </div>
                <div>
                    <label for="message">Your Message </label>
                    <textarea id="message" name="message" rows="4" required></textarea>
                </div>
                <div>
                    <button type="submit">Send it!</button>
                </div>
            </form>
        </section>
    </div>    
    <hr>
    <hr>
    <footer>
        <p>&copy; August 2024 Ravi Ramaseshan</p>
    </footer>
</body>
</html>
