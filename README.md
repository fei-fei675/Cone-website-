# Cone-website-
Clone website 
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>fei-fei-Beauty Store</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #fff7f9;
        }

        /* Sticky Header */
        header {
            position: sticky;
            top: 0;
            background-color: #ffffff;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 30px;
            box-shadow: 0 2px 5px rgba(197, 98, 204, 0.1);
            z-index: 999;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #E91E63;
        }

        nav a {
            margin-left: 20px;
            text-decoration: none;
            color: #333;
            font-weight: 500;
        }

        nav a:hover {
            color: #E91E63;
        }


        /* Products Grid */
        .products {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 20px;
            padding: 30px;
            max-width: 1200px;
            margin: auto;
        }

        .product-card {
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
            transition: transform 0.2s;
        }

        .product-card:hover {
            transform: translateY(-5px);
        }

        .product-card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }

        .info {
            padding: 10px;
        }

        .info p {
            margin: 5px 0;
            font-size: 14px;
        }

        .price {
            font-size: 16px;
            font-weight: bold;
            color: #4CAF50;
        }

        .discount {
            color: #E91E63;
        }
    </style>
</head>

<body>

    <header>
        <div class="logo">fei-fei Beauty Store</div>
        <nav>
            <a href="#">🏠 Home</a>
            <a href="#">📞 Contact</a>
            <a href="#">🔍 Search</a>
            <a href="#">⚙️ Setting</a>
        </nav>
    </header>


    <div class="products">
        <div class="product-card">
            <img src="picture/dior 04.webp" alt="Product 1">
            <div class="info">
                <p>Brand : Dior </p>
                <p>Type : Lipstick </p>
                <p class="discount">15% Off</p>
                <p class="price">$99.99</p>
            </div>
        </div>

        <div class="product-card">
            <img src="picture/dior 02.webp" alt="Product 5">
            <div class="info">
                <p>Brand : Dior </p>
                <p>Type : Lipstick </p>
                <p class="discount">25% Off</p>
                <p class="price">$99.50</p>
            </div>
        </div>

        <div class="product-card">
            <img src="picture/serum bueaty og joseon.jpg" alt="Product 5">
            <div class="info">
                <p>[Beauty of Joseon] Glow Deep Serum</p>
                <p class="discount">25% Off</p>
                <p class="price">$15.50</p>
            </div>
        </div>

        <div class="product-card">
            <img src="picture/BEAUTY OF JOSEON Dynasty Cream 50ml.jpg" alt="Product 2">
            <div class="info">
                <p>[Beauty of Joseon] Dynasty Cream 50m</p>
                <p class="discount">10% Off</p>
                <p class="price">$25.99</p>
            </div>
        </div>

        <div class="product-card">
            <img src="picture/BEAUTY OF JOSEON - Ground Rice.webp" alt="Product 3">
            <div class="info">
                <p>[Beauty of Joseon] Ground Rice and Honey Glow Mask</p>
                <p class="discount">20% Off</p>
                <p class="price">$18.49</p>
            </div>
        </div>

        <div class="product-card">
            <img src="picture/essence water.webp" alt="Product 4">
            <div class="info">
                <p>[Beauty of Joseon] Ginseng Cleansing Oil</p>
                <p class="discount">5% Off</p>
                <p class="price">$22.00</p>
            </div>
        </div>

        <div class="product-card">
            <img src="picture/ss1.webp" alt="Product 5">
            <div class="info">
                <p>[Beauty of Joseon] Sunscreen</p>
                <p class="discount">25% Off</p>
                <p class="price">$15.50</p>
            </div>
        </div>

        <div class="product-card">
            <img src="picture/sunscreen2.webp" alt="Product 6">
            <div class="info">
                <p>[Beauty of Joseon] Hybrid Sunscreen</p>
                <p class="discount">12% Off</p>
                <p class="price">$30.00</p>
            </div>
        </div>

        <div class="product-card">
            <img src="picture/Beauty of Joseon Red Bean Pore Mask.jpg" alt="Product 6">
            <div class="info">
                <p>[Beauty of Joseon] Red Bean Pore Mask</p>
                <p class="discount">12% Off</p>
                <p class="price">$30.00</p>
            </div>
        </div>

        <div class="product-card">
            <img src="picture/gel1.webp" alt="Product 1">
            <div class="info">
                <p>[Beauty of Joseon] Gel</p>
                <p class="discount">15% Off</p>
                <p class="price">$12.99</p>
            </div>
        </div>


        <div class="product-card">
            <img src="picture/skin1004 01.jpg" alt="Product 5">
            <div class="info">
                <p>[Skin1004] Sunscreen</p>
                <p class="discount">25% Off</p>
                <p class="price">$15.50</p>
            </div>
        </div>

        <div class="product-card">
            <img src="picture/skin1004 02.webp" alt="Product 5">
            <div class="info">
                <p>[Skin1004] Sunscreen</p>
                <p class="discount">25% Off</p>
                <p class="price">$15.50</p>
            </div>
        </div>

        <div class="product-card">
            <img src="picture/skin1004 03.webp" alt="Product 1">
            <div class="info">
                <p>[Skin1004] Serum</p>
                <p class="discount">15% Off</p>
                <p class="price">$12.99</p>
            </div>
        </div>

        <div class="product-card">
            <img src="picture/skin1004 04.webp" alt="Product 1">
            <div class="info">
                <p>[Skin1004] Serum</p>
                <p class="discount">15% Off</p>
                <p class="price">$12.99</p>
            </div>
        </div>

        <div class="product-card">
            <img src="picture/skin1004 05.jpeg" alt="Product 1">
            <div class="info">
                <p>[Skin1004] Clay mask </p>
                <p class="discount">15% Off</p>
                <p class="price">$12.99</p>
            </div>
        </div>

        <div class="product-card">
            <img src="picture/skin1004 05.webp" alt="Product 1">
            <div class="info">
                <p>[Skin1004] Essend </p>
                <p class="discount">15% Off</p>
                <p class="price">$12.99</p>
            </div>
        </div>

        <div class="product-card">
            <img src="picture/pka pkorlorn.jpg" alt="Product 1">
            <div class="info">
                <p>[Pka Blush] Pkor lorn</p>
                <p class="discount">15% Off</p>
                <p class="price">$12.99</p>
            </div>
        </div>

        <div class="product-card">
            <img src="picture/pka romdoul.jpg" alt="Product 1">
            <div class="info">
                <p>[Pka Blush] Romdoul</p>
                <p class="discount">15% Off</p>
                <p class="price">$12.99</p>
            </div>
        </div>

        <div class="product-card">
            <img src="picture/pka terkdos.jpg" alt="Product 1">
            <div class="info">
                <p>[Pka Blush] Terk dos </p>
                <p class="discount">15% Off</p>
                <p class="price">$12.99</p>
            </div>
        </div>

        <div class="product-card">
            <img src="picture/amore blush.jpg" alt="Product 1">
            <div class="info">
                <p>[amore ] </p>
                <p class="discount">15% Off</p>
                <p class="price">$12.99</p>
            </div>
        </div>





    </div>

</body>

</html>
