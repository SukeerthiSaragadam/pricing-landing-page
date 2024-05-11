# pricing-landing-page
Frontend web development project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pricing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Our Pricing</h1>
        <nav>
            <ul>
                <li><a href="#pricing-plans">Pricing Plans</a></li>
                <li><a href="#features">Features</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="pricing-plans">
        <h2>Pricing Plans</h2>
        <div class="pricing-plan">
            <h3>Basic</h3>
            <p class="price">$19.99/month</p>
            <ul class="features">
                <li>Feature 1</li>
                <li>Feature 2</li>
                <li>Feature 3</li>
            </ul>
            <a href="#" class="btn">Choose Plan</a>
        </div>
        <div class="pricing-plan">
            <h3>Standard</h3>
            <p class="price">$29.99/month</p>
            <ul class="features">
                <li>Feature 1</li>
                <li>Feature 2</li>
                <li>Feature 3</li>
                <li>Feature 4</li>
            </ul>
            <a href="#" class="btn">Choose Plan</a>
        </div>
        <div class="pricing-plan">
            <h3>Premium</h3>
            <p class="price">$49.99/month</p>
            <ul class="features">
                <li>Feature 1</li>
                <li>Feature 2</li>
                <li>Feature 3</li>
                <li>Feature 4</li>
                <li>Feature 5</li>
                <li>Feature 6</li>
            </ul>
            <a href="#" class="btn">Choose Plan</a>
        </div>
    </section>

    <section id="features">
        <h2>Features</h2>
        <ul>
            <li>Feature 1</li>
            <li>Feature 2</li>
            <li>Feature 3</li>
            <li>Feature 4</li>
            <li>Feature 5</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <form action="#">
            <input type="text" placeholder="Name">
            <input type="email" placeholder="Email">
            <textarea placeholder="Message"></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Pricing Page. All rights reserved.</p>
    </footer>
</body>
</html>
