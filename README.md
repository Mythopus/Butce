# Bütçe Takip

Genel bakış, bütçe kategorileri, cüzdan (kartlar/faturalar/borçlar/takvim) ve işlemler sekmelerine sahip tek sayfalık bütçe takip uygulaması. Veriler tarayıcının `localStorage`'ında, yani sadece kullandığın cihazda/tarayıcıda saklanır.

## Özellikler
- **Genel Bakış:** toplam bakiye, net kâr/zarar, tasarruf %, toplam gelir/gider, basit gelir-gider grafiği, hızlı işlem/fatura ekleme
- **İşlemler:** gelir/gider kayıtları, kategori, tarih, not; gelir/gider filtresi
- **Bütçe:** kategori bazlı aylık limit, harcanan/kalan takibi, ilerleme çubuğu
- **Cüzdan:**
  - *Kartlar:* banka ve kart ekleme
  - *Faturalar:* Elektrik/Su/Doğalgaz/İnternet/Telefon, ödenmedi/gecikmiş/ödendi durumları
  - *Borçlar:* verdiğim/aldığım borç takibi
  - *Takvim:* ödenmemiş fatura ve borçların tarihe göre listesi
- **Profil:** isim, para birimi sembolü, verileri dışa aktarma (.json) ve sıfırlama

## Yerelde çalıştırma
`index.html` dosyasını herhangi bir tarayıcıda çift tıklayarak açman yeterli, ekstra kuruluma gerek yok.

## GitHub'a yükleme

```bash
git init
git add .
git commit -m "İlk sürüm: bütçe takip uygulaması"
git branch -M main
git remote add origin https://github.com/KULLANICI_ADIN/REPO_ADIN.git
git push -u origin main
```

## GitHub Pages ile yayınlama

1. Repo → **Settings** → **Pages**.
2. Repo private ise önce **Settings → General → Danger Zone → Change visibility → Public** yap (Pages'in ücretsiz kullanımı public repo gerektirir).
3. **Pages** sayfasında Branch olarak **main** / `/ (root)` seç, **Save**.
4. Birkaç dakika sonra şu adreste yayında olur:
   `https://KULLANICI_ADIN.github.io/REPO_ADIN/`

## Not
Veriler cihaza özeldir; farklı tarayıcı/cihazdan girdiğinde geçmişi görmezsin. Profil sekmesinden "Verileri Dışa Aktar" ile yedek alabilirsin.
