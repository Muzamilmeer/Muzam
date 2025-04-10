<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Muzamil Streetwear</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@700&display=swap');

    body {
      font-family: 'Orbitron', sans-serif;
      margin: 0;
      background: #111;
      color: white;
    }

    header {
      background: linear-gradient(135deg, #000000, #1f1f1f);
      padding: 60px 20px 40px;
      text-align: center;
    }

    .logo {
      font-size: 48px;
      text-transform: uppercase;
      color: #00ffff;
      text-shadow: 0 0 5px #00ffff, 0 0 10px #00ffff, 0 0 15px #00ffff;
      transform: rotateX(20deg);
      animation: flicker 2s infinite;
    }

    @keyframes flicker {
      0%, 100% { opacity: 1; }
      50% { opacity: 0.7; }
    }

    .link-box {
      text-align: center;
      margin-top: 30px;
    }

    .link-box a {
      background: #00ffff;
      color: #000;
      padding: 15px 30px;
      border-radius: 30px;
      text-decoration: none;
      font-size: 18px;
      font-weight: bold;
      box-shadow: 0 0 15px #00ffff;
      transition: 0.3s ease-in-out;
    }

    .link-box a:hover {
      background: #008080;
      color: white;
      box-shadow: 0 0 25px #00ffff;
    }

    .product-section {
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 20px;
    }

    .product {
      background: #222;
      border-radius: 10px;
      padding: 20px;
      margin-bottom: 30px;
      box-shadow: 0 0 15px rgba(0,255,255,0.1);
      text-align: center;
    }

    .product img {
      width: 100%;
      max-width: 300px;
      border-radius: 10px;
      margin-bottom: 15px;
    }

    .product h3 {
      margin: 0 0 10px;
      color: #00ffff;
    }

    .product a {
      background: #25D366;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 30px;
      display: inline-block;
      transition: background 0.3s ease;
    }

    .product a:hover {
      background: #128C7E;
    }

    .contact-section {
      text-align: center;
      margin: 60px 20px;
    }

    .contact-section img {
      width: 200px;
      border-radius: 10px;
      margin-top: 20px;
      box-shadow: 0 0 15px #00ffff;
    }

    .contact-section .profile-img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      margin-top: 20px;
      object-fit: cover;
      box-shadow: 0 0 20px #00ffff;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">Muzamil Streetwear</div>
  </header>

  <div class="link-box">
    <a href="https://example.com/muzamil-streetwear">Visit Store</a>
  </div>

  <div class="product-section">
    <div class="product">
      <h3>Urban T-Shirt - ₹499</h3>
      <img src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1744284703/urban-t-shirt-design-614_1080x_pbjxnu.jpg" alt="Urban T-Shirt">
      <a href="https://wa.me/919103594759?text=Hi%2C%20I%20want%20to%20buy%20Urban%20T-Shirt%20from%20Muzamil%20Streetwear" target="_blank">Buy on WhatsApp</a>
    </div>

    <div class="product">
      <h3>Jordan Shoes - ₹1499</h3>
      <img src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1744284703/image_3_qwbkmd.jpg" alt="Jordan Shoes">
      <a href="https://wa.me/919103594759?text=Hi%2C%20I%20want%20to%20buy%20Jordan%20Shoes%20from%20Muzamil%20Streetwear" target="_blank">Buy on WhatsApp</a>
    </div>

    <div class="product">
      <h3>Baggy Jeans - ₹799</h3>
      <img src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1744284703/6b9e4944-ff98-4921-9989-afb5bf2518ca1733547766499-DENIMLOOK-Men-Relaxed-Fit-Stretchable-Baggy--Jeans-275173354-2_1_w3mivu.jpg" alt="Baggy Jeans">
      <a href="https://wa.me/919103594759?text=Hi%2C%20I%20want%20to%20buy%20Baggy%20Jeans%20from%20Muzamil%20Streetwear" target="_blank">Buy on WhatsApp</a>
    </div>
  </div>

  <div class="contact-section">
    <h2>Contact Us</h2>
    <p>📞 +91 9103594759</p>
    <p>Scan to Chat on WhatsApp:</p>
    <img src="https://api.qrserver.com/v1/create-qr-code/?data=https://wa.me/919103594759&size=200x200" alt="QR Code">
    <div>
      <img class="profile-img" src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1744286893/IMG_20250403_185247_xzlxll.jpg" alt="Muzamil">
    </div>
  </div>

</body>
</html>
