<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EcoLife Solutions</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
        }
        header {
            background: #28a745;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav ul {
            background: #333;
            color: #fff;
            padding: 10px;
            display: flex;
            justify-content: center;
            list-style: none;
            margin: 0;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        .container {
            max-width: 1100px;
            margin: auto;
            overflow: hidden;
            padding: 20px;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .product {
            background: #fff;
            border: 1px solid #ddd;
            padding: 15px;
            border-radius: 5px;
            flex: 1 1 calc(30% - 20px);
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .product h3 {
            margin-top: 0;
        }
        .contact-form label {
            display: block;
            margin-top: 10px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            margin-bottom: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .contact-form button {
            background: #28a745;
            color: #fff;
            border: none;
            padding: 10px 15px;
            cursor: pointer;
            border-radius: 5px;
        }
    </style>
</head>
<body>
   
    <header>
        <h1>Welcome to EcoLife Solutions</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#products">Products</a></li>
            <li><a href="#contact">Contact Us</a></li>
        </ul>
    </nav>
    <div class="container">
        <section id="home">
            <h2>About Us</h2>
            <p>EcoLife Solutions is dedicated to providing eco-friendly products to help you live a sustainable and environmentally-conscious lifestyle.</p>
        </section>
        <section id="products">
            <h2>Our Products</h2>
            <div class="products">
                <div class="product">
                    <h3>Reusable Water Bottle</h3>
                    <p>Price: $15</p>
                    <p>Eco-friendly and durable water bottle for daily use.</p>
                </div>
                <div class="product">
                    <h3>Bamboo Toothbrush</h3>
                    <p>Price: $5</p>
                    <p>100% biodegradable toothbrush for eco-conscious oral care.</p>
                </div>
                <div class="product">
                    <h3>Organic Cotton Tote Bag</h3>
                    <p>Price: $10</p>
                    <p>Stylish and sustainable alternative to plastic bags.</p>
                </div>
                <div class="product">
                    <h3>Compostable Food Wrap</h3>
                    <p>Price: $12</p>
                    <p>Natural and reusable food wrap made from beeswax.</p>
                </div>
                <div class="product">
                    <h3>Solar Powered Charger</h3>
                    <p>Price: $30</p>
                    <p>Portable and renewable energy source for your devices.</p>
                </div>
            </div>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <form class="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="5" required></textarea>

                <button type="submit">Send</button>
            </form>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 EcoLife Solutions. All rights reserved.</p>
    </footer>
</body>

</html>
