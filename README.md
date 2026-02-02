<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Saya | Awak</title>

<!-- Google Font -->
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&display=swap" rel="stylesheet">

<!-- AOS Animation -->
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:'Playfair Display',serif;
}

body{
  background:#f7f4ee;
}

.section{
  min-height:100vh;
  display:flex;
  justify-content:center;
  align-items:center;
  background:url("https://i.imgur.com/ZKQ7Q7U.jpg") center/cover no-repeat;
}

.card{
  background:rgba(255,255,255,0.88);
  padding:40px 25px;
  width:88%;
  max-width:380px;
  text-align:center;
  border-radius:12px;
}

.subtitle{
  letter-spacing:3px;
  font-size:12px;
  margin-bottom:25px;
}

.monogram{
  font-size:90px;
  font-weight:600;
  color:#6c7b3d;
  line-height:0.9;
}

.monogram span{
  font-size:60px;
}

.names{
  letter-spacing:4px;
  margin:18px 0;
  font-size:14px;
}

.date{
  margin:22px 0;
  font-size:15px;
}

.date small{
  display:block;
  margin-top:5px;
  font-size:12px;
}

.ayat{
  font-size:13px;
  font-style:italic;
  margin-top:20px;
}

.hashtag{
  margin-top:22px;
  font-size:12px;
  opacity:0.7;
}

.scroll{
  position:absolute;
  bottom:25px;
  font-size:11px;
  opacity:0.6;
}
</style>
</head>

<body>

<!-- PAGE 1 -->
<section class="section">
  <div class="card" data-aos="zoom-in">
    <div class="subtitle">WALIMATULURUS</div>

    <div class="monogram">S<br><span>A</span></div>

    <div class="names">SAYA | AWAK</div>

    <div class="date">
      25.10.2025
      <small>3 Jamadilawal 1447H</small>
    </div>

    <div class="ayat">
      “Dan Kami menciptakan kamu berpasang-pasangan”
      <br><small>Surah An-Naba’ (78:8)</small>
    </div>

    <div class="hashtag">#SayaAwakSelamanya</div>
  </div>

  <div class="scroll">SCROLL ↓</div>
</section>

<!-- PAGE 2 -->
<section class="section">
  <div class="card" data-aos="fade-up">
    <div class="subtitle">DENGAN PENUH KESYUKURAN</div>

    <p style="margin-top:20px;font-size:14px;">
      Kami menjemput<br>
      Dato’ | Datin | Tuan | Puan
    </p>

    <p style="margin-top:20px;font-size:14px;">
      Ke majlis perkahwinan
    </p>

    <p style="margin-top:20px;font-size:15px;font-weight:600;">
      Saya & Awak
    </p>

    <p style="margin-top:20px;font-size:13px;">
      📍 Dewan Impian Raya<br>
      🕰 11.00 pagi – 4.00 petang
    </p>
  </div>
</section>

<!-- PAGE 3 -->
<section class="section">
  <div class="card" data-aos="fade-up">
    <div class="subtitle">HUBUNGI KAMI</div>

    <p style="margin-top:20px;font-size:14px;">
      👤 Saya: 012-3456789
    </p>

    <p style="margin-top:15px;font-size:14px;">
      👤 Awak: 019-8765432
    </p>

    <a href="https://wa.me/60123456789" 
       style="display:inline-block;margin-top:25px;
       padding:10px 25px;border:1px solid #6c7b3d;
       text-decoration:none;color:#6c7b3d;font-size:13px;">
       RSVP WhatsApp
    </a>
  </div>
</section>

<!-- Scripts -->
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>
AOS.init({
  duration:1400,
  once:true
});
</script>

</body>
</html>
