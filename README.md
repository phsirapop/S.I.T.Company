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
      color: #333;
    }

    /* ===== Header ===== */
    .site-header {
      background: #0d6efd;
      padding: 20px;
    }

    .brand-center {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 12px;
      flex-wrap: wrap;
      text-align: center;
    }

    .logo {
      width: 120px;
      max-width: 40vw;
      height: auto;
    }

    .brand-name {
      font-size: 28px;
      font-weight: bold;
      color: white;
    }

    /* ===== Nav ===== */
    nav {
      background: #084298;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 15px;
      padding: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    /* ===== Hero ===== */
    .hero {
      background: linear-gradient(to right, #0d6efd, #6610f2);
      color: white;
      padding: 60px 20px;
      text-align: center;
    }

    /* ===== Container ===== */
    .container {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    /* ===== Product ===== */
    .products {
      display: flex;
      justify-content: center;
    }

    .card {
      background: white;
      border-radius: 12px;
      padding: 20px;
      max-width: 420px;
      width: 100%;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      text-align: center;
    }

    .card img {
      max-width: 100%;
      height: auto;
      display: block;
      margin: 0 auto 15px;
      border-radius: 8px;
    }

    .price {
      color: #0d6efd;
      font-size: 20px;
      font-weight: bold;
    }

    .card button {
      margin-top: 10px;
      padding: 10px 16px;
      border: none;
      border-radius: 6px;
      background: #0d6efd;
      color: white;
      cursor: pointer;
      width: 100%;
      max-width: 200px;
    }

    /* ===== Footer ===== */
    footer {
      background: #212529;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    /* ===== Mobile ===== */
    @media (max-width: 600px) {
      .brand-name {
        font-size: 22px;
      }

      .hero h2 {
        font-size: 24px;
      }
    }
  </style>
</head>

<body>

<header class="site-header">
  <div class="brand-center">
    <img src="Logo.png" alt="S.I.T Company Logo" class="logo">
    <span class="brand-name">S.I.T.Company</span>
  </div>
</header>

<nav>
  <a href="#home">หน้าแรก</a>
  <a href="#products">สินค้า</a>
  <a href="#contact">ติดต่อเรา</a>
</nav>

<section class="hero" id="home">
  <h2>เทคโนโลยีความปลอดภัยเพื่อคุณภาพเเละอนาคต</h2>
  <p>นวัตกรรมเพื่อความปลอดภัย</p>
</section>

<section class="container" id="products">
  <h2 style="text-align:center">สินค้าแนะนำ</h2>

  <div class="products">
    <div class="card">
      <img src="pd.jpg" alt="กล้องอัจฉริยะ(S.I.T.C)">
      <h3>สินค้า A</h3>
      <p>
        กล้องวงจรปิดสำหรับการจัดการดูแลการจอดรถตามที่สาธารณะได้อย่างมีประสิทธิภาพ
      </p>
      <p>
        - ติดตั้งง่าย<br>
        - ทีมงานผู้เชี่ยวชาญ<br>
        - ปลอดภัยในการใช้งาน
      </p>
      <div class="price">฿21,999</div>
      <a href="https://mail.google.com">
        <button>ติดต่อเรา</button>
      </a>
    </div>
  </div>
</section>

<section class="container" id="contact">
  <h2 style="text-align:center">ติดต่อเรา</h2>
  <p style="text-align:center">
    📞 080-085-0053 | 📧 S.I.T.Compax@email.com
  </p>
</section>

<footer>
  <p>© 2026 S.I.T.Company | All Rights Reserved</p>
</footer>

</body>
</html>
