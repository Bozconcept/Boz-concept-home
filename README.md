# Boz-concept-home
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Boz Concept Home</title>
  <style>
    body { margin: 0; font-family: Arial, sans-serif; background-color: #f9f9f9; color: #333; }
    header { background-color: #000; color: #FFD700; padding: 1rem; text-align: center; }
    nav { background-color: #111; display: flex; justify-content: center; gap: 2rem; padding: 1rem; }
    nav a { color: #FFD700; text-decoration: none; font-weight: bold; }
    .hero { padding: 2rem; text-align: center; background: url('https://via.placeholder.com/1200x400') center/cover no-repeat; color: white; }
    .section { padding: 2rem; max-width: 1000px; margin: auto; }
    .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1.5rem; }
    .product { background: white; padding: 1rem; border-radius: 10px; box-shadow: 0 2px 6px rgba(0,0,0,0.1); text-align: center; }
    .product img { width: 100%; height: auto; border-radius: 10px; }
    .cta { background-color: #000; color: #FFD700; padding: 2rem; text-align: center; }
    footer { background-color: #111; color: #bbb; padding: 2rem; text-align: center; }
  </style>
</head>
<body>
  <header>
    <h1>Boz Concept Home</h1>
    <p>Modern & Şık Banyo Düzenleyiciler</p>
  </header>
  <nav>
    <a href="#urunler">Ürünler</a>
    <a href="#hakkimizda">Hakkımızda</a>
    <a href="#iletisim">İletişim</a>
  </nav>

  <section class="hero">
    <h2>Banyonuzda Şıklık ve Konfor</h2>
    <p>Delmeden montaj, paslanmaz çelik kalitesiyle.</p>
  </section>

  <section id="urunler" class="section">
    <h2>Öne Çıkan Ürünler</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/300x200" alt="Altı Kancalı Banyo Sepeti">
        <h3>Altı Kancalı Banyo Sepeti</h3>
        <a href="#">Trendyol’da İncele</a>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/300x200" alt="Tezgah Üstü Raf">
        <h3>Tezgah Üstü Raf</h3>
        <a href="#">Trendyol’da İncele</a>
      </div>
    </div>
  </section>

  <section id="hakkimizda" class="section">
    <h2>Hakkımızda</h2>
    <p>Boz Concept Home, fonksiyonel ve modern banyo düzenleyicileri ile yaşam alanlarını daha estetik ve kullanışlı hale getiren bir markadır. Uygun fiyatlı, kaliteli ve şık tasarımlar sunar.</p>
  </section>

  <section id="iletisim" class="cta">
    <h2>İletişim</h2>
    <p>Instagram: <a href="#" style="color:#FFD700;">@bozconcepthome</a></p>
    <p>E-posta: info@bozconcepthome.com</p>
  </section>

  <footer>
    <p>&copy; 2025 Boz Concept Home - Tüm hakları saklıdır.</p>
  </footer>
</body>
</html>
