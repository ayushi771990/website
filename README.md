<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Sol Fab House | Premium Digital Printed Fabrics</title>
    <style>
        /* Minimal CSS Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
           .site-name {
            color: white;
            font-size: 2rem;
            font-weight: bold;
            padding: 1rem;
        }
        }
         
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            line-height: 1.6;
            color: rgb(75, 0, 130);
            background-color: #F0E6FA;
        }
        
        /* Header Styles */
        header {
            background-color: #F0E6FA;
            padding: 1.5rem 2rem;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        .logo {
            font-size: 1.8rem;
            font-weight: 700;
            color: rgb(75, 0, 130);
            text-decoration: none;
        }
        
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .nav-links {
            display: flex;
            list-style: none;
        }
        
        .nav-links li {
            margin-left: 2rem;
        }
        
        .nav-links a {
            text-decoration: none;
            color: rgb(75, 0, 130);
            font-weight: 500;
            transition: color 0.3s;
        }
        
        .nav-links a:hover {
            color: #000;
        }
        
        /* Hero Section */
        .hero {
            height: 70vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            background-image:  linear-gradient(rgba(0,0,0,0.1), rgba(0,0,0,0.1)), url('images/l.jpg');
            background-size: cover;
            background-position: center;
            color: white;
        }
        
        .hero-content h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            text-shadow: 1px 1px 3px rgba(0,0,0,0.5);
        }
        
        .hero-content p {
            font-size: 1.2rem;
            max-width: 600px;
            margin: 0 auto 2rem;
            text-shadow: 1px 1px 3px rgba(0,0,0,0.5);
        }
        
        .btn {
            display: inline-block;
            background-color: #fff;
            color: #333;
            padding: 0.8rem 1.8rem;
            text-decoration: none;
            border-radius: 4px;
            font-weight: 600;
            transition: all 0.3s;
        }
        
        .btn:hover {
            background-color: #333;
            color: #fff;
        }
        
        /* Main Content */
        .container {
            max-width: 1200px;
            margin: 4rem auto;
            padding: 0 2rem;
        }
        
        section {
            margin-bottom: 4rem;
        }
        
        h2 {
            font-size: 2rem;
            margin-bottom: 1.5rem;
            text-align: center;
        }
        
        /* Fabric Grid */
        .fabric-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 2rem;
        }
        
        .fabric-item {
            background-color: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        
        .fabric-item:hover {
            transform: translateY(-5px);
        }
        
        .fabric-img {
            height: 200px;
            background-size: cover;
            background-position: center;
        }
        
        .fabric-info {
            padding: 1.5rem;
        }
        
        .fabric-info h3 {
            margin-bottom: 0.5rem;
        }
        
        /* About Section */
        .about-section {
            display: flex;
            align-items: center;
            gap: 3rem;
            margin-top: 3rem;
        }

        .about-text {
            flex: 1;
        }

        .about-image {
            flex: 1;
            height: 400px;
            background-image: url('images/be.jpg');
            background-size: cover;
            background-position: center;
            border-radius: 8px;
        }
        
        /* Blog Preview */
        .blog-preview {
            background-image: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.3)), url('https://images.unsplash.com/photo-1563170424-310cb1d4a5f4?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            color: lavender;
            padding: 4rem 2rem;
            border-radius: 8px;
            text-align: center;
        }
        
        /* Contact Section */
        .contact {
            background-color: white;
            padding: 3rem;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            max-width: 600px;
            margin: 0 auto;
        }
        
        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 0.8rem;
            margin-bottom: 1rem;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-family: inherit;
        }
        
        .contact-form textarea {
            height: 150px;
        }
        
        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 4rem;
        }
        
        .social-links {
            margin: 1rem 0;
        }
        
        .social-links a {
            color: white;
            margin: 0 0.5rem;
            font-size: 1.2rem;
        }

        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
            .about-section {
                flex-direction: column;
            }
            .about-image {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <a href="#" class="logo">SOL FAB HOUSE</a>
            <ul class="nav-links">
               <li><a href="#" style="font-weight: bold;">Home</a></li>
<li><a href="#signature-collection" style="font-weight: bold;">Signature Collection</a></li>
<li><a href="#about" style="font-weight: bold;">About</a></li>
<li><a href="#blog" style="font-weight: bold;">Blog</a></li>
<li><a href="#contact" style="font-weight: bold;">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section class="hero">
        <div class="hero-content">
            <h1>Premium Digital Printed Fabrics</h1>
            <p>Custom-designed, high-quality textiles for fashion and interior design</p>
            <a href="#signature-collection" class="btn">Explore Signature Collection</a>
        </div>
    </section>
    
    <main class="container">
        <section id="signature-collection">
            <h2>Signature Collection</h2>
            <div class="fabric-grid">
                <div class="fabric-item">
                    <div class="fabric-img" style="background-image: url('images/ele.jpg');"></div>
                    <div class="fabric-info">
                        <h3>Botanical Elegance</h3>
                        <p>Luxury floral prints on premium silk</p>
                    </div>
                </div>
                
                <div class="fabric-item">
                    <div class="fabric-img" style="background-image: url('images/gem.jpg');"></div>
                    <div class="fabric-info">
                        <h3>Modern Geometry</h3>
                        <p>Bold contemporary patterns</p>
                    </div>
                </div>
                
                <div class="fabric-item">
                    <div class="fabric-img" style="background-image: url('images/at.jpg');"></div>
                    <div class="fabric-info">
                        <h3>Artisan Textures</h3>
                        <p>Handcrafted-inspired designs</p>
                    </div>
                </div>
                
                <div class="fabric-item">
                    <div class="fabric-img" style="background-image: url('images/lux.jpg');"></div>
                    <div class="fabric-info">
                        <h3>Minimalist Luxe</h3>
                        <p>Subtle sophistication in every thread</p>
                    </div>
                </div>
            </div>
        </section>
        
        <section id="about">
            <h2>About Sol Fab House</h2>
            <div class="about-section">
                <div class="about-text">
                    <p>At Sol Fab House, we blend innovative digital printing with sustainable practices to create exceptional textiles. Our Signature Collection represents the pinnacle of our craftsmanship - where timeless designs meet modern technology.</p>
                    <p>Each fabric is printed using eco-friendly pigments on responsibly sourced materials, ensuring both beauty and sustainability.</p>
                </div>
                <div class="about-image"></div>
            </div>
        </section>

        <section id="blog">
            <h2>From Our Journal</h2>
            <div class="blog-preview">
                <h3>Discover the Art of Digital Textile Printing</h3>
                <p>Coming soon: Expert insights on sustainable fabric production and design trends</p>
                <a href="#" class="btn" style="margin-top: 1rem;">Notify Me When Launched</a>
            </div>
        </section>
        
        <section id="contact">
            <h2>Work With Us</h2>
            <div class="contact">
                <form class="contact-form">
                    <input type="text" placeholder="Your Name" required>
                    <input type="email" placeholder="Your Email" required>
                    <input type="text" placeholder="Subject">
                    <textarea placeholder="Your Message" required></textarea>
                    <button type="submit" class="btn">Send Message</button>
                </form>
            </div>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2023 Sol Fab House. All rights reserved.</p>
        <div class="social-links">
            <a href="#">Instagram</a>
            <a href="#">Pinterest</a>
            <a href="#">Facebook</a>
        </div>
        <p>hello@solfabhouse.com | +1 (555) 987-6543</p>
    </footer>
</body>
</html>

