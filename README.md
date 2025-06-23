# 📊 Customer Churn Prediction / Müşteri Terk Etme Tahmini

📝 Project Description / Proje Açıklaması

**EN:**  
This project aims to predict whether a customer will churn (leave the company) using the Telco Customer Churn dataset. It includes exploratory data analysis (EDA), data preprocessing, machine learning models, and model evaluation with interpretation.

**TR:**  
Bu projede Telco müşteri verileri kullanılarak bir müşterinin şirketten ayrılıp ayrılmayacağı tahmin edilmeye çalışılmıştır. Projede veri analizi, veri temizleme, makine öğrenmesi modelleri ve model performans değerlendirmesi yer almaktadır.

---

## 📁 Dataset / Veri Seti

- **Name / İsim**: Telco Customer Churn  
- **Source / Kaynak**: [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- **Rows / Satır**: 7043  
- **Target Variable / Hedef Değişken**: `Churn` (Yes/No)

---

## ⚙️ Technologies & Tools / Kullanılan Teknolojiler

- Python (pandas, numpy, seaborn, matplotlib)
- scikit-learn
- Jupyter Notebook / Python Script
- RandomForestClassifier, LogisticRegression

---

## 🔍 Project Steps / Proje Adımları

1. **Data Loading / Veri Yükleme**
2. **Data Cleaning / Veri Temizleme**
   - Missing values handled
   - Data types converted (e.g. TotalCharges → float)
3. **Exploratory Data Analysis / Keşifsel Veri Analizi**
   - Target variable distribution
   - Feature distributions
   - Correlations
4. **Data Preprocessing / Ön İşleme**
   - One-hot encoding
   - Train-test split
5. **Modeling / Modelleme**
   - Logistic Regression
   - Random Forest
6. **Evaluation / Değerlendirme**
   - Accuracy, classification report, confusion matrix
7. **Feature Importance / Özellik Önem Skorları**

---
## 📊 Visualizations / Görselleştirmeler

**EN:**  
During the exploratory data analysis (EDA), several visualizations were created to better understand the dataset and feature relationships:

- **Churn Distribution:** A count plot visualizing the number of customers who churned versus those who stayed.
- **Numerical Feature Distributions:** Histograms with Kernel Density Estimation (KDE) for numerical variables such as tenure, MonthlyCharges, and TotalCharges.
- **Categorical Feature Analysis:** Count plots for categorical features like Contract type, Payment Method, Internet Service, and more.
- **Feature Importance:** A bar plot showing the top 10 most important features influencing customer churn based on the Random Forest model.

**TR:**  
Keşifsel veri analizi (EDA) sırasında, veri setini ve değişkenler arasındaki ilişkileri daha iyi anlamak için çeşitli görselleştirmeler yapılmıştır:

- **Churn Dağılımı:** Müşteri terk edenler ve kalanların sayısını gösteren sütun grafiği.
- **Sayısal Değişken Dağılımları:** tenure, MonthlyCharges ve TotalCharges gibi sayısal değişkenlerin histogram ve KDE grafikleri.
- **Kategorik Değişken Analizi:** Sözleşme tipi, ödeme yöntemi, internet servisi gibi kategorik değişkenlerin sayısal dağılımlarını gösteren sütun grafikleri.
- **Özellik Önem Grafiği:** Random Forest modeline göre churn üzerinde en etkili 10 özelliği gösteren çubuk grafik.

---


## ✅ Model Results / Model Sonuçları

| Model               | Accuracy / Doğruluk Oranı | Precision (Churn) | Recall (Churn) | F1-score (Churn) |
|---------------------|---------------------------|-------------------|----------------|------------------|
| Logistic Regression  | 0.80                      | 0.64              | 0.57           | 0.60             |
| Random Forest       | 0.79                      | 0.63              | 0.52           | 0.57             |

 ---
