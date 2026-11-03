# Rota link sayfaları

Bu klasör GitHub Pages'e (ya da kendi alan adına) olduğu gibi yüklenir.

- `.well-known/apple-app-site-association`: iPhone'un "bu adresin linklerini Rota açar" bilgisini buradan okur.
- `404.html`: `/p/<id>` ve `/u/<id>` adresleri bu sayfaya düşer. Uygulama yüklü değilse indirme butonu gösterir.
- `index.html`: ana adres.
- `.nojekyll`: GitHub Pages'in `.well-known` klasörünü gizlememesi için.

`STORE_URL` satırına TestFlight genel bağlantısını (sonra App Store adresini) yaz.
