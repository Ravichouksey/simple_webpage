<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Your product or service description here.">
    <meta name="keywords" content="landing page, product, service, call to action">
    <title>Landing Page</title>
  
    <style>

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}
a {
    text-decoration: none;
    color: inherit;
}

/* Header and Navigation */
header {
    background: #f4f4f4;
    padding: 1rem;
    text-align: center;
}
nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 1rem;
}
nav .logo {
    font-size: 1.5rem;
    font-weight: bold;
}
nav ul {
    list-style: none;
    display: flex;
}
nav ul li {
    margin-left: 1rem;
}
nav ul li a {
    color: #333;
}

/* Hero Section */
.hero {
    padding: 2rem;
    background: #007bff;
    color: white;
}
.hero h1 {
    font-size: 2rem;
    margin-bottom: 0.5rem;
}
.hero p {
    font-size: 1.2rem;
    margin-bottom: 1rem;
}
.cta-button {
    background: #ff5722;
    color: white;
    padding: 0.75rem 1.5rem;
    border-radius: 5px;
    font-weight: bold;
}

/* Contact Section */
main {
    padding: 1rem;
}
.contact-form {
    max-width: 600px;
    margin: 0 auto;
    background: #f9f9f9;
    padding: 1.5rem;
    border-radius: 8px;
}
.contact-form label {
    display: block;
    margin-bottom: 0.5rem;
}
.contact-form input, .contact-form textarea {
    width: 100%;
    padding: 0.75rem;
    margin-bottom: 1rem;
    border: 1px solid #ddd;
    border-radius: 5px;
}
.submit-button {
    background: #007bff;
    color: white;
    padding: 0.75rem;
    border: none;
    border-radius: 5px;
    font-size: 1rem;
}

/* Footer */
footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 1rem;
    position: absolute;
    bottom: 0;
    width: 100%;
}

/* Responsive Design */
@media (max-width: 768px) {
    .hero h1 {
        font-size: 1.5rem;
    }
    .hero p {
        font-size: 1rem;
    }
}
</style>
    
    
    
</head>
<body>
    <header>
        <nav>
            <a href="#home" class="logo">MyBrand</a>
            <ul>
                <li><a href="#contact">Contact</a></li>
               

            </ul>
        </nav>
        <div class="hero">
            <h1>Welcome to MyProduct</h1>
            <p>Your solution for [brief benefit or feature].</p>
            <a href="#contact" class="cta-button">Get Started</a>
        </div>
    </header>
    <main>
        <section id="contact">
            <h2>Contact Us</h2>
            <form action="#" method="post" class="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>
                
                <button type="submit" class="submit-button">Send Message</button>
            </form>
        </section>
    </main>
   
</body>
</html>
