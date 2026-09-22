# birliktekazan-site

Birlikte Kazan uygulamasının halka açık sayfaları: ana sayfa, gizlilik politikası (KVKK aydınlatma),
kullanım koşulları, hesap silme. Statik HTML, derleme yok.

Yayın: GitHub Pages (`main` dalı, kök). Uygulama içindeki linkler ve Google Play / Google Cloud
OAuth kayıtları bu sayfaları gösterir.

## Domain bağlama (birliktekazan.com)

1. Bu repo köküne `CNAME` dosyası: içeriği `birliktekazan.com`.
2. DNS (Cloudflare): `A` kayıtları `185.199.108.153`, `185.199.109.153`, `185.199.110.153`,
   `185.199.111.153`; `www` için `CNAME altaibbahat.github.io`. Proxy kapalı (DNS only) başlat.
3. GitHub → Settings → Pages → Custom domain → `birliktekazan.com`, "Enforce HTTPS".
4. Google Cloud → Auth Platform → Branding: ana sayfa + gizlilik linklerini domain'e çevir,
   domaini "Authorized domains"a ekle → Audience → Publish app.

## Değişiklik

Metinlerin yürürlük tarihi sayfa başında; içerik değişince tarihi güncelle.
