<!DOCTYPE html>
<html lang="id">
<head>
  <link href="https://fonts.googleapis.com/css2?family=Mea+Culpa&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Vollkorn&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Barriecito&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Amethysta&display=swap" rel="stylesheet">
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Data Diri Shyfa Mannawasalwa</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #f8e1f4, #e0f0ff, #F990B8);
      color: #333;
      overflow-x: hidden;
      position: relative;
    }

    /* Efek Kilauan */
    body::before {
      content: '';
      position: absolute;
      top: -50%;
      left: -50%;
      width: 200%;
      height: 200%;
      background: radial-gradient(circle, rgba(255,255,255,0.4) 0%, transparent 70%);
      animation: sparkle 10s linear infinite;
      pointer-events: none;
      z-index: 1;
    }

    @keyframes sparkle {
      0% { transform: rotate(0deg) translateX(0); }
      100% { transform: rotate(360deg) translateX(0); }
    }

    .container {
      position: relative;
      z-index: 2;
      max-width: 600px;
      margin: 50px auto;
      padding: 30px;
      /background: white;/
      border-radius: 20px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.1);
    }

    .profile-flex {
      display: flex;
      align-items: center;
      justify-content: center; /* <--- ubah dari flex-start ke center */
      gap: 30px;
      max-width: 600px;
      margin: 0 auto 30px auto;
    }

    .profile-flex .profile-pic {
      margin: 0;      /* Hapus margin auto */
      display: block;
    }

    .profile-flex h1 {
      text-align: left; /* Pastikan teks rata kiri */
      margin: 0;
      font-size: 50px;
      font-family: 'Mea Culpa';
      color: #F990B8;
    }
    .profile-pic {
      width: 220px;
      height: 220px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #F990B8;
      box-shadow: 0 0 10px rgba(1,1,1,1);
      margin: 0 auto;
      display: block;
    }
    
    img[alt="Foto Shyfa"] {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
    
     .section-white {
  background: none;
  box-shadow: none;
  padding: 0;
  border-radius: 0;
     max-width: 600px;
     margin-left: auto;
     margin-right: auto;
    }

      h1 {
      text-align: center;
      color: #F990B8;
      font-family: 'Mea Culpa';
      font-size: 50px;
    }
    
      h2 {
  text-align: left;
  margin-left: 30px; /* atau coba 40px, sesuaikan */
  color: #7d2ae8;
  font-family: 'Vollkorn';
  font-size: 40px;
}

      h3 {
      text-align: center; 
      color: #F990B8;
      font-family: 'Barriecito', cursive;
      font-size: 50px;
      letter-spacing: 10px;    /* Jarak antar huruf */
      word-spacing: 5px;      /* Jarak antar kata */
      margin-left: auto;
      margin-right: auto;
      }
     
      p {
      text-align: center;
      color: #1E0959 ;
      font-family: 'Amethysta';
      font-size: 20px ;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
     }
     
     .info-flex {
  display: flex;
  gap: 32px; /* jarak antar kotak */
  max-width: 1000px;
  margin: 0 auto 30px auto;
  align-items: flex-start;
}
.tentang-box, .pendidikan-box {
  flex: 1 1 0;
  min-width: 0;
}
.pendidikan-box h2 {
  margin-left: 0;
  text-align: left;
}
.pendidikan-box p {
  text-align: left;
  margin-left: 0;
}
     
     .nama-box {
  display: block;
  text-align: left;
  margin-left: 30px;
  background: #fff;
  border-radius: 16px;
  box-shadow: 0 4px 16px rgba(0,0,0,0.12);
  padding: 25px 25px;
  max-width: 500px;
  font-family: 'Amethysta';
  font-size: 20px;
  color: #1E0959;
}
     
      span {
      text-align: center;
      color:#1E0959 ;
      font-family: 'Amethysta';
      font-size: 20px;
      max-width: 500px;
      margin-left: auto;
      margin-right: auto;
     }
     
     .pendidikan-item {
  background: #fff;
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.12);
  padding: 10px 18px;
  margin-bottom: 10px;
  font-family: 'Amethysta';
  font-size: 18px;
  color: #1E0959;
  text-align: left;
  max-width: 350px;
}

.hobi-box, .softskills-box {
  flex: 1 1 0;
  max-width: 500px;
  background: #fff;
  border-radius: 16px;
  box-shadow: 0 4px 16px rgba(0,0,0,0.12);
  padding: 25px;
  margin-bottom: 10px;
  font-family: 'Amethysta';
  font-size: 18px;
  color: #1E0959;
}

.quote {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  font-style: italic;
  color: #555;
  max-width: 500px;
  margin: 40px auto;
  height: 80px; /* opsional */
}
     
    .contact-title {
  text-align: center;
  margin-left: auto;
  margin-right: auto;
}

    .info {
      margin-top: 10px;
      line-height: 1.2;
      font-size: 15px;
    }

    .footer {
      text-align: center;
      margin-top: 30px;
      font-size: 14px;
      color: #777;
    }

    @media (max-width: 600px) {
      .info strong {
        display: block;
        width: auto;
        margin-top: 10px;
      }
    }
  </style>
</head>
<body>
  <img src="https://uploads.onecompiler.io/43w7wuzdj/43wwc6ytt/color_1-removebg-preview.png" alt="Foto Shyfa">
  <div class="profile-flex">
  <img src="https://uploads.onecompiler.io/43w7wuzdj/43w9auzan/shyfa.jpog.jpg" class="profile-pic">
  <div>
    <h1>hi, i'm Shyfa!</h1>
    <div class="section-white">
      <p>orangnya ceria dan optimis, tapi kadang-kadang terlalu peerfeksionis. Meskipun beitu, selalu berusaha untuk belajar dan berkembang menjadi lebih baik. Senang mencoba hal-hal baru dan mudah berbaur</p>
    </div>
  </div>
</div>
  
  <div class="info-flex">
  <div class="tentang-box">
    <h2>tentang saya</h2>
    <span class="nama-box">
      nama saya
      <span style="color:#1E095;"><b>Shyfa Mannawasalwa</b></span>, biasanya dipanggil 
      <span style="color:#1E095;"><b>Shyfa</b></span> lahir di 
      <span style="color:#1E095;"><b>Batam, 30 Mei 2009</b></span>. 
      saya tinggal di Nongsa, Jl Hang Lekiu, Sambau, Batam, Kepulauan Riau. Saat ini duduk dibangku SMK dan menjadi bagian dari siswi  SMK Negeri 7 yang tertarik dengan teknologi dan digital khususnya pada bidang pemrograman, data analis, dan keamaan digital.
</span>
  </div>
  <div class="pendidikan-box">
    <h2>📚 Pendidikan 📚</h2>
    <p class="pendidikan-item">SD: SDN 001 Batam</p>
<p class="pendidikan-item">SMP: SMPN 8 Batam</p>
<p class="pendidikan-item">SMK: SMKN 7 Batam</p>
<p class="pendidikan-item">Universitas Impian: Universitas Gadjah Mada</p>

  </div>
</div>

<div class="info-flex">
  <div class="hobi-box">
    <h2>Hobi</h2>
    <p>🎧 mendengarkan musik</p>
    <p>🎬 menonton film</p>
    <p>🎨 menggambar</p>
  </div>
  <div class="softskills-box">
    <h2>Soft Skills</h2>
    <p>✓ communication     ✓ teamwork</p>
    <p>✓ leadership        ✓ time management</p>
    <p>✓ creativity        ✓ adaptability</p>
    <p>✓ empathy</p>
  </div>
</div>
      
    <p class="quote">"Belajar bukan tentang menjadi yang terbaik, tetapi tentang menjadi lebih baik dari dirimu yang kemarin."</p>

      
    <h2 class="contact-title">contact</h2>
<p>
  <a href="https://wa.me/6282392996788" target="_blank" style="color:#25D366; text-decoration:none; font-size:22px;">
    WhatsApp
  </a>
  &nbsp;|&nbsp;
  <a href="https://instagram.com/shyfamslwaa" target="_blank" style="color:#BE27F5; text-decoration:none; font-size:22px;">
    Instagram
  </a>
  &nbsp;|&nbsp;
  <a href="https://www.tiktok.com/@bipb1pp" target="_blank" style="color:#010101; text-decoration:none; font-size:22px;">
    TikTok
  </a>
  &nbsp;|&nbsp;
  <a href="mailto:mannawasalwashyfa@gmail.com" style="color:#0072C6; text-decoration:none; font-size:22px;">
    Email
  </a>
</p>  
    

    <div class="footer">
      salam kenal ya! 🌸
    </div>
  </div>
</body>
</html>
