# Novaris Shoe

Novaris Shoe, mobil ve masaüstünde çalışan basit bir ayakkabı tasarım uygulamasıdır.

## Canlı siteye dönüştürme (GitHub Pages)

1. Bu projeyi GitHub'a yükleyin.
2. GitHub'da repo sayfasına gidin: **Settings → Pages**.
3. **Source** bölümünde:
   - Branch: `main` (veya kendi branch'iniz)
   - Folder: `/ (root)`
4. **Save** deyin.
5. 1-2 dakika sonra siteniz şu formatta açılır:
   - `https://<kullanici-adi>.github.io/<repo-adi>/`

## Yerelde çalıştırma

```bash
python -m http.server 8080
```

Tarayıcıdan açın:

`http://localhost:8080`

## Dosya yapısı

- `index.html` → Arayüz
- `styles.css` → Stil dosyası (responsive)
- `app.js` → Etkileşim ve Novaris AI Bot mantığı
