# BTK Akademi Başvuru Web Sitesi

Bu proje, BTK Akademi eğitim programına başvuruların alındığı basit bir **ASP.NET Core MVC** uygulamasıdır. Uygulamada kullanıcılar, eğitim programlarına başvuru yapabilir ve başvuru listesini görüntüleyebilirler.

## Projede Yer Alan Temel Özellikler

### 1. Başvuru Listesi Görüntüleme
- Kullanıcılar, yapılan başvuruları bir liste halinde görebilirler.
- Her başvuru; e-posta adresi, tam adı, başvuru tarihi ve seçilen kurs bilgilerini içerir.

### 2. Başvuru Yapma
- Kullanıcılar bir form aracılığıyla başvuru yapabilirler.
- Formda; e-posta, ad, soyad, yaş ve kurs seçimi alanları yer almaktadır.
- Aynı e-posta ile birden fazla başvuru yapılmasını önlemek için kontrol yapılmaktadır.

### 3. Geri Bildirim
- Başvuru başarıyla tamamlandığında, kullanıcıya bir geri bildirim sayfası gösterilir.
- Bu sayfada, kullanıcının başvuru yaptığı kurs ve başvuru tarihi yer alır.

## Kullanılan Teknolojiler
- **ASP.NET Core MVC**
- **C#**
- **Entity Framework Core** (veri yönetimi için Repository modeli)
- **Razor View Engine** (görünüm dosyaları)

## Proje Adımları
1. Kullanıcı "Apply" sayfasına giderek başvuru formunu doldurur.
2. Aynı e-posta ile başvuru yapılıp yapılmadığı kontrol edilir. Eğer başvuru varsa hata mesajı gösterilir.
3. Başvuru başarılı olursa, kullanıcının başvuru bilgileri **Repository**'ye kaydedilir ve geri bildirim sayfası görüntülenir.
4. Tüm başvurular, ana sayfada tablo halinde listelenir.

## Ekran Görüntüleri
![Ekran görüntüsü 2024-10-17 160259](https://github.com/user-attachments/assets/da8ec3fb-6733-47b7-9ac5-a3ae6699f61c)
![Ekran görüntüsü 2024-10-17 160216](https://github.com/user-attachments/assets/cbe9d6e6-a2f3-48ce-bb2f-b42209cf1181)
![Ekran görüntüsü 2024-10-17 154053](https://github.com/user-attachments/assets/e11e97f3-2949-4fec-9c43-6756e593323e)
![Ekran görüntüsü 2024-10-17 154617](https://github.com/user-attachments/assets/6bdedc95-6f0f-458a-bdce-d681528656d3)
![Ekran görüntüsü 2024-10-17 154555](https://github.com/user-attachments/assets/bacdac62-4224-4b7f-85a8-07cfe7855340)
