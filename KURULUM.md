# Linie B2 – iPhone / iPad kurulumu (ücretsiz, hesap girişi yok)

Bu klasördeki dosyalar ücretsiz bir sunucuya konur, telefonda bir kez açılır ve ana ekrana eklenir.
Ana ekrandan açılan uygulama internetsiz de çalışır.

## 1) GitHub Pages’e yükle (bilgisayardan, bir kere)
1. github.com’da yeni bir repo aç, örneğin `linie-b2` (Public).
2. "Add file → Upload files" ile bu klasördeki dosyaların hepsini yükle:
   index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, apple-touch-icon.png
3. Settings → Pages → Source: "Deploy from a branch", Branch: `main` / `(root)` → Save.
4. 1–2 dakika sonra adres hazır: `https://KULLANICIADIN.github.io/linie-b2/`

## 2) iPhone / iPad’e ekle
1. Bu adresi **Safari** ile aç (Chrome değil).
2. Paylaş butonu → **Ana Ekrana Ekle** → Ekle.
3. Uygulamayı artık ana ekrandaki Bahni simgesinden aç.

## Bilmen gerekenler
- İlerleme cihazın kendisinde saklanır. Uygulamayı silersen ilerleme de silinir.
- Bu adresi Android tablette Chrome ile açıp "Ana ekrana ekle" dersen orada da aynı şekilde çalışır.
- Uygulamayı güncellediğimde yeni index.html’i repoya yükle ve sw.js içindeki
  `linie-b2-v1` değerini `v2` yap; telefon bir sonraki açılışta yeni sürümü alır.
