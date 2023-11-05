# Makine Öğrenme Projesi Sonuçları

Bu proje, Random Forest Regressor kullanılarak gerçekleştirilen bir makine öğrenme çalışmasını içermektedir. Aşağıda, projenin sonuçları ve önemli bulguları sunulmaktadır.
## En İyi Model

Proje sonuçlarına göre, Random Forest Regressor modelinin en iyi hiperparametreleri şunlardır:

    Rastgele Durum (Random State): 42
    Ağaç Sayısı (n_estimators): 300
    Minimum Örnekleme Bölünmesi (min_samples_split): 5
    Minimum Yaprak Örneği (min_samples_leaf): 2
    Maksimum Özellik Sayısı (max_features): 'auto'
    Maksimum Derinlik (max_depth): 30

## Performans Değerlendirmesi

Bu modelin performansı, negatif ortalama kare hata (neg_mean_squared_error) skorunu kullanarak ölçülmüştür:
## Eğitim Verileri Üzerinde Performans:

    Negatif Ortalama Kare Hata (neg_mean_squared_error): -231958133.13
    Kök Ortalama Kare Hata (RMSE): 15230.17

## Test Verileri Üzerinde Performans:

    Negatif Ortalama Kare Hata (neg_mean_squared_error): -4754792943.75
    Kök Ortalama Kare Hata (RMSE): 68955.01

Ayrıca, modelin test verileri üzerinde ortalama hata (Mean Absolute Error) değeri 8284.62 ve ortalama hata karesi (Mean Squared Error) değeri 4754792943.75 olarak hesaplanmıştır.

# Sonuçlar ve Açıklamalar

Elde edilen sonuçlar, modelin eğitim verileri üzerinde oldukça iyi performans gösterdiğini göstermektedir. Ancak, test verileri üzerinde negatif ortalama kare hata (neg_mean_squared_error) değeri oldukça yüksektir ve bu, modelin aşırı uydurma (overfitting) sorunu yaşadığını gösterir.

Aşırı uydurmanın önlenmesi ve modelin daha iyi genelleme yapabilmesi için hiperparametrelerin daha dikkatli bir şekilde ayarlanması gerekebilir. 
