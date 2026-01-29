<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <title>S.I.T.Company</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #1e90ff, #7b2cff);
            color: white;
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
        }

        .header-center h1 {
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

        /* ===== Hero ===== */
        .hero {
            text-align: center;
            padding: 70px 20px;
        }

        .hero h2 {
            font-size: 34px;
            margin-bottom: 10px;
        }

        .hero p {
            opacity: 0.9;
        }

        /* ===== Product ===== */
        .product {
            max-width: 600px;
            margin: 60px auto;
            background: white;
            color: black;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.3);
            text-align: center;
        }

        .product h2 {
            margin-bottom: 20px;
        }

        .product img {
            width: 100%;
            max-width: 400px;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        .price {
            font-size: 22px;
            color: #1870f0;
            font-weight: bold;
        }

        /* ===== Contact ===== */
        .contact {
            text-align: center;
            margin: 40px 0;
            font-size: 14px;
        }

        /* ===== Footer ===== */
        footer {
            background: #222;
            text-align: center;
            padding: 15px;
            font-size: 13px;
        }
    </style>
</head>

<body>

<header>
    <div class="header-center">
        <img src="Logo.png" alt="S.I.T Logo">
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
    <img src="pd.jpg" alt="สินค้า">
    <p>
        กล้องวงจรปิดสำหรับการจัดการจราจร<br>
        ติดตั้งง่าย ปลอดภัย และใช้งานสะดวก
    </p>
    <p class="price">฿21,999</p>
</section>

<div class="contact">
    📞 โทร: 080-085-0053 | ✉ Email: S.I.T.Company@gmail.com
</div>

<footer>
    © 2026 S.I.T.Company | All Rights Reserved
</footer>

</body>
</html>
