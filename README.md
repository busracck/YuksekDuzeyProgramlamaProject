# machine-learning-project
Predict Future Sales

Bu dokümanda, Kaggle'ın 'Predict Future Sales' yarışmasından elde edilen veri setleri kullanılarak oluşturulan modeller ve analizler yer almaktadır. Projede, regresyon, sınıflandırma ve görüntü işleme algoritmaları kullanılarak satış tahmini ve ürün sınıflandırma işlemleri gerçekleştirilmiştir.
1. Gerekli Kütüphaneler
Projede kullanılan kütüphaneler: pandas, numpy, matplotlib, seaborn, scikit-learn ve TensorFlow. Bu kütüphaneler veri işleme, model eğitimi ve görselleştirme için kullanılmıştır.
2. Veri Setlerinin Yüklenmesi ve İncelenmesi
Projede kullanılan veri setleri şunlardır:
- sales_train.csv: Satış verileri
- items.csv: Ürün bilgileri
- item_categories.csv: Ürün kategorileri
- shops.csv: Mağaza bilgileri

Veri setleri yüklenmiş ve ilk birkaç satırı incelenmiştir.
3. Veri Ön İşleme
Veriler üzerinde eksik değerler kontrol edilmiş, tarih formatları dönüştürülmüş ve bağımlı/bağımsız değişkenler oluşturulmuştur. Ayrıca kategorik değişkenler sayısal değerlere dönüştürülmüştür.
4. Regresyon Modeli ile Satış Tahmini
Aylık satış tahmini için doğrusal regresyon modeli eğitilmiştir. Modelin performansı RMSE metriği ile değerlendirilmiştir.
5. Sınıflandırma Modeli ile Ürün Kategorisi Tahmini
Ürünlerin satış miktarına göre hangi kategoriye ait olduğunu tahmin etmek için rastgele orman sınıflandırıcısı kullanılmıştır. Modelin doğruluğu hesaplanmış ve karışıklık matrisi görselleştirilmiştir.
6. Görüntü İşleme ile Ürün Görsellerinin Sınıflandırılması
Ürün görselleri kullanılarak bir görüntü sınıflandırma modeli oluşturulmuştur. Model, TensorFlow kullanılarak eğitilmiş ve doğrulama veri seti üzerindeki performansı değerlendirilmiştir.
Sonuç
Bu projede, satış tahmini ve sınıflandırma problemleri çözülmüş, ayrıca ürün görselleri ile görüntü sınıflandırma modeli geliştirilmiştir. Model performansları farklı metriklerle değerlendirilmiş ve görselleştirilmiştir.



