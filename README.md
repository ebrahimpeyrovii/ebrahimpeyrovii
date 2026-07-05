<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ebrahim Peyrovi</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial;
    }

    body {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(-45deg, #0f0f0f, #1a1a1a, #111827, #0f0f0f);
      background-size: 400% 400%;
      animation: bgMove 10s ease infinite;
      color: white;
    }

    @keyframes bgMove {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .card {
      background: rgba(255,255,255,0.05);
      border: 1px solid rgba(255,255,255,0.1);
      padding: 30px;
      border-radius: 20px;
      text-align: center;
      width: 90%;
      max-width: 380px;
      backdrop-filter: blur(10px);
      animation: fadeIn 1.2s ease;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .profile {
      width: 110px;
      height: 110px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #E1306C;
      margin-bottom: 15px;
      animation: pop 1s ease;
    }

    @keyframes pop {
      0% { transform: scale(0); }
      100% { transform: scale(1); }
    }

    h1 {
      font-size: 22px;
      margin-bottom: 10px;
    }

    p {
      font-size: 14px;
      color: #bbb;
      margin-bottom: 20px;
      line-height: 1.6;
    }

    a {
      display: inline-block;
      background: #E1306C;
      color: white;
      padding: 12px 18px;
      text-decoration: none;
      border-radius: 12px;
      font-weight: bold;
      transition: 0.3s;
    }

    a:hover {
      transform: scale(1.05);
      background: #c21f5a;
    }

    /* موبایل */
    @media (max-width: 480px) {
      .card {
        padding: 20px;
      }

      h1 {
        font-size: 18px;
      }
    }
  </style>
</head>

<body>

  <div class="card">

    <!-- عکس پروفایل (اینجا عکس خودت رو بذار) -->
    <img class="profile" src="profile.jpg" alt="Profile">

    <h1>Ebrahim Peyrovi</h1>

    <p>
      این صفحه معرفی رسمی من است 🚀<br>
      برای دیدن فعالیت‌ها وارد اینستاگرام شوید.
    </p>

    <a href="https://www.instagram.com/ebrahimpeyrovii" target="_blank">
      ورود به اینستاگرام
    </a>

  </div>

</body>
</html>
