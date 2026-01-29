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
    header {
      background: #0d6efd;
      color: white;
      padding: 20px;
      text-align: center;
    }
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
    .hero {
      background: linear-gradient(to right, #0d6efd, #6610f2);
      color: white;
      padding: 60px 20px;
      text-align: center;
    }
    .hero button {
      margin-top: 20px;
      padding: 12px 20px;
      font-size: 16px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      background: #ffc107;
    }
    .container {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    .card img {
      width: 100%;
      border-radius: 8px;
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
    footer {
      background: #212529;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    .p {
      color: #000;
    }
    .site-header {
  background: #0d6efd;
  padding: 30px 20px;
}

.brand-center {
  display: flex;
  align-items: center;
  justify-content: center;   /* สำคัญมาก */
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

  </style>
</head>
<body>

<header class="site-header">
  <div class="brand-center">
    <img src="file:///C:/Users/User/Downloads/ChatGPT%20Image%20Jan%2028,%202026,%2007_06_57%20PM.png" alt="S.I.T Company Logo" class="logo">
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
  <p>นวัฒกรรมเพื่อความปลอดภัย</p>
  

<section class="container" id="products">
  <h2 style="text-align:center">สินค้าแนะนำ</h2>
  <div class="products">
    <div class="card">
      <img src="file:///C:/Users/User/Downloads/S__4931596.jpg" alt="กล้องอัจฉริยะ(S.I.T.C)">
      <h3>สินค้า A</h3>
      <p class="p">กล้องวงจรปิดสำหรับการจัดการดูแลการจอดรถตามที่สาธารณะได้อย่างมีประสิทธิภาพ ออกแบบมาเพื่ออำนวยความสะดวกให้แก่ประชาชนและหน่วยวยงานต่างๆ</p>
      <p class="p">ติดตั้งง่ายและปลอดภัยจากผู้ใช้งาน<br>
        - ทีมงานและผู้เชี่ยวชาญพร้อมช่วยเหลือทุกเมื่อ<br>
        - ตอบโจทย์การใช้งานที่รวดเร็ว<br>
        - ปลอดภัยจากการใช้ยานพาหนะ</p>
      <div class="price">฿21999</div>
      <a href="https://mail.google.com/mail/u/0/?tab=rm&ogbl#inbox"><button>ติดต่อเรา</button></a>
    </div>
   
  </div>
</section>

<section class="container" id="contact">
  <h2 style="text-align:center">ติดต่อเรา</h2>
  <p style="text-align:center">📞 โทร: 080-085-0053 | 📧 Email: S.I.T.Compax@email.com</p>
</section>

<footer>
  <p>© 2026 My Product | All Rights Reserved</p>
</footer>

</body>
</html>
