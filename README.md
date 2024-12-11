<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>منصة الاستباقيه</title>

	
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #d3d3d3; /* Light gray background */
        }
        .store-container {
            max-width: 1300px;
            margin: 20px auto;
            padding: 20px;
            background-color: #F4EEE9;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .product-container {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: center;
        }
        .product {
            display: flex;
            flex-direction: column;
            align-items: center;
            width: calc(33% - 20px);
            margin-bottom: 20px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            background-color: #f9f9f9;
        }
        .product img {
            width: 150px;
            border-radius: 5px;
            border: 2px solid #EE8D41;
            margin-bottom: 10px;
        }
        .product-details {
            text-align: center;
        }
        .product-details h3 {
            color: #333;
        }
        .product-actions button {
            padding: 10px 20px;
            background-color: #EE8D41;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .product-actions button:hover {
            background-color: #EE8D41;
        }
        .comments {
            margin-top: 30px;
        }
        .comments textarea {
            width: 100%;
            height: 100px;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            background-color: #fefefe;
        }
        .comments button {
            padding: 10px 20px;
            background-color: #28a745;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .comments button:hover {
            background-color: #218838;
        }
        .cart {
            text-align: center;
            margin-top: 20px;
        }
        .cart button {
            padding: 10px 20px;
            background-color: #ff9800;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .cart button:hover {
            background-color: #e68a00;
        }
		    <title>User Information Form</title>
  
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .form-container {
            background-color: #ffffff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 300px;
        }
        .form-container h2 {
            text-align: center;
            color: #007bff;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            font-weight: bold;
            margin-bottom: 5px;
        }
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 16px;
        }
        .form-group textarea {
            resize: none;
        }
        .form-group button {
            width: 100%;
            padding: 10px;
            background-color: #e68a00;
            color: white;
            border: none;
            border-radius: 4px;
            font-size: 16px;
            cursor: pointer;
        }
        .form-group button:hover {
            background-color: #e68a00;
        }
    </style>
</head>
<body>
    <div class="store-container">
        <h1 style="color: #E98E46; text-align: center;">منصة الاستباقيه</h1>

        <!-- Product List -->
        <div class="product-container">
            <div class="product">
                <img src="WhatsApp Image 2024-12-11 at 11.13.52 (1).jpeg" alt="Product 1">
                <div class="product-details">
                <h3>منشار ميكانيكي </h3>
                </div>
                <div class="product-actions">
                    <button onclick="addToCart('Product 1')">Add to Cart</button>
                </div>
            </div>

            <div class="product">
                <img src="WhatsApp Image 2024-12-11 at 11.13.52.jpeg" alt="Product 2">
                <div class="product-details">
                    <h3>منشار الصفائح الدائري</h3>
                </div>
                <div class="product-actions">
                    <button onclick="addToCart('Product 2')">Add to Cart</button>
                </div>
            </div>

            <div class="product">
                <img src="WhatsApp Image 2024-12-11 at 11.13.53.jpeg" alt="Product 3">
                <div class="product-details">
                    <h3>مقص هايدروليكي</h3>
                </div>
                <div class="product-actions">
                    <button onclick="addToCart('Product 3')">Add to Cart</button>
                </div>
            </div>

            <div class="product">
                <img src="WhatsApp Image 2024-12-11 at 11.13.54.jpeg" alt="Product 4">
                <div class="product-details">
                    <h3>خلاعه ثلاثيه</h3>
                </div>
                <div class="product-actions">
                    <button onclick="addToCart('Product 4')">Add to Cart</button>
                </div>
            </div>

            <div class="product">
                <img src="WhatsApp Image 2024-12-11 at 11.13.55 (1).jpeg" alt="Product 5">
                <div class="product-details">
                    <h3>فاتحة الأبواب الهايدروليكية 100 </h3>
                </div>
                <div class="product-actions">
                    <button onclick="addToCart('Product 5')">Add to Cart</button>
                </div>
            </div>

            <div class="product">
                <img src="WhatsApp Image 2024-12-11 at 11.13.55 (1).jpeg" alt="Product 6">
                <div class="product-details">
                    <h3>طارد الدخان </h3>
                </div>
                <div class="product-actions">
                    <button onclick="addToCart('Product 6')">Add to Cart</button>
                </div>
            </div>

            <div class="product">
                <img src="WhatsApp Image 2024-12-11 at 11.13.56 (1).jpeg" alt="Product 7">
                <div class="product-details">
                    <h3>شفاط ارضي </h3>
                </div>
                <div class="product-actions">
                    <button onclick="addToCart('Product 7')">Add to Cart</button>
                </div>
            </div>

            <div class="product">
                <img src="WhatsApp Image 2024-12-11 at 11.13.56 (1).jpeg" alt="Product 8">
                <div class="product-details">
                    <h3>قاذف رغوه S400</h3>
                </div>
                <div class="product-actions">
                    <button onclick="addToCart('Product 8')">Add to Cart</button>
                </div>
            </div>

            <div class="product">
                <img src="WhatsApp Image 2024-12-11 at 11.13.56.jpeg" alt="Product 9">
                <div class="product-details">
        <h3> 2.5 inch خرطوم إطفاء </h3>
                </div>
                <div class="product-actions">
                    <button onclick="addToCart('Product 9')">Add to Cart</button>
                </div>
            </div>

            <div class="product">
                <img src="WhatsApp Image 2024-12-11 at 11.13.57.jpeg" alt="Product 10">
                <div class="product-details">
                    <h3>فاتحة الأبواب</h3>
                </div>
                <div class="product-actions">
                    <button onclick="addToCart('Product 10')">Add to Cart</button>
                </div>
            </div>
        </div>

        <!-- View Cart Button -->
        <div class="cart">
            <button onclick="viewCart()">View My Cart</button>
        </div>

        <!-- Comments Section -->
        <div class="comments">
            <h2 style="color: #007bff;">Leave a Comment</h2>
            <textarea id="comment" placeholder="Write your comment here..."></textarea>
            <button onclick="submitComment()">Submit Comment</button>
        </div>
    </div>

    <script>
        let cart = [];

        function addToCart(product) {
            cart.push(product);
            alert(product + ' has been added to your cart!');
        }

        function viewCart() {
            if (cart.length > 0) {
                alert('Your cart contains: ' + cart.join(', '));
            } else {
                alert('Your cart is empty.');
            }
        }

        function submitComment() {
            const comment = document.getElementById('comment').value;
            if (comment) {
                alert('Thank you for your comment!');
                document.getElementById('comment').value = '';
            } else {
                alert('Please write a comment before submitting.');
            }
        }
    </script>
	<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <div class="form-container">
        <h2>Enter Your Details</h2>
        <form action="#" method="post">
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" placeholder="Enter your name" required>
            </div>
            <div class="form-group">
                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone" placeholder="Enter your phone number" required>
            </div>
            <div class="form-group">
                <label for="address">Address:</label>
                <textarea id="address" name="address" placeholder="Enter your address" rows="4" required></textarea>
            </div>
            <div class="form-group">
                <button type="submit">Submit</button>
            </div>
        </form>
    </div>

</body>
	<a href="mailto:estibaqia.com">Send email</a>
	
</html>
