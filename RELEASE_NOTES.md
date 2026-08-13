# Dil ve Birim Düzeltmeleri

Bu sürüm, dil ve para birimi davranışları için yapılan son düzeltmeleri içerir.

| Başlık | Loan Calculator | Auto Loan Calculator |
|---|---|---|
| Para birimi seçimi | Para birimi değiştiğinde sonuç kartları ve amortisman tablosu anında güncellenir. | USD, EUR, TRY ve GBP seçicisi eklendi; sonuçlar anında güncellenir. |
| Yerel biçim | Aktif dilin sayı/para biçimi kullanılır. | Aktif dilin sayı/para biçimi kullanılır. |
| Vade birimi | Vade alanı seçili dilde yıl cinsinden açıklanır. | Vade alanı açıkça ay cinsinden belirtilir. |
| CSV | Seçili para birimi ilk satırda yer alır; UTF-8 BOM ve para birimine özel dosya adı kullanılır. | Seçili para birimi ilk satırda yer alır; UTF-8 BOM ve para birimine özel dosya adı kullanılır. |
| Tercihlerin korunması | Seçilen dil ve para birimi tarayıcıda saklanır; sayfa yeniden yüklendiğinde geri yüklenir. | Seçilen dil ve para birimi tarayıcıda saklanır. |

> Seçilen para birimi giriş ve sonuçların hesaplama/gösterim birimidir. Uygulamalar otomatik döviz kuru dönüşümü yapmaz; değerleri seçtiğiniz para biriminde girmelisiniz.

Loan Calculator’da EN, TR, DE, FR, ES, IT, NL, SV, DA, NO, FI ve ZH sözlükleri uygulama içine gömülüdür; bu nedenle dil değişimi harici JSON isteğine veya ağ bağlantısına bağlı değildir. EN dışındaki her dilde görünen `data-i18n` arayüz metinleri İngilizce kaynakla karşılaştırılmış ve marka adı hariç İngilizce geri dönüşü tespit edilmemiştir. Doğrulama için proje kök dizininde `npm run verify` komutunu çalıştırabilirsiniz.
