# WorldWise

Dünyadaki gezdiğiniz şehirleri ve ülkeleri harita üzerinde kaydedip takip edebileceğiniz, React tabanlı bir seyahat günlüğü uygulaması.

## Özellikler

- **Harita Üzerinde Kayıt:** Gittiğiniz şehirleri harita üzerinden seçip kaydedin.
- **Şehir ve Ülke Listesi:** Ziyaret ettiğiniz şehirleri ve ülkeleri listeleyin.
- **Not Ekleme:** Her şehir için notlarınızı ekleyin.
- **Kullanıcı Girişi:** Basit demo kullanıcı ile giriş/çıkış yapabilme.
- **Veri Saklama:** Şehir verileri local bir JSON server ile saklanır.
- **Modern Arayüz:** Responsive ve kullanıcı dostu tasarım.
- **Hızlı ve Kolay Kurulum:** Vite ile hızlı geliştirme ortamı.

## Kurulum ve Kullanım

1. **Depoyu klonlayın:**

   ```sh
   git clone <repo-url>
   cd final
   ```

2. **Bağımlılıkları yükleyin:**

   ```sh
   npm install
   ```

3. **JSON Server'ı başlatın:**

   ```sh
   npm run server
   ```

   Bu komut, `data/cities.json` dosyasını 9000 portunda bir REST API olarak sunar.

4. **Geliştirme sunucusunu başlatın:**
   ```sh
   npm run dev
   ```
   Uygulamayı [http://localhost:5173](http://localhost:5173) adresinde görüntüleyebilirsiniz.

> **Not:** Uygulamanın tam çalışması için hem frontend (`npm run dev`) hem de backend (`npm run server`) aynı anda açık olmalıdır.

## Kullanılan Teknolojiler

- **React** (SPA mimarisi)
- **React Router** (Sayfa yönlendirme)
- **React Context API** (Global state yönetimi)
- **React Leaflet & Leaflet** (Harita ve markerlar)
- **Vite** (Hızlı geliştirme ortamı)
- **JSON Server** (Mock API)
- **React Datepicker** (Tarih seçici)
- **CSS Modülleri** (Bileşen bazlı stiller)

## Demo Kullanıcı Bilgileri

- **E-posta:** `jack@example.com`
- **Şifre:** `qwerty`

## Ekran Görüntüleri

> Buraya uygulamanın ekran görüntülerini ekleyebilirsiniz.

---

Daha fazla bilgi için kodu inceleyebilirsiniz. Katkıda bulunmak isterseniz PR gönderebilirsiniz!
