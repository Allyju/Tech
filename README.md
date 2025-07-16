# Tech

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>M_in_X.Tech | Software Solutions</title>
    <style>
        :root { --primary: #2563eb; --dark: #1e293b; --light: #f8fafc; --gray: #94a3b8; }
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Segoe UI', sans-serif; line-height: 1.6; color: var(--dark); background: var(--light); }
        .container { width: 90%; max-width: 1200px; margin: 0 auto; padding: 0 1rem; }
        header { background: white; box-shadow: 0 2px 10px rgba(0,0,0,0.1); position: fixed; width: 100%; z-index: 100; }
        header .container { display: flex; justify-content: space-between; align-items: center; padding: 1rem 0; }
        .logo { font-size: 1.5rem; font-weight: 700; color: var(--dark); }
        .logo span { color: var(--primary); }
        nav a { margin-left: 1.5rem; color: var(--dark); font-weight: 500; text-decoration: none; }
        nav a:hover { color: var(--primary); }
        section { padding: 4rem 0; }
        .hero { height: 100vh; display: flex; align-items: center; text-align: center; padding-top: 80px; background: linear-gradient(135deg, rgba(37,99,235,0.1) 0%, rgba(255,255,255,1) 100%); }
        h1, h2 { line-height: 1.2; }
        .hero h1 { font-size: 2.5rem; margin-bottom: 1rem; }
        .hero p { color: var(--gray); max-width: 600px; margin: 0 auto 2rem; }
        .btn { display: inline-block; background: var(--primary); color: white; padding: 0.8rem 1.5rem; border: none; border-radius: 4px; text-decoration: none; font-weight: 600; transition: all 0.3s ease; }
        .btn:hover { opacity: 0.9; transform: translateY(-2px); }
        .section-title { text-align: center; margin-bottom: 3rem; font-size: 2rem; }
        .section-title span { color: var(--primary); }
        .services-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 2rem; }
        .service { background: white; padding: 2rem; border-radius: 8px; box-shadow: 0 5px 15px rgba(0,0,0,0.05); text-align: center; transition: all 0.3s ease; }
        .service:hover { transform: translateY(-5px); box-shadow: 0 10px 25px rgba(0,0,0,0.1); }
        .service i { font-size: 2.5rem; color: var(--primary); margin-bottom: 1rem; }
        .contact-form { max-width: 500px; margin: 0 auto; }
        .contact-form input, .contact-form textarea { width: 100%; padding: 1rem; margin-bottom: 1rem; border: 1px solid #ddd; border-radius: 4px; font-family: inherit; }
        footer { background: var(--dark); color: white; padding: 2rem 0; text-align: center; }
        .social-links { margin-top: 1rem; }
        .social-links a { color: white; margin: 0 0.5rem; }
        @media (max-width: 768px) {
            header .container { flex-direction: column; }
            nav { margin-top: 1rem; }
            nav a { margin: 0 0.5rem; }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <a href="#" class="logo">M_in_<span>X</span>.Tech</a>
            <nav>
                <a href="#services">Services</a>
                <a href="#about">About</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h1>Custom <span>Tech Solutions</span></h1>
            <p>We design and develop software that helps businesses grow.</p>
            <a href="#contact" class="btn">Get Started</a>
        </div>
    </section>

    <section id="services" class="section">
        <div class="container">
            <h2 class="section-title">Our <span>Services</span></h2>
            <div class="services-grid">
                <div class="service">
                    <i class="fas fa-laptop-code"></i>
                    <h3>Software Design</h3>
                    <p>Custom solutions for your business needs</p>
                </div>
                <div class="service">
                    <i class="fas fa-globe"></i>
                    <h3>Web Development</h3>
                    <p>Modern responsive websites</p>
                </div>
                <div class="service">
                    <i class="fas fa-mobile-alt"></i>
                    <h3>Mobile Apps</h3>
                    <p>iOS and Android applications</p>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="section">
        <div class="container">
            <h2 class="section-title">About <span>Us</span></h2>
            <p style="text-align: center; max-width: 600px; margin: 0 auto;">We're a team of passionate developers creating digital solutions since 2020. Let's build something great together.</p>
        </div>
    </section>

    <section id="contact" class="section">
        <div class="container">
            <h2 class="section-title">Contact <span>Us</span></h2>
            <form class="contact-form">
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" required></textarea>
                <button type="submit" class="btn">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 M_in_X.Tech</p>
            <div class="social-links">
                <a href="#"><i class="fab fa-github"></i></a>
                <a href="#"><i class="fab fa-linkedin"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
            </div>
        </div>
    </footer>
</body>
</html>
