# gym-crowdedness-prediction
Kampüs Spor Salonu Yoğunluk Tahmin Projesi
Bu proje, "Crowdedness at the Campus Gym" veri setini kullanarak bir üniversite spor salonundaki anlık kişi sayısını (yoğunluğu) tahmin etmeyi amaçlayan bir makine öğrenimi projesidir.

Projede, en iyi tahmin modelini bulmak amacıyla scikit-learn kütüphanesi kullanılarak çeşitli regresyon algoritmaları (Linear Regression, Lasso, Ridge, K-Neighbors Regressor, Decision Tree ve RandomForestRegressor) eğitilmiş ve karşılaştırılmıştır.

Projenin Amacı
Projenin temel amacı, günün saati, sıcaklık ve tarih gibi özelliklere dayanarak spor salonundaki yoğunluğu (number_people) mümkün olan en doğru şekilde tahmin edebilen bir regresyon modeli geliştirmektir.

Bu amaçla, farklı algoritmaların performansları R2 (R-squared), Mean Absolute Error (MAE) ve Root Mean Squared Error (RMSE) metrikleri kullanılarak değerlendirilmiştir.

 Veri Seti Bilgileri
Veri Kaynağı: Kaggle - Crowdedness at the Campus Gym

Veri Seti Özellikleri (Temel Sütunlar):

number_people: Salondaki anlık kişi sayısı (Hedef Değişken - y)

date: (Tarih bilgisi - Özellik mühendisliği için kullanıldı)

temperature: Sıcaklık

is_holiday: Tatil günü olup olmadığı

day_of_week: Haftanın günü
