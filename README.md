# Kedi ve Köpek API Projesi

Bu proje, The Cat API ve The Dog API kullanarak rastgele kedi ve köpek resimleri gösteren interaktif bir web uygulamasıdır. Kullanıcılar tek tıkla yeni hayvan resimleri görüntüleyebilir.

## Özellikler

- **Rastgele Resim Gösterimi**: Her tıklamada yeni kedi ve köpek resimleri
- **Responsive Tasarım**: Tüm cihazlarda uyumlu görüntüleme
- **Yükleme Göstergesi**: Resimler yüklenirken görsel feedback
- **Hata Yönetimi**: API istekleri için gelişmiş hata yakalama
- **Otomatik İlk Yükleme**: Sayfa açıldığında otomatik resim gösterimi

## Kullanılan Teknolojiler

- **HTML5**: Sayfa yapısı
- **CSS3**: 
  - Grid layout
  - Flexbox
  - Transitions
  - Media queries
- **JavaScript**: 
  - Async/Await
  - Fetch API
  - Error handling
  - DOM manipulation

## API'ler

- [The Cat API](https://api.thecatapi.com)
- [The Dog API](https://api.thedogapi.com)

## Kurulum

1. Projeyi klonlayın:
```bash
git clone https://github.com/kullaniciadi/proje-adi.git
```

2. Proje dizinine gidin:
```bash
cd proje-adi
```

3. `index.html` dosyasını bir web tarayıcısında açın.

## Dosya Yapısı

```
├── index.html           # Ana HTML dosyası (tüm kod bu dosyada)
└── README.md           # Proje dokümantasyonu
```

## Kullanım

1. Web sayfasını açın
2. Sayfa otomatik olarak ilk resimleri yükleyecektir
3. "Yeni Kedi Getir" veya "Yeni Köpek Getir" butonlarına tıklayarak yeni resimler görüntüleyebilirsiniz

## CSS Sınıfları

- `.container`: Ana grid container
- `.card-container`: Her bir hayvan kartı için container
- `.card-wrapper`: Resim wrapper'ı
- `.pet-image`: Hayvan resmi stil ayarları
- `.loading`: Yükleme durumu için opacity efekti

## JavaScript Fonksiyonları

- `fetchWithTimeout()`: Timeout özellikli API isteği
- `getNewCat()`: Yeni kedi resmi getirme
- `getNewDog()`: Yeni köpek resmi getirme

## Hata Yönetimi

- API istekleri için timeout kontrolü
- Resim yükleme hatalarını yakalama
- Konsola hata mesajları yazma

## Tarayıcı Desteği

- Chrome (son 3 versiyon)
- Firefox (son 3 versiyon)
- Safari (son 3 versiyon)
- Edge (son 3 versiyon)

## Performans Optimizasyonları

1. Resim yükleme optimizasyonu
2. API istekleri için timeout mekanizması
3. Yükleme durumu göstergesi

## Gelecek Özellikler

- [ ] Resim favorileme sistemi
- [ ] Sosyal medya paylaşım butonları
- [ ] Daha fazla hayvan türü
- [ ] Resim filtreleme özellikleri
- [ ] Görsel efekt seçenekleri

## Katkıda Bulunma

1. Fork'layın
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'feat: Amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Pull Request oluşturun

## Hata Raporlama

Hataları GitHub Issues üzerinden bildirebilirsiniz. Lütfen:

1. Hatanın detaylı açıklamasını
2. Hatayı yeniden oluşturma adımlarını
3. Beklenen davranışı
4. Ekran görüntülerini (varsa) ekleyin
