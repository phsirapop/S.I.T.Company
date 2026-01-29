<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>S.I.T.Company</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
    }

    /* ===== HEADER ===== */
    header {
      background: #0d6efd;
      padding: 25px;
    }

    .brand-center {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 15px;
    }

    .brand-center img {
      width: 70px;
    }

    .brand-center h1 {
      color: white;
      margin: 0;
    }

    nav {
      background: #084298;
      text-align: center;
      padding: 10px;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    /* ===== HERO ===== */
    .hero {
      background: linear-gradient(to right, #0d6efd, #6610f2);
      color: white;
      text-align: center;
      padding: 50px 20px;
    }

    /* ===== PRODUCT ===== */
    .product {
      max-width: 650px;
      margin: 40px auto;
      background: white;
      padding: 30px;
      border-radius: 15px;
      text-align: center;
      box-shadow: 0 6px 15px rgba(0,0,0,0.15);
    }

    .product img {
      display: block;
      margin: 20px auto;
      max-width: 100%;
      border-radius: 10px;
    }

    .price {
      font-size: 22px;
      font-weight: bold;
      color: #0d6efd;
      margin-top: 15px;
    }

    /* ===== FOOTER ===== */
    footer {
      background: #212529;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
  </style>
</head>

<body>

<header>
  <div class="brand-center">
    <img src="logo.png" alt="S.I.T Logo">
    <h1>S.I.T.Company</h1>
  </div>
</header>

<nav>
  <a href="#home">หน้าแรก</a>
  <a href="#product">สินค้า</a>
  <a href="#contact">ติดต่อเรา</a>
</nav>

<section class="hero" id="home">
  <h2>เทคโนโลยีความปลอดภัยเพื่อคุณภาพและอนาคต</h2>
  <p>นวัตกรรมเพื่อความปลอดภัย</p>
</section>

<section class="product" id="product">
  <h2>สินค้าแนะนำ</h2>

  <img src="pd.jpg" alt="กล้องวงจรปิดอัจฉริยะ">

  <p>
    กล้องวงจรปิดสำหรับการจัดการจราจร<br>
    ติดตั้งง่าย ปลอดภัย และใช้งานสะดวก
  </p>

  <p class="price">฿21,999</p>
</section>

<section id="contact" style="text-align:center; padding:20px;">
  📞 โทร: 080-085-0053 | 📧 Email: S.I.T.Company@email.com
</section>

<footer>
  © 2026 S.I.T.Company | All Rights Reserved
</footer>

</body>
</html>
