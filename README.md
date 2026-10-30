# Araştırma Yöntem Ve Teknikleri
# 📊 Kahve/Enerji İçeceği Tüketimi ile Uyku Kalitesi ve Odaklanma Arasındaki İlişki

## 📌 Proje Özeti ve Problem Durumu
Üniversite öğrencileri ve genç yetişkinler arasında kafein içeren içeceklerin (kahve ve enerji içecekleri) kullanımı oldukça yaygındır[cite: 219]. Ancak yüksek kafein tüketiminin gecelik uyku kalitesini düşürdüğü ve gün içindeki odaklanma/konsantrasyon sürelerini etkilediği düşünülmektedir[cite: 219]. Bu araştırmada, kafein tüketimi ile uyku kalitesi ve odaklanma seviyeleri arasındaki ilişki açık veri seti kullanılarak nicel yöntemlerle incelenecektir[cite: 219].

## 📂 Veri Seti Bilgileri
* **Veri Seti Adı:** Global Coffee Health Dataset[cite: 221]
* **Veri Seti Bağlantısı:** [Kaggle - Global Coffee Health Dataset](https://www.kaggle.com/datasets/laksikatharmalingam/global-coffee-health-dataset)[cite: 221]
* **Veri Kaynağı:** Katılımcılardan toplanmış ikincil veridir (Gerçek veridir)[cite: 219, 221].
* **Lisans:** CC BY 4.0 / Public Domain[cite: 98]
* **İncelenen Değişkenler:**
  * `Daily Coffee Intake / Caffeine Levels` (Kafein/Kahve Tüketimi)[cite: 221]
  * `Sleep Duration and Quality` (Uyku Süresi ve Kalitesi)[cite: 221]
  * `Focus / Productivity Metrics` (Odaklanma/Verimlilik Göstergeleri)[cite: 221]

## 🎯 Araştırma Sorusu ve Hipotezler
* **Temel Araştırma Sorusu:** Günlük kafein (kahve/enerji içeceği) tüketim miktarı ile uyku kalitesi ve odaklanma düzeyi arasında istatistiksel olarak anlamlı bir ilişki var mıdır?[cite: 219]
* **Hipotezler:**
  * **H1:** Günlük kafein tüketim miktarı arttıkça uyku kalitesi puanı anlamlı şekilde düşer ($r < 0, p < 0.05$)[cite: 14].
  * **H2:** Günlük kafein tüketim miktarı ile odaklanma düzeyi puanı arasında istatistiksel olarak anlamlı bir ilişki vardır ($p < 0.05$)[cite: 14].
  * **H0 (Sıfır Hipotezi):** Günlük kafein tüketimi ile uyku kalitesi ve odaklanma düzeyi arasında anlamlı bir ilişki yoktur ($p \ge 0.05$)[cite: 14].

## ⚙️ Yöntem ve Analiz
* **Analiz Yöntemi:** Python (Google Colab) ortamında normallik testleri sonrasında **Pearson** veya **Spearman Korelasyon Analizi** uygulanacaktır.
* **Kontrol Değişkenleri:** Ekran süresi, yaş ve stres düzeyi karıştırıcı değişken olarak dikkate alınacaktır[cite: 10].
* **Metodolojik Not:** Korelasyon analizi neden-sonuç ilişkisi (causality) göstermez; değişkenlerin birlikte değişim eğilimini inceler[cite: 10].

## 👤 Araştırmacı
* **[Sefa Yıldırım]:** Araştırma Tasarımı, Veri Analizi ve Raporlama
