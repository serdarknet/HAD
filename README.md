# HAD — HyperOS Android Debloater

**HAD**, Xiaomi, Redmi ve POCO cihazlarda Android/HyperOS paketlerini **root gerektirmeden ADB üzerinden** yönetmek için geliştirilmiş Windows uygulamasıdır.

> HAD kapalı kaynak (proprietary) bir yazılımdır. Kaynak kod bu public repository'de yayımlanmaz.

## Özellikler

- Windows 10 x64 ve Windows 11 x64 desteği
- Xiaomi, Redmi ve POCO cihaz desteği
- HyperOS / Android cihaz ve ROM bilgilerinin algılanması
- ADB bağlantı ve yetkilendirme kontrolü
- Paketleri **Güvenli / İsteğe bağlı / Dikkat / 3. taraf** şeklinde sınıflandırma
- Türkçe paket açıklamaları ve olası etki bilgileri
- Uygulamayı user 0 için kaldırma
- Uygulamayı devre dışı bırakma ve yeniden etkinleştirme
- Kaldırılmış paketleri geri yükleme
- APK / split APK yedekleme
- Debloat DB güncelleme
- Android Platform Tools kurulumu
- Android USB sürücülerini kurma/güncelleme
- Normal yeniden başlatma ve Fastboot modunda yeniden başlatma
- Kritik sistem paketlerine karşı koruma
- RAM, depolama ve batarya bilgilerinin görüntülenmesi

## Güvenlik yaklaşımı

HAD yeni veya doğrulanmamış bir paketi otomatik olarak güvenli kabul etmez. Kritik sistem, güvenlik ve donanım bileşenleri için ek koruma uygulanır. Bununla birlikte her ROM ve cihaz farklı olabileceğinden işlem öncesinde önemli verilerinizi yedekleyin.

## İndirme

Programı **GitHub Releases** bölümünden indirin. Repository içindeki otomatik `Source code (zip/tar.gz)` dosyaları HAD uygulamasının özel kaynak kodu değildir; GitHub'ın bu public dokümantasyon repository'sinin anlık arşivleridir.

**Önerilen dosya:** `HAD.exe`

## Sistem gereksinimleri

- Windows 10 x64 veya Windows 11 x64
- Xiaomi / Redmi / POCO Android cihaz
- USB veri bağlantısı
- USB hata ayıklama
- Güncelleme ve kurulum işlevleri için internet bağlantısı
- Sürücü kurulumu için gerektiğinde yönetici yetkisi

## İlk çalıştırma

HAD her açılışta sorumluluk reddi metnini gösterir. **Kabul Ediyorum** seçeneği 15 saniyelik okuma süresinden sonra görüntülenir. Sorumluluk reddi kabul edilmeden ana uygulama açılmaz.

## USB hata ayıklama

1. **Ayarlar > Telefon hakkında** bölümünü açın.
2. HyperOS/OS sürümüne 7 kez dokunarak geliştirici seçeneklerini etkinleştirin.
3. **Ayarlar > Ek ayarlar > Geliştirici seçenekleri** bölümüne girin.
4. **USB hata ayıklama** seçeneğini açın.
5. Telefonu veri aktarımını destekleyen USB kablosuyla bilgisayara bağlayın.
6. Telefonda çıkan RSA/USB hata ayıklama yetkilendirmesini onaylayın.

## APK yedekleme

HAD APK ve split APK dosyalarını yedekleyebilir. Android güvenlik modeli nedeniyle root olmadan başka uygulamaların `/data/data` altındaki özel verilerinin tam yedeği alınamaz.

## Sorumluluk reddi

HAD kullanıcının kendi sorumluluğunda kullanılır. Uygulamanın kullanımı veya hatalı kullanımı sonucunda oluşabilecek veri kaybı, sistem/uygulama işlevlerinin bozulması, açılış problemleri, yazılımsal arızalar, cihazın kullanılamaz hale gelmesi, garanti/servis süreçleri veya diğer doğrudan/dolaylı zararlardan geliştirici sorumlu tutulamaz.

Ayrıntılı metin için [DISCLAIMER.md](DISCLAIMER.md) dosyasını okuyun.

## Resmî olmayan yazılım

HAD; Xiaomi, Redmi, POCO, Google veya diğer üreticilerin resmî uygulaması değildir ve bu kuruluşlarla bağlantılı, sponsorlu veya onaylanmış değildir. İlgili marka ve ticari markalar kendi sahiplerine aittir.

## Lisans

HAD kapalı kaynak yazılımdır. Derlenmiş uygulamanın kullanım şartları için [LICENSE.txt](LICENSE.txt) dosyasına bakın.

## İletişim

**Geliştirici:** Serdar Kılıç  
**E-posta:** serdar-kilic@msn.com  
**GitHub:** https://github.com/serdarknet
