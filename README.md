<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>MARTC | Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #ffffff;
      color: #222;
      text-align: center;
    }

    header {
      background: #111;
      color: #fff;
      padding: 40px 20px;
    }

    section {
      padding: 50px 20px;
    }

    h1, h2 {
      margin-bottom: 20px;
    }

    a {
      text-decoration: none;
    }

    /* Contact */
    .contact a {
      display: block;
      margin: 12px 0;
      font-size: 18px;
      color: #222;
    }

    .social-icons a {
      margin: 0 12px;
      font-size: 28px;
    }

    footer {
      background: #f5f5f5;
      padding: 20px;
      font-size: 14px;
    }

    /* WhatsApp floating */
    .whatsapp-float {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25D366;
      width: 60px;
      height: 60px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 30px;
      color: #fff;
      box-shadow: 0 4px 8px rgba(0,0,0,.3);
      z-index: 999;
    }

    .whatsapp-float:hover {
      transform: scale(1.1);
    }
  </style>
</head>

<body>

<header>
  <h1>MARTC</h1>
  <p>Creative Portfolio</p>
</header>

<section>
  <h2>About</h2>
  <p>
    Creative media & content platform.<br>
    Writing – Development – Visual storytelling.
  </p>
</section>

<section class="contact" id="contact">
  <h2>Contact</h2>

  <a href="mailto:mansour@martc.live">
    <i class="fa-solid fa-envelope"></i>
    mansour@martc.live
  </a>

  <a href="https://wa.me/966508122281" target="_blank">
    <i class="fa-brands fa-whatsapp"></i>
    +966 50 812 2281
  </a>

  <a href="https://www.martc.live" target="_blank">
    <i class="fa-solid fa-globe"></i>
    www.martc.live
  </a>

  <div class="social-icons" style="margin-top:25px;">
    <a href="https://linktr.ee/mansour.art.center" target="_blank" title="All My Links">
      <i class="fa-solid fa-link"></i>
    </a>
  </div>
</section>

<footer>
  © 2026 MARTC – All Rights Reserved
</footer>

<!-- WhatsApp Button -->
<a href="https://wa.me/966508122281" class="whatsapp-float" target="_blank">
  <i class="fa-brands fa-whatsapp"></i>
</a>

</body>
</html>
