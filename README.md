# Akbank_DL_Project
## Malaria DataSets

Malaria hücre görüntüleri veri kümesi, tıbbi görüntü işleme ve yapay zeka araştırmalarında kullanılan bir veri kümesidir. Bu veri kümesi, hastalık sınıflandırma modeli eğitimi için kullanılabilir. Bu veri kümesi, plasmodium adı verilen protozoan parazitlerin neden olduğu malaria hastalığının neden olduğu kırmızı kan hücrelerindeki değişiklikleri gösteren hücre görüntüleri içerir.

Malaria hücre görüntüleri veri kümesi, Ulusal Sağlık Enstitüleri (NIH) tarafından sağlanmaktadır. Veri kümesi, 27.558 adet hücre görüntüsü içermektedir. Bu görüntülerin 13.779'u malaria parazitleri içerirken, diğerleri parazit içermez. Veri kümesi, iki sınıftan oluşur: Malaria olan ve olmayan.

Bu veri kümesi, sınıflandırma, nesne tespiti ve diğer makine öğrenimi görevleri için kullanılabilir. Veri kümesi, bilgisayarlı tomografi (BT) ve manyetik rezonans görüntüleme (MR) gibi diğer tıbbi görüntü işleme uygulamaları için de kullanılabilir. Bu veri kümesi, yapay zeka algoritmalarının tıbbi tanı ve tedavi süreçlerine katkıda bulunabileceği birçok farklı kullanım alanı sunar.
Malaria hücre görüntüleri, mikroskop kullanılarak çekilmiştir. Bu görüntüler, plasmodium adı verilen protozoan parazitlerin neden olduğu malaria hastalığının etkilerini gösteren kırmızı kan hücrelerinin ince kesitleridir.

Mikroskop kullanılarak çekilen bu görüntüler, tıbbi araştırmalar ve tanı için önemlidir. Bu görüntüler, hastalığın teşhis edilmesi ve tedavi edilmesinde yardımcı olabilir. Ayrıca, yapay zeka algoritmalarının tıbbi tanı ve tedavi süreçlerinde kullanılması için veri sağlamaktadır.

Malaria hücre görüntüleri veri kümesi, bu görüntülerin dijitalleştirilmesiyle oluşturulmuştur. Dijitalleştirme, görüntülerin sayısal veri formatına dönüştürülmesidir. Bu sayısal veriler, makine öğrenimi algoritmaları tarafından kullanılabilir hale getirilir.
Malaria hücre görüntüleri insan kanı hücrelerinin ince kesitleridir. Bu görüntüler, plasmodium adı verilen protozoan parazitlerin neden olduğu malaria hastalığının etkilerini gösteren kırmızı kan hücrelerinin mikroskop altında çekilmiş fotoğraflarıdır. Bu görüntüler, tıbbi araştırmalarda ve hastalığın teşhis ve tedavisinde kullanılır.

## Proje Hakkinda 
Bu proje, Convolutional Neural Network (CNN) kullanarak görüntü sınıflandırma işlemi gerçekleştirmektedir. TensorFlow/Keras kütüphaneleri ile derin öğrenme modeli oluşturulmuş ve eğitim süreci detaylandırılmıştır.

## Ozellikler 
- Veri ön işleme ve görselleştirme
- CNN modeli kurulumu (Conv2D, MaxPooling2D, Dense, Dropout katmanları)
- Model eğitimi, doğrulama ve test sonuçlarının analizi
- Eğitim sürecinde erken durdurma (EarlyStopping) ve doğruluk/başarı grafiklerinin çizilmesi

## Sonuç
Eğitim sonunda model, test verisi üzerinde belirli bir doğruluk oranı ile görüntüleri başarıyla sınıflandırmaktadır. Grafikler üzerinden modelin performansı izlenebilir.

## Link
Kaggle NoteBook : https://www.kaggle.com/code/muhammetalibegenjov/malaria-cell-images-i-cnn
Kaggle DataSets: https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria


