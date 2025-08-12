# JOLINA-ENTERPRISES-
Online platform for goods trading 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jolina Enterprises</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f9f9f9;
            color: #333;
        }
        header {
            background: #2c3e50;
            color: white;
            padding: 1.2rem;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2rem;
        }
        nav {
            background: #34495e;
            padding: 0.5rem;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            max-width: 1000px;
            margin: auto;
            padding: 1.5rem;
        }
        .product {
            background: white;
            padding: 1rem;
            margin-bottom: 1rem;
            border-radius: 8px;
            box-shadow: 0px 2px 5px rgba(0,0,0,0.1);
        }
        .product img {
            max-width: 100%;
            border-radius: 5px;
        }
        .product h2 {
            margin: 0.5rem 0;
            color: #2c3e50;
        }
        .product p {
            margin: 0.5rem 0;
        }
        .buy-button {
            background: #27ae60;
            color: white;
            padding: 10px 15px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
        }
        .buy-button:hover {
            background: #219150;
        }
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Jolina Enterprises</h1>
        <p>Your trusted online store for quality products</p>
    </header>

    <nav>
        <a href="#products">Products</a>
        <a href="#payment">Payment</a>
        <a href="#contact">Contact</a>
    </nav>

    <main>
        <section id="products">
            <h2>Our Products</h2>

            <div class="product">
                <img src="https://via.placeholder.com/800x400" alt="Product Image">
                <h2>Sample Product</h2>
                <p>High quality and affordable price.</p>
                <p><strong>₦5,000</strong></p>
                <a class="buy-button" href="#payment">Buy Now</a>
            </div>

            <!-- You can copy & paste more product blocks like the one above -->
        </section>

        <section id="payment">
            <h2>Payment Method</h2>
            <p>We currently accept <strong>Bank Transfer & OPay</strong> only.</p>
            <p><strong>Bank Name:</strong> OPay</p>
            <p><strong>Account Name:</strong> Jolina Enterprises</p>
            <p><strong>Account Number:</strong> 6141617298</p>
            <p>After payment, send your proof of payment to our contact below.</p>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p><strong>Phone/WhatsApp:</strong> 07085421899</p>
            <p><strong>Email:</strong> jolinaenterprises@gmail.com</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Jolina Enterprises. All Rights Reserved.</p>
    </footer>
</body>
</html>
