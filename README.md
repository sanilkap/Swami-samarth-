# Swami-samarth-
श्री स्वामी समर्थ 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Swami Samarth Merchandise</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        .header {
            background-color: #ff9800;
            color: white;
            padding: 15px;
            font-size: 24px;
        }
        .container {
            padding: 20px;
        }
        .product {
            display: inline-block;
            width: 45%;
            margin: 10px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        img {
            width: 100%;
            max-width: 200px;
        }
        .contact {
            background-color: #f1f1f1;
            padding: 20px;
            margin-top: 20px;
        }
        .billing {
            background-color: #fff3e0;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="header">Swami Samarth Merchandise</div>
    <div class="container">
        <h2>Our Products</h2>
        <div class="product">
            <img src="swami-idol.jpg" alt="Swami Samarth Idol">
            <p>Swami Samarth Idol - ₹500</p>
        </div>
        <div class="product">
            <img src="swami-pendant.jpg" alt="Swami Samarth Pendant">
            <p>Swami Samarth Pendant - ₹250</p>
        </div>
    </div>
    <div class="billing">
        <h3>Billing Information</h3>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br><br>
            <label for="address">Address:</label>
            <input type="text" id="address" name="address" required><br><br>
            <label for="phone">Phone:</label>
            <input type="tel" id="phone" name="phone" required><br><br>
            <label for="payment">Payment Method:</label>
            <select id="payment" name="payment">
                <option value="credit">Credit Card</option>
                <option value="debit">Debit Card</option>
                <option value="upi">UPI</option>
            </select><br><br>
            <p>Pay via UPI: <a href="upi://pay?pa=merchant@upi&pn=SwamiSamarthStore&mc=1234&tid=9876543210&tr=123456&tn=OrderPayment&am=&cu=INR">Click here to pay</a></p>
            <button type="submit">Submit</button>
        </form>
    </div>
    <div class="contact">
        <h3>Contact Us</h3>
        <p>Email: info@swamisamarthstore.com</p>
        <p>Phone: +91 9876543210</p>
    </div>
</body>
</html>
