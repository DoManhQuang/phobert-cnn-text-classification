# phobert-text-classification-with-cnn

Bộ dữ liệu sử dụng "[A Large-scale Vietnamese News Text Classification Corpus](https://github.com/duyvuleo/VNTC)"

---
## **Project**
* quick_start_data_NLP_Pho_Bert.ipynb : Xử lý dữ liệu
* text_classification_with_CNN.ipynb : Huấn luyện mô hình
---

## Train/Test: 80/20

### **Classification Report**

|            |precision  |  recall | f1-score |  support|
|------------|-----------|---------|----------|---------|
|Class 0     |  0.75     | 0.77    |  0.76    |   200	|
|Class 1     |  0.82     | 0.89    |  0.86    |   200	|
|Class 2     |  0.87     | 0.79    |  0.83    |   200	|
|Class 3     |  0.85     | 0.83    |  0.84    |   200|
|Class 4     |  0.91     | 0.87    |  0.89    |   200|
|Class 5     |  0.91     | 0.87    |  0.89    |   200|
|Class 6     |  0.85     | 0.88    |  0.86    |   200|
|Class 7     |  0.99     | 0.96    |  0.97    |   200|
|Class 8     |  0.90     | 0.95    | 0.92     |  200|
|Class 9     |  0.90     | 0.92    |  0.91    |   200|
|accuracy    |                     | 0.87     |  2000|
|macro avg   |  0.87     | 0.87    |  0.87    |   2000|
|weighted avg|  0.87     | 0.87    |  0.87	  |   2000|  

---

### **Confusion Matrix**
![img1](https://raw.githubusercontent.com/DoManhQuang/phobert-text-classification-with-cnn/main/Confusion_matrix_train-test_80-20_10_class.png)
---

## ROC KFold = 10
### **ROC best - Classification Report**

|              |precision| recall   |  f1-score| support|
|--------------|---------|----------|----------|-----|
|Class 0       |0.72     | 0.84     |   0.78   |  100|
|Class 1       |0.88     | 0.91     | 0.90     |  100|
|Class 2       |0.93     | 0.90     | 0.91     |  100|
|Class 3       |0.85     | 0.86     | 0.86     |  100|
|Class 4       |0.99     | 0.82     | 0.90     |  100|
|Class 5       |0.97     | 0.91     | 0.94     |  100|
|Class 6       |0.88     | 0.92     | 0.90     |  100|
|Class 7       |0.95     | 0.97     | 0.96     |  100|
|Class 8       |0.95     | 0.93     | 0.94     |  100|
|Class 9       |0.92     | 0.93     | 0.93     |  100|
|accuracy      |         |          | 0.90     | 1000|
|macro avg     |0.90     | 0.90     | 0.90     | 1000|
|weighted avg  |0.90     | 0.90     | 0.90     | 1000|

### **Confusion Matrix**
![img1](https://raw.githubusercontent.com/DoManhQuang/phobert-text-classification-with-cnn/main/bestROC_10_class.png)

### **ROC score**

|STT    | Score |
|-------|-------|
|ROC 1  | 0.9910|
|ROC 2  | 0.9933|
|ROC 3  | 0.9909|
|ROC 4  | 0.9920|
|ROC 5  | 0.9908|
|ROC 6  | 0.9912|
|ROC 7  | 0.9904|
|ROC 8  | 0.9927|
|ROC 9  | 0.9896|
|ROC 10 | 0.9941|

---

