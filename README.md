
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <title>M_in_X.Tech</title>
    <style>
        :root { --blue: #2563eb; --dark: #1e293b; --light: #f8fafc }
        * { margin: 0; box-sizing: border-box }
        body { font-family: system-ui, sans-serif; line-height: 1.6; color: var(--dark); background: var(--light); max-width: 800px; margin: 0 auto; padding: 1rem }
        header { display: flex; justify-content: space-between; align-items: center; padding: 1rem 0; margin-bottom: 2rem }
        h1 { font-size: 2rem; margin: 2rem 0 1rem }
        h2 { color: var(--blue); margin: 1.5rem 0 0.5rem }
        a { color: var(--blue); text-decoration: none }
        nav a { margin-left: 1rem }
        .btn { display: inline-block; background: var(--blue); color: white; padding: 0.6rem 1.2rem; border-radius: 4px; margin: 1rem 0 }
        section { margin: 3rem 0 }
        footer { margin-top: 3rem; text-align: center }
        @media (max-width: 600px) {
            header { flex-direction: column }
            nav { margin-top: 1rem }
            nav a { margin: 0 0.5rem }
        }
    </style>
</head>
<body>
    <header>
        <a href="#" class="logo">M_in_X.Tech</a>
        <nav>
            <a href="#services">Services</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>
        <h1>Custom Software Solutions</h1>
        <p>We build fast, reliable web and mobile applications.</p>
        <a href="#contact" class="btn">Get Started</a>

        <section id="services">
            <h2>Services</h2>
            <p><strong>Web Development:</strong> Modern responsive websites</p>
            <p><strong>Software Design:</strong> Custom business solutions</p>
            <p><strong>Mobile Apps:</strong> iOS and Android development</p>
        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>Tech team delivering solutions since 2020. We focus on clean code and user-friendly design.</p>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <form>
                <input type="text" placeholder="Name" style="width:100%;padding:0.5rem;margin:0.5rem 0" required>
                <input type="email" placeholder="Email" style="width:100%;padding:0.5rem;margin:0.5rem 0" required>
                <textarea placeholder="Message" style="width:100%;padding:0.5rem;margin:0.5rem 0;min-height:100px" required></textarea>
                <button type="submit" class="btn">Send</button>
            </form>
        </section>
    </main>

    <footer>
        <p>© 2025 M_in_X.Tech</p>
        <p>
            <a href="https://github.com/yourusername" target="_blank">GitHub</a> |
            <a href="https://linkedin.com" target="_blank">LinkedIn</a> |
            <a href="mailto:contact@m_in_x.tech">Email</a>
        </p>
    </footer>
</body>
</html>
