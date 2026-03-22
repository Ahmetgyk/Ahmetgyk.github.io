# FORM — Kas Takip Uygulaması

Kişisel kas gelişimi takip uygulaması.

## GitHub Pages'e Deploy

1. Bu repoyu fork'la veya yeni repo oluştur
2. `index.html` dosyasını repo köküne yükle
3. **Settings → Pages → Source: Deploy from branch → main → / (root) → Save**
4. `https://KULLANICI_ADI.github.io/REPO_ADI` adresinden eriş

## Veri Güvenliği

Veriler tarayıcının `localStorage`'ında saklanır.

### ⚠️ Önemli
- **Düzenli yedek al** — Header'daki ⬇️ butonu ile JSON yedek indir
- **Tarayıcı verilerini silme** — "Site verilerini temizle" seçeneği verileri siler
- **Aynı cihaz & tarayıcı** kullandığın sürece veriler korunur

### Yedekleme
- Header'daki **⬇️ (download)** butonu → `form_yedek_TARIH.json` indirir
- Header'daki **⬆️ (upload)** butonu → yedek dosyasını geri yükler
- **Haftada bir yedek almak** yeterli
