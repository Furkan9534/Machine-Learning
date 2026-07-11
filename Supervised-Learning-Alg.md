# Supervised Learning (Denetimli Öğrenme)

Denetimli öğrenme (Supervised Learning), bir modelin etiketlenmiş verilerden öğrendiği bir makine öğrenmesi türüdür.
 Bu yöntemde her girdinin doğru bir çıktısı vardır. Model, yaptığı tahminleri gerçek sonuçlarla karşılaştırır ve doğruluğunu 
 artırmak için zaman içinde kendini geliştirir.

### Kısacası : 
Supervised Learning = Etiketli verilerle öğrenme + tahmin yapma + hatalardan kendini düzeltme süreci.




<img src="/pictures/supervisedLearning.jpeg" alt="Supervised Learning" width="800">



## Başlıca Özellikler:

 Her girdinin bilinen bir çıktısı vardır. Tahmin hatalarını azaltmak için kendini ayarlar. Yeni veriler üzerinde doğru tahminler yapar.
Örneğin, eğitildiği verilerden yola çıkarak el yazısı rakamları tanır.




### Denetimli Öğrenme Türleri
Denetimli öğrenme, başlıca iki tür probleme uygulanabilir:

Sınıflandırma: Çıktının kategorik bir değişken olduğu durumlar (örneğin, spam olan ve olmayan e-postalar, evet/hayır).
Regresyon: Çıktının sürekli bir değişken olduğu durumlar (örneğin, konut fiyatlarının veya hisse senedi fiyatlarının tahmin edilmesi).



### Denetimli Makine Öğreniminin İşleyişi
Denetimli makine öğreniminin işleyişi şu temel adımları izler:


1. Etiketli Veri Toplayın
2. Veri Setini Bölün
3. Modeli Eğitin
4. Modeli Doğrulayın ve Test Edin
5. Yeni Veriler Üzerinde Dağıtım ve Tahmin

### Denetimli Makine Öğrenmesi Algoritmaları
Denetimli öğrenme, etiketli verilere dayanarak çıktıları tahmin etmek için kullanılan çeşitli algoritma türlerini kapsar. Her bir algoritma, tahmin veya sınıflandırma gibi belirli görevler için tasarlanmıştır.

Doğrusal Regresyon (Linear Regression): Sürekli değerleri (örneğin fiyat, sıcaklık) tahmin etmek için kullanılır. Basit ve yaygın olarak kullanılan bir yöntemdir.
Lojistik Regresyon (Logistic Regression): İkili (binary) bir çıktı değişkenini tahmin etmek için kullanılan, denetimli öğrenme tabanlı bir sınıflandırma algoritmasıdır.
Karar Ağaçları (Decision Trees): Her bir düğümün bir kararı, her bir yaprağın ise bir sonucu temsil ettiği ağaç benzeri bir yapı kullanır.
Rastgele Ormanlar (Random Forests): Doğruluğu artırmak ve aşırı öğrenmeyi (overfitting) azaltmak amacıyla birden fazla karar ağacını birleştirir.
Destek Vektör Makineleri (SVM): Verileri bir sınır (hiper düzlem) kullanarak sınıflara ayırır. Destek vektörleri, bu sınırın tanımlanmasına yardımcı olur.
K-En Yakın Komşu (K-Nearest Neighbors): En yakın veri noktalarına dayanarak tahmin yürütür. Sonuçlar, k değerine ve mesafe ölçütüne bağlıdır.
Gradyan Artırma (Gradient Boosting): Önceki modellerin hatalarını düzelterek modelleri adım adım oluşturur ve böylece güçlü bir model ortaya çıkarır.
Naive Bayes Algoritması: Özelliklerin birbirinden bağımsız olduğunu varsayarak, olasılık ve Bayes Teoremi'ne dayalı olarak çalışır.


Supervised-Learning