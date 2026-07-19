# Abel Project - Müfredat Koçu AI

## 📖 Genel Bakış
Abel Project, öğrenciler ve eğitimciler için tasarlanmış modern bir "Müfredat Koçu AI" çalışma alanıdır. Bu tek sayfa uygulaması, konu başlıklarını yönetme, markdown formatında içerik görüntüleme ve yapay zeka destekli sohbet özelliklerini bir araya getirir.

## ✨ Özellikler

### Temel Özellikler
- **Üç Panelli Arayüz**: 
  - Sol panel: Konu başlıkları ve navigasyon
  - Orta panel: Markdown içerik görüntüleme
  - Sağ panel: AI sohbet asistanı
- **Markdown Desteği**: Marked.js kütüphanesi ile zengin metin formatlama
- **Matematik Formülleri**: KaTeX ile LaTeX tabanlı matematik gösterimi
- **AI Entegrasyonu**: OpenRouter API üzerinden akıllı sohbet desteği
- **Tema Desteği**: Açık ve koyu tema arasında geçiş yapabilme
- **Responsive Tasarım**: Mobil, tablet ve masaüstü uyumlu arayüz

### Gelişmiş Özellikler
- **Local Storage**: Taslakları otomatik kaydetme ve geri yükleme
- **Toast Bildirimleri**: Kullanıcı etkileşimleri için anlık geri bildirimler
- **Animasyonlu Arka Plan**: Modern ve dinamik görsel deneyim
- **Kopyalama Kolaylığı**: Kod bloklarını tek tıkla kopyalama
- **Yazma Animasyonları**: AI yanıtları için doğal yazma efekti

## 🛠️ Teknolojiler

### Frontend
- **HTML5/CSS3**: Semantik yapı ve modern stil
- **JavaScript (Vanilla)**: Etkileşimli fonksiyonlar
- **Tailwind CSS**: Utility-first CSS framework
- **Marked.js**: Markdown parser
- **KaTeX**: Matematik formülü render motoru

### Fontlar
- **DM Sans**: Başlıklar ve genel metin
- **Inter**: Arayüz elemanları
- **JetBrains Mono**: Kod blokları

### API Entegrasyonları
- **OpenRouter API**: Çoklu LLM desteği için AI gateway

## 🚀 Kurulum ve Kullanım

### Gereksinimler
- Modern bir web tarayıcısı (Chrome, Firefox, Safari, Edge)
- İnternet bağlantısı (CDN kaynakları ve API erişimi için)
- OpenRouter API anahtarı (AI özellikleri için)

### Çalıştırma
1. `abelproject.html` dosyasını herhangi bir web tarayıcısında açın
2. Sağ paneldeki ayarlardan OpenRouter API anahtarınızı girin
3. Konu başlıklarını seçerek içerik görüntülemeye başlayın
4. AI sohbet özelliğini kullanarak sorular sorun

### API Anahtarı Ayarlama
```javascript
// Sağ panel ayarlar bölümünden API anahtarınızı girin
// veya doğrudan konsol üzerinden:
localStorage.setItem('openrouter_api_key', 'your-api-key-here');
```

## 📁 Proje Yapısı

```
abel-project/
├── abelproject.html      # Ana uygulama dosyası
├── README.md            # Bu dosya
└── (CDN kaynakları)     # Tailwind, Marked.js, KaTeX
```

## 🎨 Özelleştirme

### Tema Değiştirme
- Sağ üst köşedeki tema butonu ile açık/koyu mod arasında geçiş yapabilirsiniz
- Tercihiniz local storage'da saklanır

### AI Model Seçimi
- Farklı LLM modelleri arasında seçim yapabilirsiniz
- Model tercihleri oturum boyunca saklanır

## 🔒 Güvenlik ve Gizlilik

- API anahtarları sadece tarayıcınızda local storage'da saklanır
- Hiçbir veri sunucuya gönderilmez (API çağrıları hariç)
- Tüm işlemler istemci tarafında gerçekleşir

## 🤝 Katkıda Bulunma

Proje geliştirmesine katkıda bulunmak için:
1. Projeyi fork edin
2. Yeni bir branch oluşturun (`git checkout -b feature/yeni-ozellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'yeni özellik eklendi'`)
4. Branch'inizi push edin (`git push origin feature/yeni-ozellik`)
5. Pull Request oluşturun

## 📝 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için LICENSE dosyasına bakınız.

## 📞 İletişim

Sorularınız ve önerileriniz için proje deposu üzerinden issue açabilirsiniz.

---

**Not**: Bu proje eğitim amaçlı geliştirilmiş olup, üretim ortamında kullanılmadan önce güvenlik testlerinden geçirilmelidir.
