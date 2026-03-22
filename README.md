# Ex02 Commercial Website
## Date:

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bike Spares Shop</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Navbar -->
  <div class="navbar">
    <h1>BIKE SPARES</h1>
    <div class="nav-links">
      <a href="#">Login</a>
      <a href="#">Cart</a>
      <a href="#">Contact</a>
    </div>
  </div>

  <!-- Products -->
  <div class="container">

    <div class="card">
      <img src="MtThunder3ProIsleOfManMattRed1.webp" alt="Helmet">
      <h3>Helmet</h3>
      <p class="price">$120</p>
      <button class="btn" onclick="addToCart('Helmet')">Add to Cart</button>
    </div>

    <div class="card">
      <img src="images.jpg" alt="Brake Pads">
      <h3>Brake Pads</h3>
      <p class="price">$40</p>
      <button class="btn" onclick="addToCart('Brake Pads')">Add to Cart</button>
    </div>
    <div class="card">
      <img src="two-wheeler-royal-enfield-engine-oil.jpg" alt="Engine Oil">
      <h3>Engine Oil</h3>
      <p class="price">$25</p>
      <button class="btn" onclick="addToCart('Engine Oil')">Add to Cart</button>
    </div>

    <div class="card">
      <img src="images (1).jpg" alt="Tyre">
      <h3>Tyre</h3>
      <p class="price">$150</p>
      <button class="btn" onclick="addToCart('Tyre')">Add to Cart</button>
    </div>
  </div>

  <script>
    function addToCart(product) {
      alert(product + " added to cart");
    }
  </script>

</body>
</html>

```
```
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f4f4f4;
}

/* Navbar */
.navbar {
  background: #0d1b2a;
  color: white;
  padding: 15px 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.navbar h1 {
  margin: 0;
}

.nav-links a {
  color: white;
  margin-left: 15px;
  text-decoration: none;
}

/* Product Grid */
.container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  padding: 20px;
}

.card {
  background: white;
  width: 250px;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

.card img {
  width: 150px;
  height: 150px;
  object-fit: cover;
}

.card h3 {
  margin: 10px 0;
}

.price {
  color: #333;
  margin-bottom: 10px;
}

.btn {
  background: #fca311;
  border: none;
  padding: 10px 15px;
  cursor: pointer;
  border-radius: 5px;
}

.btn:hover {
  background: #ffba08;
}

```


## OUTPUT
<img width="1919" height="1142" alt="Screenshot 2026-03-22 203924" src="https://github.com/user-attachments/assets/4c6f54c9-7dc4-45bf-aba8-b02696b4aaa2" />

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
