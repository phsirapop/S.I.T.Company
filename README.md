<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <title>S.I.T Company</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;

            /* ✅ เปลี่ยนเฉพาะสีพื้นหลัง */
            background: #f5f7fa;

            color: #000;
        }

        header {
            text-align: center;
            padding: 60px 20px;
            background: linear-gradient(to right, #0d6efd, #6610f2);
            color: white;
        }

        header h1 {
            font-size: 48px;
            margin-bottom: 10px;
        }

        header p {
            font-size: 20px;
            opacity: 0.9;
        }

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
            font-size: 32px;
            margin-bottom: 20px;
        }

        .product img {
            display: block;
            margin: 20px auto;
            max-width: 100%;
            height: auto;
            border-radius: 12px;
            background: #fff;
        }

        .product p {
            font-size: 18px;
            line-height: 1.6;
        }

        .price {
            font-size: 26px;
            font-weight: bold;
            margin-top: 15px;
            color: #0d6efd;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #222;
            color: white;
        }
    </style>
</head>

<body>

    <header>
        <h1>เทคโนโลยีความปลอดภัยเพื่อคุณภาพและอนาคต</h1>
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
