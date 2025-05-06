# Kelime Temsili ve Karşılaştırma Projesi

Bu proje, **Word2Vec** algoritması ile kelimelerin vektör temsillerini öğrenmeyi ve bu temsilleri **normal eğitim yöntemleriyle** karşılaştırmayı amaçlamaktadır. Projede, kelimelerin semantik ilişkilerini anlamak için iki farklı yöntemle sonuçlar elde edilmiştir:

1. **Word2Vec ile Kelime Temsilleri:** Kelimeler, Word2Vec algoritması ile vektörlere dönüştürülmüş ve kelimeler arasındaki semantik benzerlikler incelenmiştir.
2. **Normal Eğitim Yöntemi (Doğrudan Eğitim):** Veri seti doğrudan eğitim algoritmalarıyla işlenmiş ve sonuçlar karşılaştırılmıştır.

## Proje Özeti

Bu projede, aşağıdaki adımlar gerçekleştirilmiştir:

1. **Veri Seti:** Proje için özel olarak hazırlanmış bir veri seti kullanılmıştır. Bu veri seti, **[AG News](https://huggingface.co/datasets/sepidmnorozy/Turkish_sentiment/viewer?views%5B%5D=train)** veya benzeri metin verilerini içerebilir.
2. **Word2Vec Modeli:** `Word2Vec` algoritması kullanılarak kelimelerin vektör temsilleri öğrenilmiştir. Eğitim sürecinde, modelin çıktıları kelimeler arasındaki anlamlı ilişkileri yakalamayı amaçlamıştır.
3. **Normal Eğitim Modeli:** Veri seti doğrudan bir makine öğrenimi algoritmasıyla eğitilmiş ve farklı metotlarla karşılaştırma yapılmıştır.
4. **Karşılaştırma:** Word2Vec ve normal eğitim yöntemlerinin sonuçları karşılaştırılarak her iki yaklaşımın performansı analiz edilmiştir.

## Kullanılan Teknolojiler

- Python
- Gensim (Word2Vec)
- Scikit-learn
- Pandas
- Matplotlib / Seaborn (görselleştirme)
- Hugging Face Datasets

## Veri Seti

Projede kullanılan veri seti, metin verisi içeren **AG News** veri seti gibi yaygın metin kümelerinden alınmıştır. Veri setinin amacı, haber başlıklarını sınıflandırmak ve kelimeler arasındaki anlamlı ilişkileri öğrenmektir.

- [AG News Veri Seti Linki](https://huggingface.co/datasets/sepidmnorozy/Turkish_sentiment/viewer?views%5B%5D=train)
