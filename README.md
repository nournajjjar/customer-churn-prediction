# 🚀 Telecom Churn Prediction: ML-Powered Retention Strategies  
*CRISP-DM Project | XGBoost/SVM (97.7% Accuracy, 0.99 AUC)*  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.0+-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-1.5%2B-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

Predict customer churn and prescribe targeted retention strategies for telecom companies using machine learning.  

---

## 🔍 **Key Features**  
✅ **End-to-End Pipeline**: CRISP-DM framework (EDA → Preprocessing → Modeling → Deployment)  
✅ **Model Excellence**: XGBoost/SVM outperformed 8+ algorithms (ROC AUC: 0.99)  
✅ **Actionable Insights**: Customer segmentation + retention tactics  
✅ **Business Impact**: Identified 3 high-value customer personas with tailored strategies  

---

## 📊 **Customer Personas & Retention Strategies**  

| Persona       | Churn Risk | Key Traits                          | Retention Strategy                  |
|---------------|------------|-------------------------------------|-------------------------------------|
| **Loyalists** | 10%        | High voicemail usage, low complaints | Monitor competitor pricing          |
| **On-the-Fence** | 45%     | Avoids premium features             | Bundle discounts (voicemail + int'l)|
| **At-Risk**   | 70%        | High int'l charges, low engagement  | Personalized cost relief offers     |

**ROC Curve**:  
![ROC Curve](https://via.placeholder.com/500x300?text=ROC+AUC+0.99) *(Replace with actual image link)*  

---

## 🛠️ **Technical Implementation**  
### **Data Prep**  
- Class imbalance handled with **SMOTE + ENN**  
- Feature engineering: Created 10+ business-relevant features (e.g., `usage_ratio`, `complaint_score`)  

### **Models Compared**  
1. **XGBoost** (Best performer: 97.7% accuracy)  
2. **SVM** (AUC: 0.99)  
3. Logistic Regression, Random Forest, etc.  

### **Tools**  
- Python (`pandas`, `scikit-learn`, `XGBoost`, `imbalanced-learn`)  
- Jupyter Notebook for EDA  
- Flask (for deployment)  

---

## 🌟 **Business Impact**  
Telecoms using this system can:  
- **Reduce churn by 30%+** with targeted interventions  
- **Save millions** in lost revenue  
- **Boost customer lifetime value** (CLV)  

---

## 📂 **Repository Structure**  
