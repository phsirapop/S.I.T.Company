<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<title>S.I.T Company</title>

<style>
body{
    margin:0;
    font-family: Arial, sans-serif;
    background:#f5f7fa;
}

/* ===== TOP HEADER ===== */
.top-header{
    background:#0d6efd;
    color:white;
    padding:15px 40px;
    display:flex;
    align-items:center;
    justify-content:space-between;
}

.logo-area{
    display:flex;
    align-items:center;
    gap:12px;
}

.logo-area img{
    width:45px;
}

.logo-area span{
    font-size:22px;
    font-weight:bold;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
    font-size:16px;
}

/* ===== HERO ===== */
.hero{
    background: linear-gradient(to right,#0d6efd,#6610f2);
    color:white;
    text-align:center;
    padding:60px 20px;
}

.hero h1{
    font-size:36px;
    margin-bottom:10px;
}

.hero p{
    font-size:18px;
    opacity:0.9;
}

/* ===== PRODUCT ===== */
.product{
    max-width:650px;
    margin:50px auto;
    background:white;
    padding:30px;
    text-align:center;
    border-radius:15px;
    box-shadow:0 10px 25px rgba(0,0,0,0.15);
}

.product h2{
    font-size:26px;
}

.product img{
    max-width:100%;
    border-radius:12px;
}

.product p{
    font-size:17px;
    line-height:1.6;
}

.price{
    font-size:24px;
    font-weight:bold;
    color:#0d6efd;
}

/* ===== FOOTER ===== */
footer{
    background:#222;
    color:white;
    text-align:center;
    padding:15px;
    margin-top:40px;
}
</style>
</head>

<body>

<!-- 🔹 HEADER -->
<div class="top-header">
    <div class="logo-area">
        <img src="logo.png">
        <span>S.I.T.Company</span>
    </div>

    <nav>
        <a href="index.html">หน้าแรก</a>
        <a href="products.html">สินค้า</a>
        <a href="contact.html">ติดต่อเรา</a>
    </nav>
</div>

<!-- 🔹 HERO -->
<div class="hero">
    <h1>เทคโนโลยีความปลอดภัยเพื่อคุณภาพและอนาคต</h1>
    <p>นวัตกรรมเพื่อความปลอดภัย</p>
</div>

<!-- 🔹 PRODUCT -->
<section class="product">
    <h2>สินค้าแนะนำ</h2>

    <img src="pd.jpg" alt="สินค้า">

    <p>
        กล้องวงจรปิดสำหรับการจัดการจราจร<br>
        ติดตั้งง่าย ปลอดภัย และใช้งานสะดวก
    </p>

    <div class="price">฿21,999</div>
</section>

<!-- 🔹 FOOTER -->
<footer>
© 2026 S.I.T Company | All Rights Reserved
</footer>

</body>
</html>
