# Render ile Yayına Alma Rehberi

Render.com üzerinden sitenizi yayınlamak için kodlarınızın **GitHub**'da olması gerekir. Netlify Drop gibi sürükle-bırak özelliği yoktur.

İşte adım adım yapmanız gerekenler:

### Adım 1: GitHub Deposu (Repository) Oluşturun
1.  [GitHub.com](https://github.com) adresine gidin ve (yoksa) üye olun.
2.  Sağ üst köşedeki **+** işaretine tıklayıp **"New repository"** seçeneğini seçin.
3.  **Repository name** kısmına bir isim verin (örn: `yilbasi-surprizi`).
4.  **Public** seçili olsun.
5.  **Create repository** butonuna basın.

### Adım 2: Dosyalarınızı Yükleyin
GitHub'da kod kullanmadan dosya yüklemek için:
1.  Oluşturduğunuz yeni sayfada **"uploading an existing file"** linkine tıklayın.
2.  Masaüstünüzdeki **"Yeni klasör"**ün içindeki tüm dosyaları (`index.html`, `assets` klasörü vb.) seçip buraya sürükleyin.
3.  Dosyalar yüklendikten sonra alttaki **"Commit changes"** butonuna basın.

### Adım 3: Render ile Bağlayın
1.  [Render.com](https://render.com) adresine gidin ve üye olun (GitHub ile giriş yapabilirsiniz).
2.  **New +** butonuna basıp **"Static Site"** seçeneğini seçin.
3.  Listede GitHub deponuzu (`yilbasi-surprizi`) göreceksiniz. Yanındaki **"Connect"** butonuna basın.
4.  Açılan sayfada en alttaki **"Create Static Site"** butonuna basın.

### Sonuç
Render sitenizi hazırlayacak ve birkaç dakika içinde size `https://yilbasi-surprizi-xxxx.onrender.com` gibi bir link verecektir.

> **Not:** Bu yöntem Netlify Drop'a göre biraz daha uzundur çünkü GitHub kullanmanızı gerektirir. Ancak Render kullanmak istiyorsanız izlemeniz gereken yol budur. Kolay gelsin! 🚀
