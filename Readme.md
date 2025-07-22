# Öğrenci Başarı Tahmini – Linear Regression ile Modelleme

Bu projede, öğrencilerin çeşitli demografik ve akademik özelliklerine bakarak not başarılarını tahmin etmek için **Linear Regression** modelini kullandım. Amacım, öğrencilerin gelecekteki performanslarını veriye dayalı olarak öngörmekti.

---

## 📁 Veri Seti

Kullandığım veri seti, Kaggle üzerinde yayında olan öğrenci başarı verilerini içeriyor.   
📌 [Student Habits and Academic Performance Dataset]([https://www.kaggle.com/code/talhayldz/student-performance-modeling-87](https://www.kaggle.com/datasets/aryan208/student-habits-and-academic-performance-dataset))


---

## ⚙️ Kullandığım Teknolojiler

- Python 3
- pandas, numpy
- scikit-learn
- seaborn, matplotlib

---

## 🧪 Yaptığım Çalışmalar

1. **Veri İncelemesi ve Temizliği**  
   - Eksik veya hatalı verileri kontrol ettim.  
   - Kategorik sütunları `Label Encoding` ile sayısal forma dönüştürdüm.

2. **Keşifsel Veri Analizi (EDA)**  
   - Özelliklerin dağılımını ve hedef değişkenle olan ilişkisini görselleştirdim.  
   - Korelasyon matrisi oluşturarak en etkili değişkenleri belirledim.

3. **Modelleme**  
   - Tahmin modeli olarak **Linear Regression** algoritmasını kullandım.  
   - Veriyi eğitim ve test olmak üzere `train_test_split` ile ayırdım.  
   - Modeli eğittikten sonra tahmin sonuçlarını inceledim.

4. **Model Değerlendirme**  
   - Aşağıdaki regresyon metriklerini kullandım:
     - R² (R-kare) skoru
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)

---
