# Katkida Bulunma Rehberi (CONTRIBUTING)

T.C. Kastamonu Belediyesi tarafindan gelistirilen acik kaynakli kamu ve akilli sehir projelerine gosterdiginiz ilgi ve katki icin tesekkur ederiz.

## Kurumsal Ilkeler ve Standartlar

Kamu yararini gozeten yazilim gelistirme sureclerimizde asagidaki temel standartlar uygulanir:

1. **Kamu Verisi ve Kisisel Verilerin Korunmasi (KVKK):**
   - Kod tabanina, test dosyalarina veya ornek veri setlerine gercek vatandas verileri, uretim kimlik bilgileri, API anahtarlari veya dahili ag adresleri kesinlikle eklenemez.
2. **Mimari ve Tip Guvenligi:**
   - Gelistirilen servislerde katmanli mimari, guclu tip denetimi ve anlasilir API dokumantasyonu zorunludur.
3. **Sifir Emoji Politikasi:**
   - Commit mesajlarinda, PR aciklamalarinda, kod ici yorumlarda ve dokumanlarda unicode emoji kullanilmaz.
4. **Temiz Kod ve Test Kapsami:**
   - Gonderilen tum Pull Request (PR) bildirimlerinde ilgili birim testleri (unit tests) ve entegrasyon dogrulari yer almalidir.

## Katki Sureci

1. **Depoyu Fork Edin:** Katki saglamak istediginiz belediye reposunu kendi hesabiniza fork ediniz.
2. **Dal (Branch) Olusturun:** `git checkout -b ozellik/<ozellik-adi>` veya `git checkout -b duzeltme/<hata-adi>`.
3. **Degisiklikleri Isleme (Commit):**
   - Standart commit formati uygulayiniz (ornek: `feat(api): add citizen application validation`, `fix(auth): correct token expiry window`).
4. **Test ve Dogrulama:** Kodunuzun tum yerel testlerden basariyla gectiginden emin olunuz.
5. **Pull Request Acin:** Degisikliklerinizi belediyemizin ana dalina (`main` veya `master`) hedeflenen aciklayici bir PR ile iletiniz. PR incelemesi Araştırma ve Geliştirme Müdürlüğü teknik ekibi tarafindan yapilacaktir.
