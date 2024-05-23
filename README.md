
  
  <h1>Home Appliances Store</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to Our Home Appliances Store</h2>
        <p>Find the best appliances for your home.</p>
    </section>

    <section id="products">
        <h2>Our Products</h2>
        <div class="product">
            <img src="images/refrigerator.jpg" alt="Refrigerator">
            <h3>Refrigerator</h3>
            <p>High-quality refrigerators to keep your food fresh.</p>
        </div>
        <div class="product">
            <img src="images/washing-machine.jpg" alt="Washing Machine">
            <h3>Washing Machine</h3>
            <p>Efficient washing machines to make laundry easier.</p>
        </div>
        <div class="product">
            <img src="images/dishwasher.jpg" alt="Dishwasher">
            <h3>Dishwasher</h3>
            <p>Quiet and efficient dishwashers for sparkling clean dishes.</p>
        </div>
        <!-- Add more products as needed -->
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form action="submit_form_url" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Submit</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Home Appliances Store. All rights reserved.</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
