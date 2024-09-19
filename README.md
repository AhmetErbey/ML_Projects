
# Bölgelere göre sıcaklık tahmini yapan bir ML projesi

Not: Notebook'un kaggle linki ve data setinin linki aşağıda bulunmaktadır.

## Giriş
Küresel ısınma, Dünya'nın ortalama sıcaklığındaki sürekli artışla karakterize edilen kritik bir sorundur. Bu fenomen, doğrudan sıcaklık ölçümleri ve diğer gözlemlenebilir çevresel değişiklikler ile kanıtlanmaktadır. Şehir düzeyindeki küresel sıcaklık verilerini analiz etmek, iklim değişikliğinin etkilerini anlamak için değerli bilgiler sunabilir. Ayrıca, hava durumu verileri, satış tahmini, lojistik optimizasyonu ve enerji tüketimi gibi çeşitli veri bilimi uygulamaları için önemli bir rol oynar.

## Veri Kümesi Genel Bakış

Bu veri kümesi, dünya çapındaki büyük şehirler için günlük ortalama sıcaklık verilerini sunar ve bu veriler, araştırma ve veri analizi için güçlü bir araçtır. Sıcaklık verilerini kullanarak iklim trendlerini inceleyebilir, çevresel araştırmaları destekleyebilir veya hava koşullarından etkilenen endüstrilerde tahmin modellerini geliştirebilirsiniz.



## İçerik
 Dünya genelindeki şehirler için günlük ortalama sıcaklık değerleri.

Olası Kullanım Alanları

İklim Değişikliği Analizi: Bu verileri kullanarak şehir düzeyinde küresel ısınma trendlerini analiz edebilir ve farklı bölgelerin nasıl etkilendiğini gözlemleyebilirsiniz.

Satış Tahmini: Hava durumu verilerini, özellikle hava koşullarına duyarlı sektörlerde ürün talebini tahmin eden modellerde kullanabilirsiniz.

Lojistik Optimizasyonu: Taşıma rotalarını ve programlamayı optimize etmek için sıcaklık verilerini analiz edebilirsiniz, özellikle hava koşullarına bağlı endüstrilerde.

Enerji Tüketim Tahmini: Enerji talebini tahmin etmek için, özellikle ısıtma ve soğutma sektörlerinde hava durumu verileri önemli bir değişkendir.

Dosya: city_temperature.csv

## Kullanılan yöntemler ve adımlar

####  Bazı temel kütüphanelerin import edilmesi ve Veriye Genel bir bakış
####  Keşifsel Veri Analizi (EDA - Exploratory Data Analysis)

####  VERİ ÖN İŞLEME - (LABEL ENCODING / SPLITING TRAIN AND TEST SETS / SCALING)

####  Standart Scaler Methodu ile Veriyi Ölçekleme

####  Hiperparametre Optimizasyonu

####  K-means modeli ile Gözetimsiz öğrenme

####  Supervised ve Unsupervised yöntemle verinin eğitilmesi



  
## ilgili kaynaklar

İşte bazı ilgili kaynaklar:(üzerine tıklayınız)

[Kaggle notebookunun linki](https://www.kaggle.com/code/ahmeterbeyy/s-cakl-k-tahmini)(kaggleda save olurken hata aldı bazı grafikler githubdaki gibi gözükmüyor)

[Kaggle notebookunu 2. Grafiklerin hatasız gözüktüğü verisyonu](https://www.kaggle.com/code/ahmeterbeyy/s-cakl-k-tahmini-supervised-unsupervised-withgraf)(error almamış şekili)

[Github notebookunun linki](https://github.com/matiassingers/awesome-readme)

[Kaggledaki Veri setinin linki](https://www.kaggle.com/datasets/sudalairajkumar/daily-temperature-of-major-cities/data)
