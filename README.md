<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <title>S.I.T Company</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f5f7fa; /* พื้นหลังเหมือนเดิม */
            color: #000;
        }

        /* ===== HEADER ===== */
        header {
            background: linear-gradient(to right, #0d6efd, #6610f2);
            color: white;
            padding: 40px 20px;
            text-align: center;
        }

        .logo {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 15px;
            margin-bottom: 20px;
        }

        .logo img {
            width: 60px;
            height: auto;
        }

        .logo h1 {
            font-size: 32px;
            margin: 0;
            text-decoration: underline;
        }

        header h2 {
            font-size: 36px;
            margin: 15px 0 10px;
        }

        header p {
            font-size: 18px;
            opacity: 0.9;
        }

        /* ===== PRODUCT ===== */
        .product {
            max-width: 650px;
            margin: 50px auto;
            padding: 30px;
            text-align: center;
            background: white;
            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.15);
        }

        .product h2 {
            font-size: 28px;
            margin-bottom: 20px;
        }

        .product img {
            max-width: 100%;
            border-radius: 12px;
        }

        .product p {
            font-size: 18px;
            line-height: 1.6;
        }

        .price {
            font-size: 26px;
            font-weight: bold;
            color: #0d6efd;
            margin-top: 15px;
        }

        /* ===== FOOTER ===== */
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>

<body>

<header>
    <div class="logo">
        <!-- 🔽 โลโก้ -->
        <img src="logo.png" alt="S.I.T Company Logo">
        <h1>S.I.T.Company</h1>
    </div>

    <h2>เทคโนโลยีความปลอดภัยเพื่อคุณภาพและอนาคต</h2>
    <p>นวัตกรรมเพื่อความปลอดภัย</p>
</header>

<section class="product">
    <h2>สินค้าแนะนำ</h2>

    <img src="pd.jpg" alt="สินค้า">

    <p>
        กล้องวงจรปิดสำหรับการจัดการจราจร<br>
        ติดตั้งง่าย ปลอดภัย และใช้งานสะดวก
    </p>

    <p class="price">฿21,999</p>
</section>

<footer>
    © 2026 S.I.T Company | All Rights Reserved
</footer>

</body>
</html>
