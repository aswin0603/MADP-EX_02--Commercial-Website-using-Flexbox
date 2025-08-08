# Ex02 Commercial Website
## Date: 08-08-2025

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM:
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
### index.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta
      charset="UTF-8"
      name="viewport"
      content="width=device-width, initial-scale=1.0"
    />
    <title>FreshCart | Your Online Grocery Store</title>
    <link rel="stylesheet" href="style.css" />
  </head>

  <body>
    <div class="navbar">
      <div class="logo"><h2>FreshCart</h2></div>
      <nav>
        <a href="#">Home</a>
        <a href="#categories">Categories</a>
        <a href="#products">Products</a>
        <a href="#testimonials">Reviews</a>
        <a href="#">My Cart</a>
        <a href="#newsletter">Subscribe</a>
      </nav>
    </div>

    <section class="hero-section">
      <div class="hero-overlay"></div>
      <div class="hero-content">
        <h1>Fresh & Fast Groceries<br /><span>Delivered to Your Door</span></h1>
        <p>
          Shop quality produce, daily essentials, and pantry staples from the
          comfort of your home.
        </p>
        <a class="cta-btn" href="#products">Start Shopping</a>
      </div>
    </section>

    <section class="quote-section">
      <div class="quote-body">
        <h2 class="quote">“A good meal begins with good ingredients.”</h2>
        <p class="meaning">
          And we bring them straight to your kitchen — fresh, fast, and
          affordably.
        </p>
        <p class="author">~ FreshCart Philosophy</p>
      </div>
    </section>

    <section class="section1" id="categories">
      <div class="section1-div">
        <h4 class="small-title">Browse</h4>
        <h1 class="title">product categories</h1>
        <p class="section1-paragraph">
          From farm-fresh fruits to dairy and bakery, explore a wide range of
          everyday groceries.
        </p>
      </div>
      <div class="image-row">
        <img src="./images/fruits.jpg" alt="Fruits" />
        <img src="./images/vegetables.jpg" alt="Vegetables" />
        <img src="./images/dairy.jpg" alt="Dairy" />
        <img src="./images/bakery.jpg" alt="Bakery" />
      </div>
    </section>

    <section class="sidebysidesec" id="deals">
      <div class="section2">
        <h2>Seasonal Offers</h2>
        <p>
          Enjoy exclusive discounts on in-season produce and pantry favorites.
          Check back every week for fresh deals curated just for you.
        </p>
      </div>
    </section>

    <section class="product-grid" id="products">
      <h2 class="title">Our Fresh Picks</h2>
      <div class="product-grid-container">
        <div class="product-card">
          <img src="./images/tomatoes.jpg" alt="Tomato" />
          <h3>Tomato</h3>
          <p class="product-description">
            Fresh, juicy red tomatoes perfect for cooking and salads.
          </p>
          <p class="product-price">₹25/kg</p>
        </div>
        <div class="product-card">
          <img src="./images/potatoes.jpg" alt="Potato" />
          <h3>Potato</h3>
          <p class="product-description">
            All-purpose potatoes rich in starch and taste.
          </p>
          <p class="product-price">₹20/kg</p>
        </div>
        <div class="product-card">
          <img src="./images/onions.jpg" alt="Onion" />
          <h3>Onion</h3>
          <p class="product-description">
            Essential kitchen staple, flavorful and aromatic.
          </p>
          <p class="product-price">₹30/kg</p>
        </div>
        <div class="product-card">
          <img src="./images/apple.jpg" alt="Apple" />
          <h3>Apple</h3>
          <p class="product-description">
            Crisp, sweet apples packed with nutrients and flavor.
          </p>
          <p class="product-price">₹120/kg</p>
        </div>
        <div class="product-card">
          <img src="./images/banana.jpg" alt="Banana" />
          <h3>Banana</h3>
          <p class="product-description">
            Naturally sweet bananas, ideal for snacks or smoothies.
          </p>
          <p class="product-price">₹45/dozen</p>
        </div>
        <div class="product-card">
          <img src="./images/carrots.jpg" alt="Carrot" />
          <h3>Carrot</h3>
          <p class="product-description">
            Crunchy, orange carrots rich in vitamin A.
          </p>
          <p class="product-price">₹35/kg</p>
        </div>
        <div class="product-card">
          <img src="./images/coriander.jpg" alt="Coriander" />
          <h3>Coriander</h3>
          <p class="product-description">
            Fresh green coriander leaves to garnish your dishes.
          </p>
          <p class="product-price">₹10/bunch</p>
        </div>
        <div class="product-card">
          <img src="./images/rice.jpg" alt="Rice" />
          <h3>Basmati Rice</h3>
          <p class="product-description">
            Long grain basmati rice, aromatic and fluffy when cooked.
          </p>
          <p class="product-price">₹90/kg</p>
        </div>
        <div class="product-card">
          <img src="./images/wheat.jpg" alt="Wheat Flour" />
          <h3>Wheat Flour</h3>
          <p class="product-description">
            Stone-ground whole wheat flour for healthy chapatis.
          </p>
          <p class="product-price">₹45/kg</p>
        </div>
        <div class="product-card">
          <img src="./images/dairy.jpg" alt="Milk" />
          <h3>Fresh Milk</h3>
          <p class="product-description">
            Full cream milk sourced from local dairies.
          </p>
          <p class="product-price">₹60/litre</p>
        </div>
        <div class="product-card">
          <img src="./images/egg.jpg" alt="Eggs" />
          <h3>Eggs</h3>
          <p class="product-description">
            Farm-fresh eggs, packed with protein and nutrients.
          </p>
          <p class="product-price">₹70/dozen</p>
        </div>
        <div class="product-card">
          <img src="./images/chilli.jpg" alt="Green Chilli" />
          <h3>Green Chilli</h3>
          <p class="product-description">
            Spicy and fresh green chillies to add some heat.
          </p>
          <p class="product-price">₹15/100g</p>
        </div>
      </div>
    </section>

    <section class="reviews" id="testimonials">
      <h4 class="small-title">customer voices</h4>
      <h1 class="title">what people are saying</h1>
      <div class="review-grid">
        <div class="review-item">
          <p class="review-text">
            FreshCart has made my weekly grocery shopping effortless. Always
            fresh!
          </p>
          <span class="review-author">– Anjali M., Bengaluru</span>
        </div>
        <div class="review-item">
          <p class="review-text">
            Their delivery is super fast and the veggies are farm-fresh every
            time.
          </p>
          <span class="review-author">– Vikram S., Chennai</span>
        </div>
        <div class="review-item">
          <p class="review-text">
            I love their offers and the quality. Highly recommended!
          </p>
          <span class="review-author">– Tara K., Mumbai</span>
        </div>
      </div>
    </section>

    <section class="section1" id="newsletter">
      <div class="section1-div">
        <h4 class="small-title">Subscribe</h4>
        <h1 class="title">join our newsletter</h1>
        <p class="section1-paragraph">
          Get the latest deals, recipes, and grocery tips delivered to your
          inbox weekly.
        </p>
        <form action="#" method="post" class="newsletter-form">
          <input type="email" placeholder="Enter your email" required />
          <button type="submit" class="cta-btn">Subscribe</button>
        </form>
      </div>
    </section>

    <footer class="footer">
      <div class="footer-content">
        <div class="footer-left">
          <div class="footer-logo-text">
            <p class="footer-text">
              FreshCart is your trusted grocery partner, delivering quality and
              convenience at your doorstep.
            </p>
          </div>
        </div>
        <div class="footer-columns">
          <div class="footer-column">
            <h4>Quick Links</h4>
            <a href="#">Home</a>
            <a href="#">View Products</a>
            <a href="#">Contact Us</a>
          </div>
        </div>
      </div>
      <hr class="centered-line" />
      <div class="footer-bottom">
        <p>© 2025 FreshCart. All rights reserved.</p>
        <div class="footer-links">
          <a href="#">Privacy Policy</a>
          <a href="#">Terms & Conditions</a>
        </div>
      </div>
    </footer>
  </body>
</html>
```

### style.css:
```css
@import url("https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100..900&family=Roboto:ital,wght@0,100..900&display=swap");

:root {
  --primary: hsla(126, 93%, 62%, 0.852);
  --white: #ffffff;
  --button-hover: #83f862e9;
  --black-txt: #000000;
  --hero-overlay: rgba(20, 20, 30, 0.4);
  --soft-bg: #dcf7dd;
  --soft-grey: #5f5f5f;
  --rounded: 1.4rem;
  --shadow: 0 0.25rem 1.5rem rgba(0, 0, 0, 0.1);
  --max-section-width: 90%;
  --section-padding: 3rem 2rem;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background: var(--white);
  max-width: 100%;
  overflow-x: hidden;
}

html {
  max-width: 100%;
  margin-top: 7rem;
  overflow-x: hidden;
  scroll-behavior: smooth;
  scroll-padding-top: calc(5rem + 2rem);
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Poppins", sans-serif;
}

p {
  font-family: "Roboto", sans-serif;
}

span {
  font-style: italic;
  color: var(--primary);
}

a {
  text-decoration: none;
  font-family: "Roboto", sans-serif;
}

a:hover {
  text-decoration: underline;
}

section {
  width: var(--max-section-width);
  padding: var(--section-padding);
  margin: 0 auto 6rem auto !important;
  overflow-x: hidden;
  overflow-y: hidden;
  max-width: 90%;
}

.small-title {
  font-size: 1.5rem;
  text-align: center;
  text-transform: uppercase;
  padding-bottom: 1rem;
  color: var(--soft-grey) !important;
}

.title {
  text-transform: uppercase;
  text-align: center;
  font-size: 3rem;
  padding-bottom: 1.5rem;
  font-weight: 800;
}

.quote-section {
  margin: 0 auto;
  height: auto;
  max-height: 100vh;
}

.quote,
.author,
.meaning {
  text-align: center;
}

.quote {
  line-height: 1.5;
  padding-bottom: 2rem;
}

.meaning {
  padding-bottom: 2rem;
  font-weight: 400;
  font-size: 1.2rem !important;
  line-height: 2;
  color: var(--soft-grey);
}

.author {
  font-style: italic;
  font-weight: normal;
  font-size: 1rem;
  color: var(--soft-grey);
}

.section1 {
  background-color: var(--soft-bg);
  border-radius: var(--rounded);
  overflow: hidden;
}

.section1-div {
  padding: var(--section-padding);
  height: auto;
  max-height: 100vh;
}

.section1-paragraph {
  text-align: center;
  font-size: 1rem;
  line-height: 1.5rem;
  padding-bottom: 1rem;
  max-width: 900px;
  margin: 0 auto;
}

.section1-img {
  aspect-ratio: 4 / 3;
  width: 50%;
  min-height: 50vh;
  margin: 0 auto 3rem auto;
  display: flex;
  overflow: hidden;
  justify-content: center;
  border-radius: var(--rounded);
}

.section1-img img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.section2 {
  display: flex;
  justify-content: space-between;
  gap: 2rem;
}

.section2 h2 {
  text-align: left;
  line-height: 2.5rem;
  font-size: 2rem;
  font-weight: 700;
  width: 30%;
  color: var(--black-txt);
}

.section2 p {
  text-align: left;
  line-height: 2rem;
  font-size: 1rem;
  width: 60%;
  color: var(--soft-grey);
}

.navbar {
  position: fixed;
  top: 1rem;
  left: 0;
  right: 0;
  width: 98%;
  z-index: 100;
  font-family: "Roboto", sans-serif;
  background: var(--white);
  border-radius: var(--rounded);
  box-shadow: var(--shadow);
  padding: 1.3rem 3rem 1.3rem 2.2rem;
  display: flex;
  justify-content: space-between;
  margin: 0 auto;
}

.navbar nav a {
  color: var(--soft-grey);
  text-decoration: none;
  margin-left: 2.4rem;
  font-size: 1rem;
  transition: color 0.2s;
}

.navbar nav a:hover {
  font-weight: 800;
  border-bottom: 2px solid var(--primary);
}

.hero-section {
  position: relative;
  min-height: 80vh;
  display: flex;
  align-items: flex-end;
  background: url(./images/hero.jpg);
  color: var(--white);
  background-size: cover;
  background-position: center;
  border-radius: var(--rounded);
  overflow: hidden;
}

.hero-overlay {
  position: absolute;
  inset: 0;
  background: var(--hero-overlay);
  border-radius: inherit;
  z-index: 1;
}

.hero-content {
  position: relative;
  z-index: 2;
  padding: 2.5rem;
  max-width: 50rem;
  padding-bottom: 10rem;
}

.hero-content h1 {
  font-size: 3rem;
  font-weight: bold;
  line-height: 1.15;
  margin-bottom: 1rem;
  letter-spacing: 1.15px;
}

.hero-content h1 span {
  font-style: normal;
}

.hero-content p {
  font-size: 1.08rem;
  opacity: 0.85;
  line-height: 2;
  margin-bottom: 1.5rem;
  letter-spacing: 1.15px;
}

.cta-btn,
.btn {
  padding: 0.8rem 1.7rem;
  background: var(--primary);
  font-family: "Roboto", sans-serif;
  color: var(--black-txt);
  font-weight: 600;
  border: none;
  border-radius: 0.5rem;
  text-decoration: none;
  font-size: 1.1rem;
  cursor: pointer;
  transition: background 0.21s;
}

.cta-btn:hover,
.btn:hover {
  background: var(--button-hover);
}

.image-row {
  display: flex;
  flex-wrap: wrap;
  gap: 1.5rem;
  justify-content: center;
  margin-top: 2rem;
}

.image-row img {
  aspect-ratio: 1 / 1;
  width: 10rem;
  border-radius: var(--rounded);
  box-shadow: var(--shadow);
  object-fit: cover;
}

.image-row img:hover {
  transform: translateY(-2rem);
  transition: 0.3s ease;
}

.product-grid {
  background-color: var(--soft-bg);
  border-radius: var(--rounded);
  padding: var(--section-padding);
  margin-bottom: 4rem;
}

.product-grid-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  padding-top: 2rem;
}

.product-card {
  background-color: var(--white);
  border-radius: var(--rounded);
  box-shadow: var(--shadow);
  padding: 1.5rem;
  text-align: center;
  transition: transform 0.2s ease;
}

.product-card:hover {
  transform: translateY(-0.5rem);
}

.product-card img {
  width: 100%;
  aspect-ratio: 4 / 3;
  object-fit: cover;
  border-radius: var(--rounded);
  margin-bottom: 1rem;
}

.product-card h3 {
  font-family: "Poppins", sans-serif;
  font-size: 1.2rem;
  font-weight: 600;
  margin-bottom: 0.5rem;
  color: var(--black-txt);
}

.product-description {
  font-size: 0.95rem;
  color: var(--soft-grey);
  line-height: 1.4;
  margin-bottom: 0.8rem;
}

.product-price {
  font-size: 1.1rem;
  font-weight: bold;
  color: var(--primary);
}

.reviews {
  padding: var(--section-padding);
  margin-bottom: 6rem;
}

.review-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 2rem;
  padding-top: 2rem;
  justify-content: center;
  position: relative;
}

.review-item {
  background: var(--white);
  border-radius: 1.2rem;
  box-shadow: var(--shadow);
  padding: 2rem;
  max-width: 22rem;
  position: relative;
}

.review-item:nth-child(1),
.review-item:nth-child(3) {
  transform: translateY(20px);
}

.review-item:nth-child(2) {
  transform: translateY(-10px);
}

.review-text {
  font-size: 1.1rem;
  line-height: 1.2;
  margin-bottom: 1rem;
  color: var(--soft-grey);
  quotes: "“" "”" "‘" "’";
}

.review-text::before {
  content: open-quote;
  font-size: 2rem;
  vertical-align: -0.4rem;
  color: var(--primary);
}

.review-text::after {
  content: close-quote;
  font-size: 2rem;
  vertical-align: -0.4rem;
  color: var(--primary);
}

.review-author {
  font-size: 0.9rem;
  opacity: 0.6;
  font-style: italic;
  color: var(--black-txt);
}

.newsletter-form {
  margin-top: 2rem;
  display: flex;
  gap: 1rem;
  justify-content: center;
  flex-wrap: wrap;
}

.newsletter-form input {
  padding: 0.8rem 1rem;
  font-size: 1rem;
  border-radius: 0.5rem;
  border: 1px solid #ccc;
  width: 300px;
  max-width: 100%;
}

.newsletter-form button {
  padding: 0.8rem 1.5rem;
  font-size: 1rem;
  border: none;
  background: var(--primary);
  color: var(--black-txt);
  border-radius: 0.5rem;
  cursor: pointer;
  transition: background 0.2s ease-in-out;
}

.newsletter-form button:hover {
  background: var(--button-hover);
}

.footer {
  background-color: var(--soft-bg);
  padding: 1.5rem 3.5rem;
  border-radius: var(--rounded);
  width: 95%;
  box-shadow: var(--shadow);
  margin: 0 auto 3rem auto;
  font-family: "Roboto", sans-serif;
}

.footer-content {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  gap: 5rem;
  margin: 2rem 0;
}

.footer-left {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  gap: 1rem;
}

.footer-logo-text {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 1rem;
}

.footer-text {
  font-size: 0.95rem;
  color: var(--soft-grey);
  max-width: 350px;
  line-height: 1.5;
}

.footer-column {
  display: flex;
  flex-direction: column;
  gap: 0.8rem;
}

.footer-column h4 {
  font-size: 1.5rem;
  font-weight: bold;
  margin-bottom: 1rem;
  color: var(--black-txt);
}

.footer-column a {
  text-decoration: none;
  color: rgb(3, 112, 9);
  font-size: 1.1rem;
}

.footer-column a:hover {
  text-decoration: underline;
}

.centered-line {
  width: 100%;
  height: 0.1rem;
  background-color: var(--soft-grey);
  border: none;
  margin: 2rem auto;
}

.footer-bottom {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  width: 100%;
  align-items: center;
  line-height: 1.5;
  font-size: 0.9rem;
  color: var(--soft-grey);
}

.footer-links {
  display: flex;
  justify-content: flex-end;
  gap: 1rem;
  align-items: center;
}

.footer-links a {
  text-decoration: none;
  color: var(--black-txt);
  font-weight: 600;
  transition: color 0.2s ease;
}

.footer-links a:hover {
  text-decoration: underline;
  color: var(--primary);
}

.navbar nav a:focus,
.cta-btn:focus,
.btn:focus {
  outline: 3px solid var(--primary);
  outline-offset: 2px;
}

.navbar nav a,
.cta-btn,
.btn {
  padding: 0.5rem 1rem;
}
```


## OUTPUT
Here are some images of the designed Website.
<img width="1919" height="1026" alt="1" src="https://github.com/user-attachments/assets/cee653db-7429-44df-9533-37ecc090753f" />
<img width="1919" height="1026" alt="2" src="https://github.com/user-attachments/assets/1a8169f8-8f1e-410e-aae9-86e5a5d621c4" />
<img width="1918" height="1035" alt="3" src="https://github.com/user-attachments/assets/b16eeeb8-d6c8-49ab-b8f6-da85651fc2ab" />
<img width="1917" height="1028" alt="4" src="https://github.com/user-attachments/assets/8be1ee4b-23ba-4cef-a753-738bba5cd6c1" />
<img width="1916" height="1029" alt="5" src="https://github.com/user-attachments/assets/75a4355d-cf3e-4807-b00e-c4b89d4d75e1" />
<img width="1919" height="1030" alt="6" src="https://github.com/user-attachments/assets/469bc152-1cab-481b-b119-67bd52d7a43e" />
<img width="1919" height="1035" alt="7" src="https://github.com/user-attachments/assets/7523edfa-a1a6-49ad-8d3c-ac45793e0865" />
<img width="1919" height="1028" alt="8" src="https://github.com/user-attachments/assets/f5823b39-7c6a-41c3-94ed-615acaff5121" />




## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.


### Name: ASWIN B
### Register Number : 212224110007
