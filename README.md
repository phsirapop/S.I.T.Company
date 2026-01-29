<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <title>S.I.T.Company</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        /* ===== Header ===== */
        header {
            background: #1870f0;
            padding: 20px 0;
        }

        .header-center {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 15px;
        }

        .header-center img {
            width: 70px;
            height: auto;
        }

        .header-center h1 {
            color: white;
            margin: 0;
            font-size: 32px;
        }

        /* ===== Menu ===== */
        nav {
            background: #0b3f8f;
            text-align: center;
            padding: 10px 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* ===== Hero ===== */
        .hero {
            background: linear-gradient(135deg, #1e90ff, #7b2cff);
            color: white;
            text-align: center;
            padding: 80px 20px;
        }

        .hero h2 {
            font-size: 36px;
            margin-bottom: 10px;
        }

        /* ===== Product ===== */
        .product {
            max-width: 900px;
            margin: 50px auto;
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
            text-align: center;
        }

        .product img {
            width: 300px;
            margin-bottom: 20px;
        }

        .price {
            font-size: 22px;
            color: #1870f0;
            font-weight: bold;
        }
    </style>
</head>

<body>

<header>
    <div class="header-center">
        <img src="logo.png" alt="S.I.T Logo">
        <h1>S.I.T.Company</h1>
    </div>
</header>

<nav>
    <a href="index.html">หน้าแรก</a>
    <a href="products.html">สินค้า</a>
    <a href="contact.html">ติดต่อเรา</a>
</nav>

<section class="hero">
    <h2>เทคโนโลยีความปลอดภัยเพื่อคุณภาพและอนาคต</h2>
    <p>นวัตกรรมเพื่อความปลอดภัย</p>
</section>

<section class="product">
    <h2>สินค้าแนะนำ</h2>
    <img src="logo.png" alt="สินค้า">
    <p>
        กล้องวงจรปิดสำหรับการจัดการจราจร
        ติดตั้งง่าย ปลอดภัย และใช้งานสะดวก
    </p>
    <p class="price">฿21,999</p>
</section>

</body>
</html>
