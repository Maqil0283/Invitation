<html lang="ms">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>A | A Engagement</title>

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Great+Vibes&display=swap" rel="stylesheet">

<!-- AOS -->
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Playfair Display', serif;
  scroll-behavior: smooth;
}

body {
  background: #f6f3ed;
  overflow-x: hidden;
  display: flex;
  flex-direction: column;
  align-items: center;
}

/* =========================
   INVITATION CARD
========================= */
.card {
  margin: 80px 20px 40px;
  opacity: 0;
  animation: fadeIn 0.8s ease forwards;
  background: rgba(255, 255, 255, 0.88);
  width: 90%;
  max-width: 500px;
  padding: 40px 25px;
  border-radius: 18px;
  text-align: center;
  box-shadow: 0 10px 30px rgba(0,0,0,0.1);
}

@keyframes fadeIn {
  to { opacity: 1; }
}

.subtitle {
  font-size: 13px;
  letter-spacing: 3px;
  margin-bottom: 20px;
  color: #6b7a3c;
}

/* MONOGRAM */
.monogram {
  margin-bottom: 18px;
}

.monogram span {
  font-family: 'Great Vibes', cursive;
  font-size: 80px;
  color: #6b7a3c;
  letter-spacing: -6px;
  text-shadow: 1px 1px 2px rgba(0,0,0,0.25);
}

.names {
  font-size: 15px;
  letter-spacing: 4px;
  margin: 16px 0;
  font-weight: 600;
}

.date {
  font-size: 15px;
  margin: 22px 0;
}

.date small {
  display: block;
  font-size: 12px;
  margin-top: 6px;
}

.ayat {
  font-size: 14px;
  font-style: italic;
  line-height: 1.6;
  margin-top: 20px;
}

.hashtag {
  font-size: 12px;
  opacity: 0.8;
  margin-top: 20px;
}

/* =========================
   PAGE 2 SECTION
========================= */
.section {
  width: 100%;
  min-height: 100vh;
  padding: 50px 20px;
  display: flex;
  justify-content: center;
  align-items: center;
  background: url("https://raw.githubusercontent.com/Maqil0283/assets/refs/heads/main/floral-bg.png.png") center/cover no-repeat;
}

.location-card {
  background: rgba(255, 255, 255, 0.88);
  width: 90%;
  max-width: 500px;
  padding: 40px 25px;
  border-radius: 18px;
  text-align: center;
  box-shadow: 0 10px 30px rgba(0,0,0,0.1);
}

.location-card h2 {
  font-size: 18px;
  margin-bottom: 16px;
  color: #6b7a3c;
}

.location-card p {
  font-size: 14px;
  margin-bottom: 22px;
}

/* MAP */
.map-container {
  width: 100%;
  height: 240px;
  border-radius: 12px;
  overflow: hidden;
  margin-bottom: 25px;
}

.map-container iframe {
  width: 100%;
  height: 100%;
  border: 0;
}

/* GALLERY */
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
  gap: 12px;
}

.gallery img {
  width: 100%;
  border-radius: 12px;
  object-fit: cover;
  transition: transform 0.3s ease;
}

.gallery img:hover {
  transform: scale(1.08);
}

/* RESPONSIVE */
@media(max-width:480px) {
  .monogram span { font-size: 60px; }
  .map-container { height: 200px; }
}
</style>
</head>

<body>

<!-- INVITATION CARD -->
<section>
  <div class="card">
    <div class="subtitle">Engagement of</div>

    <div class="monogram">
      <span>A&amp;A</span>
    </div>

    <div class="names">Aqil | Alya</div>

    <div class="date">
      30.05.2025
      <small>10:00 am</small>
    </div>

    <div class="ayat">
      “Dan Kami menciptakan kamu berpasang-pasangan”<br>
      <small>Surah An-Naba’ (78:8)</small>
    </div>

    <div class="hashtag">#AlyakeAqilhayat</div>
  </div>
</section>

<!-- LOCATION & GALLERY -->
<section class="section" id="location">
  <div class="location-card" data-aos="fade-up">
    <h2>Lokasi Majlis</h2>
    <p>Lot 2494, Jalan Joget 4, Taman Ria Jaya, 08000, Sungai Petani, Kedah</p>

    <div class="map-container">
      <iframe
        src="https://www.google.com/maps?q=Lot+2494,+Jalan+Joget+4,+Taman+Ria+Jaya,+08000,+Sungai+Petani,+Kedah&output=embed"
        loading="lazy"
        allowfullscreen>
      </iframe>
    </div>

    <h2>Kenangan Kami</h2>
    <div class="gallery">
      <img src="https://raw.githubusercontent.com/Maqil0283/assets/refs/heads/main/Foto%201.HEIC" alt="Foto 1">
      <img src="https://raw.githubusercontent.com/Maqil0283/assets/refs/heads/main/Foto3.JPG" alt="Foto 2">
    </div>

    <div class="hashtag">#AlyakeAqilhayat</div>
  </div>
</section>

<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>
AOS.init({ duration:1200, once:true });
</script>

</body>
</html>
