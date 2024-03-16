# mask_application
Bu kod, COVID-19 pandemisi sırasında hayati önem taşıyan maske dağıtımını yönetmek için tasarlanmıştır. Kullanıcıların maske alıp almadıklarını kontrol eder ve henüz maske almamış olanlara maske sağlar. Eğer bir kullanıcı zaten maske almışsa, sistem ek maske vermez. Bu, kaynakların etkin kullanımını sağlamak ve maske stoklarının adil bir şekilde dağıtılmasını desteklemek için önemlidir.

## Özellikler
- Kullanıcı maske alıp almadığını kontrol eder.
- Maske almamış kullanıcılara otomatik olarak maske verir.
- Maske zaten verilmişse, tekrar vermez.

## Nasıl Çalışır?
Kod, kullanıcıların maske alıp almadığını bir veritabanında tutar. Bir kullanıcı maske istediğinde, sistem önce veritabanını kontrol eder. Eğer kullanıcıya daha önce maske verilmemişse, maske verilir ve veritabanı güncellenir. Aksi takdirde, sistem kullanıcıya zaten maske verildiğini bildirir.

## Katkıda Bulunma
Bu projeye katkıda bulunmak isteyen herkesi teşvik ediyoruz. İyileştirmeler, hata düzeltmeleri ve yeni özellikler için pull request'ler açabilirsiniz.

Bu proje, pandemi sırasında toplumun ihtiyaçlarını karşılamak ve sağlık güvenliğini artırmak amacıyla geliştirilmiştir.
