# Eyleme topluluğu

**Ad güncellemesi — 14 Ekim 2026:** Ürünün adı **Eyleme** (önceki adı Eylema), tamamlayıcı ürünün adı **Derleme** (önceki adı Derlema) oldu; **Onama** aynı kaldı. GitHub organizasyonunun adı artık `eyleme-dev` (önceki adı `eylema-dev`). Ana deponun adı artık `eyleme-dev/eyleme`. 15 Ekim 2026 tarihinde altı `eylema-*` alt deposu `eyleme-*` olarak değişti. Alan adları, komutlar, crate/paket adları, ortam değişkenleri, veri yolları ve protokol/şema tanımlayıcıları uyumluluk için mevcut yazımlarını korur. Tarihsel kanıtlar özgün ad ve bağlantıları korur.

Organizasyon profili ve ortak katkı şablonları. [English](README.md).

**Durum: yalnızca depo iskeleti.** Bu kurulum uygulama, kıyaslama sonucu, katalog girdisi, eğitilmiş model veya eğitim koşusu sunmaz.

## Kapsam

Kolay bulunan organizasyon profili ve tutarlı issue/PR girişi.

Üretim Rust kodu, ortak tipler, çalışma zamanı/model yürütmesi ve CLI [Eyleme](https://github.com/eyleme-dev/eyleme) içinde; ürün sözleşmeleri [İngilizce](https://github.com/eyleme-dev/eyleme-docs-en) ve [Türkçe](https://github.com/eyleme-dev/eyleme-docs-tr) belge depolarındadır. [Depo haritası](https://github.com/eyleme-dev/devguide/blob/main/docs/tr/repository-map.md) sınırları tanımlar.

## İlk kabul kapısı

Uygulamadan önce girdi/çıktı sözleşmeleri, kesin çekirdek revizyonu, anlamlı hata durumları, bağımlılık envanteri ve yürütme hedefleri içeren sınırlı bir görev açın. Uygulama ekleyen PR'da belge aşaması kaynak korumasını uygun testlerle değiştirin. Belge CI'ı çalışma zamanı veya donanım kanıtı değildir.

[Katkı rehberini](CONTRIBUTING.tr.md) ve [AGENTS](AGENTS.md) sözleşmesini kullanın. Özel veriler, kimlik bilgileri, operasyon kayıtları ve model ağırlıkları Git dışında kalır. Açık varlıklar için ayrıca onaylanmış depolama, köken ve lisans kararı gerekir; burada depolama veya hizmet kurulmaz. Kendi kaynak kodumuz ve belgelerimiz [Apache-2.0](LICENSE) lisanslıdır. Ayrı belirtilen üçüncü taraf içerikleri, model ağırlıkları ve veri kümeleri kendi koşullarını korur.

Kapsamlı işi [47 Goal issue/milestone indeksiyle](https://github.com/eyleme-dev/devguide/blob/main/docs/tr/github-work-management.md) izle. Plan etiketleri veya hazır koruma isteği yetki ya da uygulanmış dal kuralı oluşturmaz; kabul edilen teslim güncel CI, tam head üzerinde ayrı inceleme ve maintainer kararı gerektirir.
