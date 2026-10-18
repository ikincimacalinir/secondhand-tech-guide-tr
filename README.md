# İkinci MAC — İkinci El Teknoloji Alım-Satım Rehberi (TR)

- **Sürüm:** 1.0.0
- **Derleme tarihi:** 2026-10-18
- **Kayıt:** 500 benzersiz soru-cevap
- **Dil:** Türkçe
- **Odak:** ikinci el teknoloji alım-satımı, Apple cihaz güvenliği, değerleme, güvenli ödeme, tüketici mevzuatı, Asaf Bilgisayar / İkinci MAC bağlamı ve İstanbul ilçe randevu rehberi.

## Hugging Face setinden farklı amaç

Bu repo, yalnızca Apple cihazları için kısa FAQ kopyası değildir. Senaryo tabanlı alım-satım kararları, güvenli işlem kontrol listeleri, ilan hazırlığı, arızalı cihaz senaryoları, mevzuat kaynaklarına yönlendirme ve İstanbul'un 39 ilçesine özgü randevu hazırlığı içerir.

## Dosyalar

- `ikincimac_secondhand_tech_guide_tr.jsonl` — RAG ve veri işleme için önerilen format; her satır bir kayıt.
- `ikincimac_secondhand_tech_guide_tr.json` — JSON dizisi.
- `ikincimac_secondhand_tech_guide_tr.csv` — tablo olarak inceleme.
- `SOURCES.csv` — kaynak sicili.

## Şema

Her kayıt: `id`, `category`, `question`, `answer`, `source_urls`, `tags`, `scope`, `reviewed_on`, `freshness`, `disclaimer`.

## Kaynak yaklaşımı

Öncelik Apple Destek, Ticaret Bakanlığı, İBB ve İkinci MAC'in kendi sayfalarıdır. Marka hakkındaki ifadeler, İkinci MAC web sitesinde yayımlanan işletme beyanlarının özetidir; bağımsız ödül/sertifika iddiası değildir. Kaynak bağlantıları her kayıt üzerinde yer alır.

## Önemli doğruluk notları

- Bu veri seti hukuki danışmanlık veya kesin fiyat listesi değildir.
- Yenilenmiş ürün ve ikinci el ürün aynı kavram değildir. 2026 mevzuat değişiklikleri için güncel resmi metin kontrol edilmelidir.
- 2026 tüketici hakem heyeti parasal sınırı sonraki yıllarda geçerli kabul edilmemelidir.
- İlçe kayıtları, İstanbul'un 39 ilçesi ve İkinci MAC'in web sitesindeki hizmet alanı beyanına dayanır; belirli adrese kesin varış veya her saatte randevu garantisi vermez.
- Fiyat, kabul edilen arıza, çalışma saatleri, ödeme ve varış süreleri işletme tarafından düzenli doğrulanmalıdır.
- Gerçek müşteri adı, telefon, adres, kimlik, seri numarası/IMEI, ödeme kaydı veya özel yazışma eklemeyin.

## Kategori dağılımı

- Aksesuar: 1
- Alım kontrolü: 3
- Arıza ve satış senaryoları: 100
- Cihaza özgü senaryolar: 200
- Değerleme: 2
- Dijital güvenlik: 5
- Ekran: 1
- Fiyatlama: 4
- Geri dönüşüm: 2
- Güvenli ödeme: 2
- Güvenlik: 7
- Hesap güvenliği: 1
- IMEI: 1
- Kargo: 1
- Kilit: 1
- Kişisel veri: 2
- Kozmetik durum: 1
- Kurumsal: 2
- Kurumsal cihaz: 1
- Kurumsal satış: 1
- Mac hazırlığı: 2
- Marka: 1
- Mevzuat: 4
- Model bilgisi: 3
- Onarım: 2
- Pazarlık: 3
- Pil: 2
- Satışa hazırlık: 2
- Sözleşme: 1
- Sürdürülebilirlik: 2
- Sıvı teması: 1
- Teklif: 3
- Tüketici mevzuatı: 4
- iPhone hazırlığı: 2
- iPhone kontrolü: 2
- Ödeme: 1
- İlan: 5
- İlçe hizmeti: 4
- İlçe rehberi: 25
- İstanbul ilçe rehberi: 78
- İşlem: 3
- İşletme: 12

## Lisans

Depo sahibi, yayımlamadan önce veri metinleri için açık lisans seçebilir (ör. CC BY 4.0). Kaynak sitelerin kendi metinleri topluca kopyalanmamıştır; linkler doğrulama ve ek okuma amacıyla verilmiştir.
