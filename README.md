
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Mir Store Stylish</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      padding: 0;
      margin: 0;
    }
    header {
      background: linear-gradient(45deg, #000000, #1a1a1a);
      color: white;
      padding: 20px;
      text-align: center;
    }
    .header-content {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 20px;
    }
    .header-content img {
      width: 60px;
      height: 60px;
      border-radius: 50%;
      box-shadow: 0 0 10px #00ffff;
    }
    .header-content h1 {
      font-size: 2.5em;
      font-weight: bold;
      margin: 0;
      text-shadow: 0 0 10px #00ffff, 0 0 20px #00ffff;
    }
    .container {
      padding: 20px;
    }
    .product {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 20px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product img {
      width: 100%;
      max-width: 300px;
      border-radius: 10px;
      margin: 10px 0;
    }
    .order-button {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 20px;
      background: #25D366;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }
    .order-button:hover {
      background: #128C7E;
    }
    .contact {
      text-align: center;
      padding: 30px 20px;
    }
    .contact img {
      margin-top: 10px;
      width: 200px;
      border-radius: 10px;
      box-shadow: 0 0 10px #888;
    }
  </style>
</head>
<body>

  <header>
    <div class="header-content">
      <img src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1744286893/IMG_20250403_185247_xzlxll.jpg" alt="Logo">
      <h1>Mir Store</h1>
    </div>
  </header>

  <div class="container">

    <div class="product">
      <h3>Urban T-Shirt - ₹499</h3>
      <img src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1744284703/urban-t-shirt-design-614_1080x_pbjxnu.jpg" alt="Urban T-Shirt">
      <a class="order-button" href="https://wa.me/919103594759?text=Hi%2C%20I%20want%20to%20buy%20Urban%20T-Shirt%20from%20Mir%20Store">Order Now on WhatsApp</a>
    </div>

    <div class="product">
      <h3>Jordan Shoes - ₹1499</h3>
      <img src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1744284703/image_3_qwbkmd.jpg" alt="Jordan Shoes">
      <a class="order-button" href="https://wa.me/919103594759?text=Hi%2C%20I%20want%20to%20buy%20Jordan%20Shoes%20from%20Mir%20Store">Order Now on WhatsApp</a>
    </div>

    <div class="product">
      <h3>Baggy Jeans - ₹799</h3>
      <img src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1744284703/6b9e4944-ff98-4921-9989-afb5bf2518ca1733547766499-DENIMLOOK-Men-Relaxed-Fit-Stretchable-Baggy--Jeans-275173354-2_1_w3mivu.jpg" alt="Baggy Jeans">
      <a class="order-button" href="https://wa.me/919103594759?text=Hi%2C%20I%20want%20to%20buy%20Baggy%20Jeans%20from%20Mir%20Store">Order Now on WhatsApp</a>
    </div>

  </div>

  <div class="contact">
    <h3>Contact Us</h3>
    <p>Call or WhatsApp: <strong>+91 9103594759</strong></p>
    <p>Scan this QR to chat on WhatsApp:</p>
    <img src="https://api.qrserver.com/v1/create-qr-code/?data=https://wa.me/919103594759&size=200x200" alt="WhatsApp QR Code">
  </div>

</body>
</html>
