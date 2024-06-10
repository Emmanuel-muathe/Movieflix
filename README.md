```html
<!DOCTYPE html>
<html>
<head>
    <title>Gramartins Enterprise</title>
</head>
<body>
    <h1>Welcome to Gramartins Enterprise - Your One-Stop Shop for Electronics</h1>
    
    <h2>Featured Products</h2>
    <ul>
        <li><a href="product.html">Laptops</a></li>
        <li><a href="product.html">Smartphones</a></li>
        <li><a href="product.html">Smart TVs</a></li>
        <li><a href="product.html">Headphones</a></li>
    </ul>
    
    <h3>Special Discounts</h3>
    <p>Get up to 50% off on selected items! Hurry, while stocks last.</p>
    
    <form action="checkout.html" method="post">
        <label for="quantity">Quantity:</label>
        <input type="number" id="quantity" name="quantity" min="1" max="10">
        <input type="submit" value="Add to Cart">
    </form>
    
    <h3>Login with</h3>
    <button onclick="googleLogin()">Login with Google</button>
    <button onclick="facebookLogin()">Login with Facebook</button>
    
    <footer>
        <p>Contact us at info@gramartins.com for any inquiries.</p>
    </footer>
    
    <script>
        function googleLogin() {
            // Connect with Google login API
            console.log("Logged in with Google");
        }
        
        function facebookLogin() {
            // Connect with Facebook login API
            console.log("Logged in with Facebook");
        }
    </script>
</body>
</html>
```
