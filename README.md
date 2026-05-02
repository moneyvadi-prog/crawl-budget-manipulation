# Crawl Budget Manipulation — Claude Skill

Düşük rekabetli long-tail anahtar kelimelerde **6-24 saat içinde index** ve **ilk sayfa sıralaması** elde etmeyi hedefleyen, Claude için sistematik bir SEO metodolojisi.

> Bu Skill; anahtar kelime araştırması, içerik briefleri, döngüsel iç linkleme ve Search Console aksiyon planlamasını tek bir çalışma akışında birleştirir.

---

## Kimler İçin?

- **SEO uzmanları** — Yeni domainlerde veya yeni nişlerde hızlı görünürlük yaratmak isteyenler
- **İçerik ekipleri** — 20 içeriklik kampanyaları sistematik biçimde planlamak isteyenler
- **Ajanslar** — Müşteri raporlarında somut, ölçülebilir deneyler sunmak isteyenler
- **Site sahipleri** — Tarama bütçelerinin nasıl davrandığını test etmek isteyenler

---

## Metodoloji Özeti

Google bot davranışı rastgele değildir. Üç sinyal birleştiğinde tarama bütçesi yönlendirilebilir:

1. **Manuel crawl tetikleme** — Search Console + güncel sitemap
2. **Loop iç linkleme yapısı** — İçerikler birbirine döngüsel bağlanır
3. **Düşük rekabet + doğru intent** — Google'ın hızlıca değerlendirebileceği kelimeler

Bu üçlü, Google'a "site aktif ve değerli" sinyali verir → tarama sıklığı artar → index hızlanır.

### Kampanya Aşamaları

| # | Aşama | Çıktı |
|---|-------|-------|
| 1 | Anahtar kelime seti | 20 long-tail kelime (Grup A: 10 toplu yayın + Grup B: 10 zamana yayılmış) |
| 2 | İçerik briefleri | Her kelime için standart H1/H2/meta yapısı |
| 3 | Loop iç linkleme haritası | 20 satırlık linkleme matrisi |
| 4 | Yayın takvimi | Tarih/saat bazlı program |
| 5 | Search Console aksiyon listesi | Her içerik için tetikleme adımları |
| 6 | Takip metrikleri | Crawl, index, gösterim, pozisyon ölçümleri |

---

## Kurulum (claude.ai)

> **Gereksinim:** Claude Pro, Max, Team veya Enterprise planı (Custom Skills bu planlarda mevcuttur).

1. Bu repodaki `crawl-budget-manipulation.zip` dosyasını indirin
2. **claude.ai → sol menü → Customize → Skills** açın
3. Sağ üstteki **+** butonuna tıklayın → **Upload skill**
4. ZIP dosyasını sürükle-bırak ile yükleyin
5. Toggle'ı **açın** (mavi)

Yüklendikten sonra Claude'a aşağıdaki gibi mesajlar yazdığınızda Skill otomatik olarak tetiklenir:

- *"Beylikdüzü diyetisyen nişi için crawl budget kampanyası kuralım"*
- *"Yeni siteme hızlı index için 20 içeriklik long-tail kampanya planla"*
- *"Düşük rekabet kelimelerde hızlı sıralama almak istiyorum"*

---

## Kullanım Örnekleri

### Senaryo 1: Yeni Lokal Hizmet Sitesi
Yeni açılan bir Beylikdüzü diyetisyen sitesi için 20 long-tail kelime kümesi, briefler ve yayın takvimi.

### Senaryo 2: B2B SaaS Blog Boostu
Düşük otoriteli SaaS blog'unda niş alt-sorulara odaklanan içerik kampanyası.

### Senaryo 3: E-ticaret Kategori Doldurma
Spesifik ürün özelliklerine yönelik soru-bazlı içeriklerle uzun kuyruk trafik açma.

---

## Uygunluk Sınırları

Bu metodoloji **uygundur:**
- ✅ Düşük rekabetli kelimeler (KD < 20)
- ✅ Long-tail soru-bazlı queryler
- ✅ Bilgi-amaçlı veya yumuşak ticari intent
- ✅ Yeni veya orta-otoriteli domainler

Bu metodoloji **uygun değildir:**
- ❌ Yüksek rekabetli ana ticari kelimeler
- ❌ Yüksek hacimli marka kelimeleri
- ❌ Domain otoritesi gerektiren kısa kuyruk queryler

---

## Beklenen Sonuçlar

Doğru uygulandığında tipik gözlemler:

- İçeriklerin %70-90'ı **ilk 6-24 saatte index** alır
- Düşük rekabetli kelimelerin **%40-60'ı 1. sayfada** konumlanır
- Bazı içerikler **ilk 3 sırada** çıkabilir
- Kalıcılık kullanıcı sinyalleri (CTR, dwell time) ile belirlenir

---

## Lisans

MIT License — Bkz. [LICENSE](LICENSE)

Skill içeriğini kişisel veya ticari projelerinizde kullanabilir, fork'layabilir, geliştirebilirsiniz. Atıf zorunlu değildir, ancak takdir edilir.

---

## Katkı

Bu Skill bir **canlı dokümandır** — gerçek deney sonuçlarına göre iyileştirilir. Kendi kampanya verilerinizden çıkan içgörüler varsa, Issues veya Pull Request açarak paylaşabilirsiniz.

---

## Yazar

SEO ve dijital pazarlama alanında çalışan bir uzmanın saha deneyimlerinden damıtılmıştır.

Bu Skill'in temel aldığı orijinal deney metodolojisi için: [Crawl Budget Manipulation Deneyi — Gülşah Arslan](https://www.seodanismanlikhizmeti.com.tr/crawl-budget-manipulation-deneyi-gulsah-arslan/)
