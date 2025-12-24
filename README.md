# Hava Durumu Projesi – V&V Final Projesi

Bu GitHub deposu, **Yazılım Doğrulama ve Geçerleme (Verification & Validation)** dersi kapsamında gerçekleştirilen final projesine aittir.  
Proje, işveren (client) gereksinimlerine dayalı olarak geliştirilen bir **Hava Durumu Web Uygulaması** ve bu uygulama için yürütülen **QA (Quality Assurance)** sürecini kapsamaktadır.

Bu repo; **client dokümantasyonu**, **QA/test dokümantasyonu** ve **uygulamanın çalışan kodlarını** bir arada sunan bir teslim paketidir.

---

## 📌 Proje Kapsamı ve Amaç

Projenin temel amacı:

- İşveren tarafından iletilen gereksinimlerin doğru anlaşılması
- Bu gereksinimlere uygun bir yazılım ürününün geliştirilmesi
- Geliştirilen ürünün QA ekibi tarafından doğrulanması ve geçerlenmesi
- Test süreçlerinin raporlanması ve belgelenmesi

Bu kapsamda ekip, hem **QA ekibi** hem de **başka bir proje için client rolünü üstlenen ekip** olarak çalışmıştır.

---

## 👥 Proje Rolleri

Bu projede ekip aşağıdaki rolleri üstlenmiştir:

- **QA Ekibi:**  
  Hava Durumu uygulaması için test planı, test senaryoları, test sonuçları ve QA raporunun hazırlanması

- **Client (İşveren) Rolü:**  
  Farklı bir proje için (Otel Yönetim Sistemi) işveren gereksinimlerinin ve client raporunun hazırlanması

---

## 📂 Depo Yapısı ve Dokümanlar

Bu repository içerisinde yer alan dosyalar ve amaçları aşağıda açıklanmıştır:

### 📄 `hava durumu.pdf`
- QA ekibimize iletilen **işveren (client) gereksinim dokümanı**
- Proje vizyonu, beklentiler ve kullanıcı ihtiyaçlarını içermektedir
- **Bizim tarafımızdan oluşturulmamıştır**
- Geliştirme ve test süreci için **referans/fikir alma amacıyla** kullanılmıştır

---

### 📄 `V&V_HavaDurumu_QA.pdf`
- **Bizim ekibimiz tarafından hazırlanmış QA raporu**
- Test planı, test senaryoları, test sonuçları ve doğrulama–geçerleme faaliyetlerini içerir
- Hava Durumu uygulamasının QA sürecini temsil eder

---

## 🧪 QA ve Doğrulama Süreci

QA süreci aşağıdaki adımları kapsamaktadır:

- Client gereksinimlerinin analiz edilmesi
- Test planının oluşturulması
- Test senaryolarının hazırlanması
- Uygulamanın test edilmesi
- Bulgu ve sonuçların raporlanması

Bu süreçlerin detayları **V&V_HavaDurumu_QA.pdf** dosyasında yer almaktadır.

---

### 📄 `V&V_Otel_Client.pdf`
- **Bizim ekibimiz tarafından**, başka bir QA ekibi için hazırlanmış **client (işveren) raporu**
- Ekip olarak yalnızca QA değil, **client rolünü de üstlendiğimizi** göstermektedir
- Dersin çapraz ekip çalışma mantığını destekleyen bir dokümandır

---

### 💻 Uygulama Kaynak Kodları

Aşağıdaki dosyalar, Hava Durumu web uygulamasının çalışan halini temsil eder:

- `index.html` → Uygulamanın ana HTML yapısı
- `styles.css` → Arayüz tasarımı ve tema stilleri
- `script.js` → Uygulama mantığı, API entegrasyonu ve etkileşimler

Uygulama:
- Vanilla JavaScript kullanılarak geliştirilmiştir
- OpenWeather API üzerinden hava durumu verilerini alır
- Sayfa ilk açıldığında şehir slider’ı gösterir

Herhangi bir framework kullanılmadan, tamamen **HTML, CSS ve JavaScript** ile geliştirilmiştir.

### 🚀 Özellikler

* 🌍 Şehir bazlı hava durumu sorgulama
* 📅 7 günlük hava tahmini
* 🌗 Koyu / Açık tema
* 🌐 Türkçe / İngilizce dil desteği
* 🧼 Sade ve performanslı yapı

### 🔑 OpenWeather API Key Alma

Uygulama çalışmak için **OpenWeather API key** gerektirir.

#### 1️⃣ API Key Al

1. [https://openweathermap.org](https://openweathermap.org) adresine git
2. Ücretsiz bir hesap oluştur
3. Giriş yaptıktan sonra **API Keys** bölümüne gir
4. Oluşturulan API key’i kopyala

### 🛠 API Key’i Projeye Ekleme

1. Proje içindeki **`script.js`** dosyasını aç
2. En üstte şu satırı bul:

```js
const API_KEY = "";
```

3. Boş tırnakların içine kendi API key’ini yapıştır:

```js
const API_KEY = "BURAYA_API_KEYINI_YAPISTIR";
```

4. Dosyayı kaydet ve uygulamayı tarayıcıda aç

---

## 👨‍💻 Proje Ekibi

Melih KILIÇ - 2012721026  
Furkan TEKİN - 2112721055  
Yusuf TUNÇ - 2012721024
