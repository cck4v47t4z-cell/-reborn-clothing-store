# -reborn-clothing-store<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>REBORN. | Official Store</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background: #080808;
    color: white;
    font-family: Arial, sans-serif;
}

a {
    color: inherit;
    text-decoration: none;
}

.announcement {
    background: white;
    color: black;
    text-align: center;
    padding: 10px;
    font-size: 10px;
    letter-spacing: 2px;
}

header {
    height: 75px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 6%;
    border-bottom: 1px solid #252525;
    position: sticky;
    top: 0;
    background: #080808;
    z-index: 10;
}

.logo {
    font-size: 27px;
    font-weight: 900;
    letter-spacing: 5px;
}

.nav {
    display: flex;
    gap: 30px;
    font-size: 11px;
    letter-spacing: 1px;
    text-transform: uppercase;
}

.actions {
    display: flex;
    gap: 20px;
    font-size: 11px;
}

.categories {
    display: flex;
    justify-content: center;
    gap: 28px;
    padding: 17px 10px;
    overflow-x: auto;
    white-space: nowrap;
    border-bottom: 1px solid #252525;
}

.categories a {
    font-size: 10px;
    letter-spacing: 1.5px;
    color: #aaa;
}

.categories a:hover {
    color: white;
}

.hero {
    min-height: 550px;
    display: flex;
    align-items: end;
    padding: 8%;
    background: linear-gradient(120deg,#080808,#171717);
}

.hero h1 {
    font-size: clamp(55px,9vw,110px);
    line-height: .9;
    letter-spacing: -4px;
    margin: 20px 0;
}

.hero p {
    color: #999;
    max-width: 400px;
    line-height: 1.8;
    font-size: 13px;
}

.button {
    display: inline-block;
    background: white;
    color: black;
    padding: 16px 27px;
    margin-top: 25px;
    font-size: 10px;
    letter-spacing: 2px;
    font-weight: bold;
}

section {
    padding: 75px 6%;
}

.section-title {
    font-size: 28px;
    margin-bottom: 30px;
}

.category-grid {
    display: grid;
    grid-template-columns: repeat(3,1fr);
    gap: 15px;
}

.category-card {
    height: 300px;
    background: linear-gradient(145deg,#191919,#090909);
    border: 1px solid #292929;
    display: flex;
    align-items: end;
    padding: 25px;
}

.category-card h3 {
    font-size: 25px;
    margin-bottom: 12px;
}

.category-card span {
    font-size: 10px;
    color: #aaa;
    letter-spacing: 2px;
}

.filters {
    display: flex;
    gap: 10px;
    overflow-x: auto;
    margin-bottom: 30px;
}

.filters button {
    background: transparent;
    color: white;
    border: 1px solid #333;
    padding: 11px 18px;
    cursor: pointer;
    white-space: nowrap;
}

.filters button:hover,
.filters button.active {
    background: white;
    color: black;
}

.products {
    display: grid;
    grid-template-columns: repeat(4,1fr);
    gap: 20px 14px;
}

.product-image {
    height: 280px;
    background: linear-gradient(145deg,#191919,#090909);
    border: 1px solid #292929;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #555;
    font-size: 10px;
    letter-spacing: 2px;
}

.product h3 {
    font-size: 12px;
    margin-top: 15px;
}

.product p {
    color: #888;
    font-size: 11px;
    margin-top: 8px;
}

.product button {
    width: 100%;
    padding: 12px;
    background: transparent;
    color: white;
    border: 1px solid #444;
    margin-top: 12px;
}

.product button:hover {
    background: white;
    color: black;
}

.story {
    background: #111;
    text-align: center;
    padding: 85px 20px;
}

.story h2 {
    font-size: 40px;
    margin: 15px;
}

.story p {
    color: #999;
    max-width: 500px;
    margin: auto;
    line-height: 1.8;
    font-size: 13px;
}

footer {
    padding: 60px 6% 25px;
    border-top: 1px solid #292929;
}

.footer-grid {
    display: grid;
    grid-template-columns: 2fr 1fr 1fr 1fr;
    gap: 30px;
}

footer h4 {
    font-size: 11px;
    letter-spacing: 2px;
    margin-bottom: 20px;
}

footer a {
    display: block;
    color: #999;
    font-size: 12px;
    margin: 13px 0;
}

footer p {
    color: #888;
    font-size: 12px;
    line-height: 1.8;
    margin-top: 15px;
}

.copyright {
    border-top: 1px solid #292929;
    margin-top: 40px;
    padding-top: 20px;
    color: #777;
    font-size: 10px;
}

@media(max-width:750px) {
    .nav {
        display: none;
    }

    .categories {
        justify-content: flex-start;
    }

    .category-grid {
        grid-template-columns: 1fr;
    }

    .category-card {
        height: 190px;
    }

    .products {
        grid-template-columns: repeat(2,1fr);
    }

    .product-image {
        height: 210px;
    }

    .footer-grid {
        grid-template-columns: 1fr 1fr;
    }

    .hero {
        min-height: 480px;
    }
}
</style>
</head>

<body>

<div class="announcement">
A NEW CHAPTER BEGINS HERE — REBORN.
</div>

<header>
    <a href="#" class="logo">REBORN.</a>

    <nav class="nav">
        <a href="#">Home</a>
        <a href="#shop">Shop</a>
        <a href="#categories">Collections</a>
        <a href="#story">Our Story</a>
    </nav>

    <div class="actions">
        <a href="#shop">Search</a>
        <a href="#shop">Bag (0)</a>
    </div>
</header>

<nav class="categories">
    <a href="#shop">ALL</a>
    <a href="#shop">T-SHIRTS</a>
    <a href="#shop">OVERSIZED</a>
    <a href="#shop">HOODIES</a>
    <a href="#shop">SWEATSHIRTS</a>
    <a href="#shop">WALLETS</a>
    <a href="#shop">ACCESSORIES</a>
    <a href="#shop">BEST SELLERS</a>
    <a href="#shop">NEW ARRIVALS</a>
</nav>

<div class="hero">
    <div>
        <span style="letter-spacing:3px;color:#999;font-size:10px;">
            REBORN / EST. 2026
        </span>

        <h1>WEAR YOUR<br>NEXT CHAPTER.</h1>

        <p>
            Everyday essentials. Considered details.
            A new expression of personal style.
            Discover the world of REBORN.
        </p>

        <a href="#shop" class="button">EXPLORE COLLECTION ↗</a>
    </div>
</div>

<section id="categories">

    <h2 class="section-title">SHOP BY CATEGORY</h2>

    <div class="category-grid">

        <a href="#shop" class="category-card">
            <div>
                <span>01 / EVERYDAY ESSENTIALS</span>
                <h3>CLOTHING</h3>
                <span>EXPLORE ↗</span>
            </div>
        </a>

        <a href="#shop" class="category-card">
            <div>
                <span>02 / THE DETAILS</span>
                <h3>ACCESSORIES</h3>
                <span>EXPLORE ↗</span>
            </div>
        </a>

        <a href="#shop" class="category-card">
            <div>
                <span>03 / CARRY YOUR ESSENTIALS</span>
                <h3>WALLETS</h3>
                <span>EXPLORE ↗</span>
            </div>
        </a>

    </div>

</section>

<section id="shop">

    <h2 class="section-title">EXPLORE THE COLLECTION</h2>

    <div class="filters">
        <button class="active" onclick="filterProducts('all',this)">ALL</button>
        <button onclick="filterProducts('clothing',this)">CLOTHING</button>
        <button onclick="filterProducts('accessories',this)">ACCESSORIES</button>
        <button onclick="filterProducts('wallets',this)">WALLETS</button>
    </div>

    <div class="products">

        <div class="product" data-category="clothing">
            <div class="product-image">IMAGE COMING SOON</div>
            <h3>Essential T-Shirt</h3>
            <p>COMING SOON</p>
        </div>

        <div class="product" data-category="clothing">
            <div class="product-image">IMAGE COMING SOON</div>
            <h3>Oversized T-Shirt</h3>
            <p>COMING SOON</p>
        </div>

        <div class="product" data-category="clothing">
            <div class="product-image">IMAGE COMING SOON</div>
            <h3>Signature Hoodie</h3>
            <p>COMING SOON</p>
        </div>

        <div class="product" data-category="clothing">
            <div class="product-image">IMAGE COMING SOON</div>
            <h3>REBORN Sweatshirt</h3>
            <p>COMING SOON</p>
        </div>

        <div class="product" data-category="accessories">
            <div class="product-image">IMAGE COMING SOON</div>
            <h3>Everyday Cap</h3>
            <p>COMING SOON</p>
        </div>

        <div class="product" data-category="accessories">
            <div class="product-image">IMAGE COMING SOON</div>
            <h3>Classic Belt</h3>
            <p>COMING SOON</p>
        </div>

        <div class="product" data-category="wallets">
            <div class="product-image">IMAGE COMING SOON</div>
            <h3>Minimal Wallet</h3>
            <p>COMING SOON</p>
        </div>

        <div class="product" data-category="wallets">
            <div class="product-image">IMAGE COMING SOON</div>
            <h3>Card Holder</h3>
            <p>COMING SOON</p>
        </div>

    </div>

</section>

<div class="story" id="story">

    <span style="color:#999;letter-spacing:3px;font-size:10px;">
        MORE THAN WHAT YOU WEAR
    </span>

    <h2>REBORN TO BE WORN.</h2>

    <p>
        REBORN is about starting fresh, expressing yourself
        and finding your own identity through everyday style.
        This is just the beginning.
    </p>

</div>

<footer>

    <div class="footer-grid">

        <div>
            <div class="logo">REBORN.</div>
            <p>Everyday pieces. A new chapter. REBORN to be worn.</p>
        </div>

        <div>
            <h4>SHOP</h4>
            <a href="#shop">All Products</a>
            <a href="#shop">Clothing</a>
            <a href="#shop">Accessories</a>
            <a href="#shop">Wallets</a>
        </div>

        <div>
            <h4>HELP</h4>
            <a href="#">Contact</a>
            <a href="#">Shipping</a>
            <a href="#">Returns</a>
            <a href="#">FAQs</a>
        </div>

        <div>
            <h4>FOLLOW</h4>
            <a href="https://instagram.com/re.born.gg" target="_blank">Instagram ↗</a>
        </div>

    </div>

    <div class="copyright">
        © 2026 REBORN. ALL RIGHTS RESERVED.
    </div>

</footer>

<script>
function filterProducts(category,button) {

    document.querySelectorAll('.filters button')
    .forEach(btn => btn.classList.remove('active'));

    button.classList.add('active');

    document.querySelectorAll('.product').forEach(product => {

        if(category === 'all' ||
           product.dataset.category === category) {

            product.style.display = 'block';

        } else {

            product.style.display = 'none';

        }

    });

}
</script>

</body>
</html>
