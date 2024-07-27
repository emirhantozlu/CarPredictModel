# Araba Fiyat Tahmin Projesi

## Proje Amacı
Bu proje, model, yıl ve kilometre gibi çeşitli özelliklere dayalı olarak ikinci el arabaların fiyatlarını tahmin etmeyi amaçlamaktadır. Projede, araba verileri üzerinde kapsamlı bir analiz yapılmış, uygun makine öğrenimi modelleri seçilmiş ve bu modeller kullanılarak araba fiyatları doğru bir şekilde tahmin edilmiştir.

## Kullanılan Veri Setleri
**Train Veri Seti:** Model, yıl, kilometre, motor hacmi, güç ve fiyat gibi bilgileri içeren ikinci el arabalar hakkında veriler içermektedir.

## Proje ve Araştırma Basamakları
### Veri Setinin Seçilmesi
İkinci el araba fiyatları ile ilgili veri seti seçilmiş ve kullanılmıştır.

### Veri Seti Üzerinde Ön İşleme Yapılması
Verilerin temizlenmesi, eksik değerlerin işlenmesi, normalizasyon ve diğer ön işleme adımları gerçekleştirilmiştir.

### Kullanılan Modeller
- **Lineer Regresyon:** Temel bir regresyon modeli olarak kullanılmıştır.
- **Ridge Regresyon:** Lineer regresyonun düzenlenmiş bir versiyonu olarak kullanılmıştır.
- **Lasso Regresyon:** Öznitelik seçimi yapmak için kullanılmıştır.
- **ElasticNet Regresyon:** Ridge ve Lasso regresyonlarının bir kombinasyonu olarak kullanılmıştır.
- **K-En Yakın Komşu (KNN) Regresyonu:** Basit bir makine öğrenimi algoritması olarak kullanılmıştır.

### Model Eğitimi ve Performans Değerlendirmesi
Her bir model, eğitim verisi üzerinde eğitilmiş ve doğruluk oranları, F1 skoru ve ROC AUC skoru gibi performans metrikleri kullanılarak değerlendirilmiştir.

## Temel Bulgular
Proje kapsamında yapılan çalışmalar sonucunda elde edilen performans metrikleri, çeşitli regresyon modellerinin araba fiyatlarını tahmin etme konusundaki başarılarını göstermiştir. Özellikle, belirli modeller diğerlerine kıyasla daha yüksek doğruluk oranları ve daha iyi F1 skoru sağlamıştır.

## İletişim
Daha fazla bilgi veya projeyle ilgili sorularınız için benimle iletişime geçebilirsiniz:
 
[Emirhan Tozlu](https://www.linkedin.com/in/emirhntozlu/)
