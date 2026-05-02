---
name: crawl-budget-manipulation
description: Düşük rekabetli long-tail anahtar kelimelerde hızlı index ve ilk sayfa sıralaması elde etmek için crawl budget manipulation metodolojisini uygular. Anahtar kelime listesi, içerik briefleri, loop iç linkleme haritası, yayın takvimi ve Search Console aksiyon planı üretir. Kullanıcı "hızlı sıralama", "hızlı index", "long-tail kampanya", "crawl deneyi", "yeni site sıralama", "20 içerik kampanyası" gibi taleplerde tetiklenir.
---

# Crawl Budget Manipulation Kampanyası

Bu Skill, **düşük rekabetli long-tail anahtar kelimelerde** Googlebot davranışını yönlendirerek **6-24 saat içinde index** ve **ilk sayfa sıralaması** elde etmeyi hedefleyen tekrarlanabilir bir SEO metodolojisidir.

## Ne Zaman Kullanılır

Bu Skill aşağıdaki durumlarda devreye girer:

- Yeni bir niş/sektörde hızlı görünürlük gerektiğinde
- Hızlı sonuç beklenen, uzun süreli SEO sürecinin uygun olmadığı projelerde
- Düşük rekabetli kelimelerden trafik kanalı açmak istendiğinde
- Yeni bir blog/site için ilk traksiyon yaratmak gerektiğinde
- Mevcut domain otoritesinin tarama bütçesini test etmek istendiğinde

**Uygun DEĞİL:** Yüksek rekabetli kelimeler, ticari yüksek hacimli queryler, marka kelimeleri.

## Metodolojinin Temel Mantığı

Google bot davranışı rastgele değildir. Üç sinyal birleştiğinde tarama bütçesi yönlendirilebilir:

1. **Manuel crawl tetikleme** (Search Console + sitemap)
2. **Loop iç linkleme yapısı** (içerikler birbirine döngüsel bağlanır)
3. **Düşük rekabet + doğru intent** (Google'ın hızlıca değerlendirebileceği kelimeler)

Bu üçlü, Google'a "site aktif ve değerli" sinyali verir → tarama sıklığı artar → index hızlanır.

## Kampanya Aşamaları

Kullanıcı bir niş/sektör verdiğinde, aşağıdaki aşamaları **sırayla** uygula. Her aşamayı tamamladıktan sonra kullanıcıya onay için sun.

### Aşama 1: Anahtar Kelime Seti Üretimi

Hedef: **20 long-tail kelime**, hepsi aynı kategori altında, benzer arama niyetinde.

Kelime kriterleri:
- **Long-tail** (en az 4-6 kelime)
- **Düşük rekabet** (KD < 20 ideal)
- **Soru bazlı veya bilgi-amaçlı intent** (ör. "X nedir", "X nasıl yapılır", "X gerekli mi", "X ne zaman", "X kimler için")
- **Aynı tematik küme** içinde olmalı
- Marka adı veya yüksek hacimli ticari kelime İÇERMEZ

Kelimeleri **iki gruba** böl:
- **Grup A (Toplu Yayın):** 10 kelime, daha direkt soru + temel intent odaklı
- **Grup B (Zamana Yayılmış):** 10 kelime, daha açıklayıcı/derinlikli intent

Çıktı formatı:

```
GRUP A — Toplu Yayın (10 kelime)
1. [kelime] — intent: [tip] — tahmini KD: [düşük/çok düşük]
...

GRUP B — Zamana Yayılmış Yayın (10 kelime)
1. [kelime] — intent: [tip] — tahmini KD: [düşük/çok düşük]
...
```

### Aşama 2: İçerik Briefleri

Her 20 kelime için **standart bir brief şablonu** üret. Tüm briefler aynı yapıda olmalı (deneyin tek değişkeni yayın zamanı).

Her brief için:

```
İÇERİK #[no] — [anahtar kelime]

Başlık (H1): [başlık önerisi, kelimeyi içermeli]
Meta description: [150-160 karakter, kelimeyi içerir, CTA içerir]
URL slug: [kısa, kelimeyi içerir]

H2 yapısı (zorunlu — tüm içeriklerde aynı sayıda):
- [Konu nedir] (giriş)
- [Neden önemli]
- [Nasıl yapılır / kriterleri]
- [Sık yapılan hatalar / dikkat edilecekler]
- [Sonuç + öneriler]

Hedef kelime sayısı: 800-900 (±%10 deney standardı)
İç link: 3 adet (Aşama 3'te belirlenecek)
```

### Aşama 3: Loop İç Linkleme Haritası

20 içerik **döngüsel (loop) yapı** ile birbirine bağlanır. Her içerikten **3 farklı içeriğe** link verilir.

Linkleme matrisi şu mantıkla:
- İçerik #1 → linkler: #2, #5, #11
- İçerik #2 → linkler: #3, #7, #13
- ... (her içerik kendinden sonraki + bir orta + diğer gruptan bir içeriğe link verir)

Çıktı: 20 satırlık bir tablo (Hangi içerik → hangi 3 içeriğe link verecek).

**Ek kural:** Ana sayfaya kart yapısıyla 20 içeriğin tamamı listelenecek (botların doğrudan erişimi için).

### Aşama 4: Yayın Takvimi

**Grup A:** Tüm 10 içerik **tek günde, 2-3 saatlik bir pencerede** yayınlanır.
**Grup B:** 5 gün boyunca, **günde 2 içerik** (sabah + akşam aralığı) yayınlanır.

Çıktı: Tarih/saat bazlı yayın takvimi tablosu.

**Önemli:** Grup A yayınlandıktan sonra **en az 7 gün** beklenir, Grup B sonra başlar. Aksi halde veriler karışır.

### Aşama 5: Search Console Aksiyon Listesi

Her içerik yayınlandıktan **hemen sonra** uygulanacak sabit aksiyonlar:

1. Ana sayfada kart olarak listele
2. Loop iç linklerini ekle (Aşama 3 matrisine göre)
3. XML sitemap güncellemesi (otomatik tetiklenmiyorsa manuel)
4. Search Console → URL Inspection → "Request Indexing"
5. (Opsiyonel) Sosyal sinyal: 1 paylaşım

Çıktı: Her içerik için checkbox'lı aksiyon listesi.

### Aşama 6: Takip Metrikleri Tablosu

Deney süresince takip edilecek metrikler:

| Metrik | Ölçüm Aracı | Kayıt Sıklığı |
|--------|-------------|----------------|
| İlk crawl zamanı | Search Console > Crawl Stats | Günlük |
| Index alma süresi (saat) | Search Console > URL Inspection | İlk 48 saat saatlik |
| Coverage durumu | Search Console > Pages | Günlük |
| İlk gösterim zamanı | Search Console > Performance | Günlük |
| İlk tıklama zamanı | Search Console > Performance | Günlük |
| Ortalama pozisyon (7 gün) | Search Console > Performance | Günlük |
| Hedef kelime sırası | Manuel kontrol / rank tracker | Günlük |

**Takip süresi:** Minimum 14 gün, ideal 21-28 gün.

## Kritik Kurallar (Deney Saflığı)

Deney boyunca aşağıdakiler veri kirliliği yaratır:

- Yeni backlink alma
- Site yapısında değişiklik
- İçeriklerde güncelleme
- Yeni içerik ekleme (deney dışı)
- Robots.txt veya sitemap'te genel değişiklik

## Beklenen Sonuçlar (Referans)

Doğru uygulandığında tipik sonuçlar:

- İçeriklerin %70-90'ı **ilk 6-24 saatte index** alır
- Düşük rekabetli kelimelerin **%40-60'ı 1. sayfada** konumlanır
- Bazı içerikler **ilk 3 sırada** çıkabilir
- Etki **kalıcılığı**, kullanıcı sinyalleri (CTR, dwell time) ile belirlenir

**UYARI:** Bu sonuçlar sadece düşük rekabetli kelimeler için geçerlidir. Yüksek rekabetli kelimelerde aynı metodoloji çalışmaz; oradaki başarı domain otoritesi + backlink + uzun süreli sinyallere bağlıdır.

## Kullanıcıyla Etkileşim Şekli

Bu Skill tetiklendiğinde kullanıcıya **şu sırayla** sor (henüz vermediyse):

1. **Niş/sektör nedir?** (örn. "SEO danışmanlığı", "Beylikdüzü emlak", "veteriner hizmetleri")
2. **Hedef bölge var mı?** (yerel SEO için kritik)
3. **Site yeni mi, mevcut mu?** (yeni siteyse beklentileri kalibre et)
4. **Domain otoritesi tahmini?** (DR/DA biliniyorsa)

Bu bilgiler geldikten sonra **Aşama 1'den başla** ve her aşamayı sırayla teslim et. Bir aşamayı tamamlamadan diğerine geçme.

## Çıktı Tonu

- Türkçe
- Profesyonel ama jargon yüklü değil
- Madde işaretli ve tablolu — ajans deliverable formatında
- Her aşamada "neden bu adım" kısa bir açıklama içersin

## Dikkat Edilecekler

- Eğer kullanıcı yüksek rekabetli kelime verirse, uyar ve uygun olmadığını açıkla
- Eğer 20'den az/fazla kelime istiyorsa, deneyin standart yapısının 10+10 olduğunu hatırlat ama uyum sağla
- Raporlama yapılacaksa, Aşama 6 metrikleriyle "öncesi/sonrası" tablosu öner
