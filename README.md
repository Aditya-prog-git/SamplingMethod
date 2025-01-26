# Sampling Methods Evaluation

This repository presents a comparative analysis of different sampling methods across various machine learning models. The evaluation focuses on the accuracy achieved by each sampling method for the given models.

---

## 📊 Best Sampling Methods Based on Accuracy

| **Sampling Method**        | **Random Forest** | **Logistic Regression**  | **Decision Tree** | **KNN** | **SVM**  |
|----------------------------|-------------------|--------------------------|-------------------|---------|----------|
| **Random Sampling**        | 0.9902            | 0.9020                   | 0.9706            | 0.8170  | 0.6569   |
| **Stratified Sampling**    | 0.9935            | 0.9052                   | 0.9641            | 0.8268  | 0.6536   |
| **Cluster Sampling**       | 0.9935            | 0.9052                   | 0.9641            | 0.8268  | 0.6536   |
| **Systematic Sampling**    | 0.9935            | 0.9052                   | 0.9641            | 0.8268  | 0.6536   |
| **Bootstrap Sampling**     | 0.9935            | 0.9183                   | 0.9608            | 0.8333  | 0.6830   |

---

### 🏆 Best Methods Per Model
- ✅ **Random Forest**: **Random Sampling** with an accuracy of **0.9902**
- ✅ **Logistic Regression**: **Bootstrap Sampling** with an accuracy of **0.9183**
- ✅ **Decision Tree**: **Random Sampling** with an accuracy of **0.9706**
- ✅ **KNN**: **Bootstrap Sampling** with an accuracy of **0.8333**
- ✅ **SVM**: **Bootstrap Sampling** with an accuracy of **0.6830**

---

## 🧪 Evaluation Results of Various Techniques

### 🔄 RandomOverSampler
- **Random Forest**: 1.0000
- **Logistic Regression**: 0.9192
- **Decision Tree**: 0.9978
- **KNN**: 0.9847
- **SVM**: 0.6856

### 🔻 RandomUnderSampler
- **Random Forest**: 0.5000
- **Logistic Regression**: 0.8333
- **Decision Tree**: 0.8333
- **KNN**: 0.6667
- **SVM**: 0.1667

### ⚖️ ProportionalSampling
- **Random Forest**: 0.9892
- **Logistic Regression**: 0.9785
- **Decision Tree**: 0.9785
- **KNN**: 0.9892
- **SVM**: 0.9892

### 📚 StratifiedSampling
- **Random Forest**: 0.9828
- **Logistic Regression**: 0.9828
- **Decision Tree**: 0.9828
- **KNN**: 0.9828
- **SVM**: 0.9828

### 🔍 NearMiss
- **Random Forest**: 0.1667
- **Logistic Regression**: 0.5000
- **Decision Tree**: 0.1667
- **KNN**: 0.8333
- **SVM**: 0.1667

---

## 🚀 Key Insights
> **Highlights**:
> - **RandomOverSampler** achieves perfect accuracy with Random Forest.
> - **ProportionalSampling** provides consistently high accuracy across all models, especially SVM.
> - **NearMiss** shows limited effectiveness for models like SVM and Random Forest.

---

## 💡 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Aditya-prog-git/SamplingMethod
