# .github

Organizasyon profili ve ortak katkı şablonları. [English](README.md).

**Durum: yalnızca depo iskeleti.** Bu kurulum uygulama, kıyaslama sonucu, katalog girdisi, eğitilmiş model veya eğitim koşusu sunmaz.

## Kapsam

Kolay bulunan organizasyon profili ve tutarlı issue/PR girişi.

Üretim Rust kodu, ortak tipler, çalışma zamanı/model yürütmesi ve CLI [eylema](https://github.com/eylema-dev/eylema) içinde; ürün sözleşmeleri [İngilizce](https://github.com/eylema-dev/eylema-docs-en) ve [Türkçe](https://github.com/eylema-dev/eylema-docs-tr) belge depolarındadır. [Depo haritası](https://github.com/eylema-dev/devguide/blob/main/docs/tr/repository-map.md) sınırları tanımlar.

## İlk kabul kapısı

Uygulamadan önce girdi/çıktı sözleşmeleri, kesin çekirdek revizyonu, anlamlı hata durumları, bağımlılık envanteri ve yürütme hedefleri içeren sınırlı bir görev açın. Uygulama ekleyen PR'da belge aşaması kaynak korumasını uygun testlerle değiştirin. Belge CI'ı çalışma zamanı veya donanım kanıtı değildir.

[Katkı rehberini](CONTRIBUTING.tr.md) ve [AGENTS](AGENTS.md) sözleşmesini kullanın. Özel veriler, kimlik bilgileri, operasyon kayıtları ve model ağırlıkları Git dışında kalır. Açık varlıklar için ayrıca onaylanmış depolama, köken ve lisans kararı gerekir; burada depolama veya hizmet kurulmaz. Kendi kaynak kodumuz ve belgelerimiz [Apache-2.0](LICENSE) lisanslıdır. Ayrı belirtilen üçüncü taraf içerikleri, model ağırlıkları ve veri kümeleri kendi koşullarını korur.

Kapsamlı işi [47 Goal issue/milestone indeksiyle](https://github.com/eylema-dev/devguide/blob/main/docs/tr/github-work-management.md) izle. Plan etiketleri veya hazır koruma isteği yetki ya da uygulanmış dal kuralı oluşturmaz; kabul edilen teslim güncel CI, tam head üzerinde ayrı inceleme ve maintainer kararı gerektirir.
