<!DOCTYPE html>
<html lang="ru">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Hotel Arslan - Baş sahypa</title>
    <link rel="stylesheet" href="static/styles/style.css" />
    <script defer src="static/java/script.js"></script>
  </head>
  <body>
    <header class="header">
      <div class="container">
        <div class="logo">Hotel Arslan</div>
        <nav class="nav">
          <a href="#home">Baş sahypa</a>
          <a href="#gallery">Galereýa</a>
          <a href="#contact">Habarlaş</a>
        </nav>
      </div>
    </header>

    <section id="home" class="hero">
      <div class="container hero-content">
        <h1>Hoş geldiňiz Hotel Arslana</h1>
        <p>Dynç alyş üçin iň amatly ýer</p>
        <a href="#contact" class="btn">Habarlaşmak</a>
      </div>
    </section>

    <section id="gallery" class="gallery">
      <div class="container">
        <h2>Galereýa</h2>
        <div class="gallery-grid">
          <img src="static/images/qwer.jpg2.jpg" alt="#" />
          <img src="static/images/000000.jpg" alt="Otag 2" />
          <img src="static/images/app_large.webp" alt="Otag 3" />
          <img src="static/images/XXXL2.jpg" alt="#" />
        </div>
      </div>
    </section>

    <section id="contact" class="contact">
      <div class="container">
        <h2>Habarlaşmak</h2>
        <form>
          <input type="text" placeholder="Adyňyz" required />
          <input type="email" placeholder="Email" required />
          <textarea placeholder="Habaryňyz" required></textarea>
          <button type="submit">Ugrat</button>
        </form>
      </div>
    </section>

    <footer class="footer">
      <div class="container">
        <p>© 2025 Hotel Arslan. Ähli hukuklar goralan.</p>
      </div>
    </footer>
  </body>
</html>
[Upl/* Umumy sazlamalar */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}

body {
  background-color: #eef0f7;
  color: #130e0e;
}

.container {
  width: 50%;
  max-width: 1200px;
  margin: 0 auto;
}

/* Header */
.header {
  background-color: #03090f;
  padding: 20px 0;
  color: rgb(255, 251, 251);
}

.logo {
  font-size: 24px;
  font-weight: bold;
}

.nav {
  margin-top: 10px;
}

.nav a {
  color: rgb(254, 248, 248);
  margin-right: 20px;
  text-decoration: none;
  font-weight: 600;
  transition: color 0.3s;
}

.nav a:hover {
  color: #ffcc00;
}

/* Hero bölümi */
.hero {
  background: url("https://s.101hotelscdn.ru/uploads/image/hotel_image/665632/4950180.jpg")
    center center/cover no-repeat;
  height: 100vh;
  display: flex align-items center;
  color: rgb(223, 207, 207);
  text-align: center;
}

.hero-content {
  width: 100%;
}

.hero h1 {
  font-size: 48px;
  margin-bottom: 15px;
  text-shadow: 2px 2px 6px rgba(4, 0, 12, 0.7);
}

.hero p {
  font-size: 22px;
  margin-bottom: 25px;
  text-shadow: 1px 1px 5px rgba(10, 0, 0, 0.6);
}

.btn {
  background-color: #ffcc00;
  color: #003366;
  padding: 15px 30px;
  border-radius: 50px;
  font-weight: 700;
  text-decoration: none;
  transition: background-color 0.3s;
}

.btn:hover {
  background-color: #e6b800;
}

/* Galereýa */
.gallery {
  padding: 60px 0;
  text-align: center;
}

.gallery h2 {
  font-size: 36px;
  margin-bottom: 30px;
}

.gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.gallery-grid img {
  width: 100%;
  border-radius: 10px;
  object-fit: cover;
  transition: transform 0.3s ease;
  cursor: pointer;
}

.gallery-grid img:hover {
  transform: scale(1.05);
}

/* Kontakt formasy */
.contact {
  background-color: #e8f0fe;
  padding: 50px 0;
  text-align: center;
}

.contact h2 {
  font-size: 36px;
  margin-bottom: 25px;
}

.contact form {
  max-width: 500px;
  margin: 0 auto;
}

.contact input,
.contact textarea {
  width: 100%;
  padding: 15px;
  margin-bottom: 20px;
  border: 1px solid #ccc;
  border-radius: 8px;
  font-size: 16px;
  resize: vertical;
}

.contact button {
  background-color: #010d18;
  color: white;
  padding: 15px 40px;
  border: none;
  border-radius: 50px;
  font-weight: 700;
  cursor: pointer;
  transition: background-color 0.3s;
}

.contact button:hover {
  background-color: #001a4d;
}

/* Footer */
.footer {
  background-color: #020a13;
  color: white;
  padding: 20px 0;
  text-align: center;
  margin-top: 40px;
}

/* Responsiwlik */
@media (max-width: 768px) {
  .hero h1 {
    font-size: 32px;
  }

  .hero p {
    font-size: 18px;
  }
}
oading style.css…]()
