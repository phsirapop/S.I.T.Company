<html lang="th">
<head>
  <meta charset="UTF-8">
  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      color: #333;
    }

    /* ทำให้ section ยาวเต็มจอ */
    .full-width {
      width: 100vw;
      margin-left: calc(-50vw + 50%);
    }

    /* ===== Header ===== */
    .site-header {
      background: #0d6efd;
      padding: 30px 20px;
    }

    .brand-center {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 14px;
    }

    .logo {
      width: 150px;
      height: auto;
    }

    .brand-name {
      font-size: 32px;
      font-weight: bold;
      color: white;
    }

    /* ===== Nav ===== */
    nav {
      background: #084298;
      display: flex;
      justify-content: center;
      gap: 20px;
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

    /* ===== Products ===== */
    .products {
      display: flex;
      justify-content: center;
    }

    .card {
      background: white;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      text-align: center;
      max-width: 400px;
      width: 100%;
    }

    .card img {
      width: 100%;
      border-radius: 8px;
      display: block;
      margin: auto;
    }

    .card h3 {
      margin: 15px 0 10px;
    }

    .price {
      color: #0d6efd;
      font-size: 18px;
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
    }

    /* ===== Footer ===== */
    footer {
      background: #212529;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    /* ===== Responsive ===== */
    @media (max-width: 768px) {
      .brand-name {
        font-size: 24px;
      }

      .logo {
        width: 110px;
      }
    }
  </style>
</head>

<body>

  <!-- Header -->
  <header class="site-header full-width">
    <div class="brand-center">
      <img src="Logo.png" alt="S.I.T Company Logo" class="logo">
      <span class="brand-name">S.I.T.Company</span>
    </div>
  </header>

  <!-- Nav -->
  <nav class="full-width">
    <a href="#home">หน้าแรก</a>
    <a href="#products">สินค้า</a>
    <a href="#contact">ติดต่อเรา</a>
  </nav>

  <!-- Hero -->
  <section class="hero full-width" id="home">
    <h2>เทคโนโลยีความปลอดภัยเพื่อคุณภาพและอนาคต</h2>
    <p>นวัตกรรมเพื่อความปลอดภัย</p>
  </section>

  <!-- Products -->
  <section class="container" id="products">
    <h2 style="text-align:center">สินค้าแนะนำ</h2>

    <div class="products">
      <div class="card">
        <img src="pd.jpg" alt="กล้องอัจฉริยะ (S.I.T.C)">
        <h3>กล้องอัจฉริยะ (S.I.T.C)</h3>

        <p>
          กล้องวงจรปิดสำหรับการจัดการดูแลการจอดรถตามที่สาธารณะได้อย่างมีประสิทธิภาพ
          ออกแบบมาเพื่ออำนวยความสะดวกให้แก่ประชาชนและหน่วยงานต่างๆ
        </p>

        <p>
          - ติดตั้งง่ายและปลอดภัย<br>
          - ทีมงานผู้เชี่ยวชาญพร้อมช่วยเหลือ<br>
          - ตอบโจทย์การใช้งานที่รวดเร็ว
        </p>

        <div class="price">฿21,999</div>

        <a href="https://mail.google.com/mail/u/0/">
          <button>ติดต่อเรา</button>
        </a>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section class="container" id="contact">
    <h2 style="text-align:center">ติดต่อเรา</h2>
    <p style="text-align:center">
      📞 โทร: 080-085-0053 |
      📧 Email: S.I.T.Compax@email.com
    </p>
  </section>

  <!-- Footer -->
  <footer class="full-width">
    <p>© 2026 S.I.T.Company | All Rights Reserved</p>
  </footer>

</body>
</html>
