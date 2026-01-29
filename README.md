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
      background: linear-gradient(to bottom, #0d6efd, #6610f2);
      color: white;
    }

    /* ===== Header ===== */
    header {
      background: #0d6efd;
      padding: 25px 20px;
    }

    .brand-center {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 15px;
    }

    .logo {
      width: 70px;
    }

    .brand-name {
      font-size: 32px;
      font-weight: bold;
    }

    /* ===== Nav ===== */
    nav {
      background: #084298;
      display: flex;
      justify-content: center;
      gap: 25px;
      padding: 12px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    /* ===== Hero ===== */
    .hero {
      padding: 70px 20px;
      text-align: center;
    }

    .hero h2 {
      font-size: 30px;
      margin-bottom: 10px;
    }

    /* ===== Product ===== */
    .product {
      max-width: 650px;
      margin: 50px auto;
      padding: 30px;
      text-align: center;
      background: rgba(255,255,255,0.12);
      border-radius: 15px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.25);
    }

    .product img {
      display: block;
      margin: 20px auto;
      max-width: 100%;
      height: auto;
      border-radius: 12px;
    }

    .price {
      font-size: 22px;
      font-weight: bold;
      color: #ffc107;
      margin-top: 15px;
    }

    /* ===== Footer ===== */
    footer {
      background: #212529;
      text-align: center;
      padding: 20px;
      margin-top: 60px;
    }
  </style>
</head>

<body>

  <!-- Header -->
  <header>
    <div class="brand-center">
      <img src="logo.png" alt="S.I.T Logo" class="logo">
      <span class="brand-name">S.I.T.Company</span>
    </div>
  </header>

  <!-- Nav -->
  <nav>
    <a href="#home">หน้าแรก</a>
    <a href="#product">สินค้า</a>
    <a href="#contact">ติดต่อเรา</a>
  </nav>

  <!-- Hero -->
  <section class="hero" id="home">
    <h2>เทคโนโลยีความปลอดภัยเพื่อคุณภาพและอนาคต</h2>
    <p>นวัตกรรมเพื่อความปลอดภัย</p>
  </section>

  <!-- Product -->
  <section class="product" id="product">
    <h2>สินค้าแนะนำ</h2>

    <img src="pd.jpg" alt="กล้องวงจรปิดอัจฉริยะ">

    <p>
      กล้องวงจรปิดสำหรับการจัดการจราจร<br>
      ติดตั้งง่าย ปลอดภัย และใช้งานสะดวก
    </p>

    <div class="price">฿21,999</div>
  </section>

  <!-- Contact -->
  <section class="hero" id="contact">
    <h2>ติดต่อเรา</h2>
    <p>📞 080-085-0053 | 📧 S.I.T.Company@email.com</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2026 S.I.T.Company | All Rights Reserved</p>
  </footer>

</body>
</html>
