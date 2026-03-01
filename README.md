# Dekosis - KYS (Yüz Tanıma ile Yoklama Uygulaması)

Bu proje, **Emgu CV** kütüphanesi kullanılarak geliştirilmiş bir yüz tanıma ve yoklama uygulamasıdır. Uygulama, kamera ile yüz tanıma yaparak yoklama işlemini hızlı ve kolay bir şekilde gerçekleştirir.

## Özellikler

- **Yüz Tanıma**: Kameradan alınan görüntüdeki yüzleri tespit eder ve tanır (HaarCascade).
- **Yoklama Sistemi**: Tanınan yüzleri veri tabanındaki kayıtlarla karşılaştırarak yoklama alır.
- **Raporlama**: Alınan yoklamaları bir rapor dosyasına kaydeder ve mail olarak gönderir.
- **Kullanıcı Dostu Arayüz**: Basit ve anlaşılır bir kullanıcı arayüzü ile işlemleri kolaylaştırır.

## Gereksinimler

- **.NET Framework 4.7.2** veya üstü
- **Visual Studio 2022** veya üstü (isteğe bağlı geliştirme için)
- **Emgu CV Kütüphanesi**
  - `Emgu.CV`
  - `Emgu.CV.UI`
  - `Emgu.CV.Bitmap`
- Kamera (yüz tanıma işlemi için)

## Kurulum ve Çalıştırma

1. **Uygulamayı Çalıştırın**
   - `bin` klasöründe bulunan `Dekosis - KYS.exe` dosyasını çift tıklayarak çalıştırabilirsiniz.

## 🖼️ Ekran Görüntüleri

**Giriş Paneli:**

![Giriş Paneli](screenshots/1.jpg)

**Ana Ekran:**

![Ana Ekran](screenshots/2.jpg)

**Öğrenci Kayıt**

![Öğrenci Kayıt](screenshots/3.jpg)

**Kayıt Kontrol**

![Kayıt Kontrol](screenshots/4.jpg)

**Yoklama**

![Yoklama](screenshots/5.jpg)

**Yoklama Raporu**

![Yoklama Raporu](screenshots/6.jpg)

------------------------------------------------------------------------

## Lisans

Bu proje MIT Lisansı ile lisanslanmıştır. Daha fazla bilgi için [LICENSE](LICENSE) dosyasına bakabilirsiniz.

------------------------------------------------------------------------
