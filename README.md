# Rota link sayfaları

Bu klasör GitHub Pages'e (dnm79445kw-spec.github.io) olduğu gibi yüklenir.

- `p/index.html`: paylaşım linkleri (`/p/?id=<id>`). Uygulama yüklüyse iPhone linki direkt Rota'da açar, değilse bu sayfa indirme butonunu gösterir.
- `u/index.html`: profil linkleri (`/u/?id=<id>`).
- `404.html`: eski `/p/<id>` linkleri için yedek.
- `index.html`: ana adres.
- `og.png`, `icon.png`, `apple-touch-icon.png`: mesajlaşma uygulamalarındaki link önizlemesi ve logo.
- `.well-known/apple-app-site-association`: iPhone'un "bu adresin linklerini Rota açar" bilgisini buradan okur.
- `.nojekyll`: GitHub Pages'in `.well-known` klasörünü gizlememesi için.

`STORE_URL` satırına TestFlight genel bağlantısını, App Store'a çıkınca App Store adresini yaz. App Store'a çıkınca `apple-itunes-app` satırının yorumunu kaldırıp App Store ID'sini yaz; Safari'de üstte "Rota'yı aç / indir" bandı çıkar.
