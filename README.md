# Weather Classification and Analysis Using Machine Learning  

This project aims to classify and analyze weather conditions using various machine learning models, including Random Forest, Logistic Regression, and Decision Trees. The dataset includes features such as temperature, humidity, wind speed, and cloud cover, which are used to predict different weather types.

---

## **Features**  
The dataset contains the following columns:  
- **Temperature**: Recorded in Celsius.  
- **Humidity**: Percentage of air moisture.  
- **Wind Speed**: Speed of wind in km/h.  
- **Precipitation (%)**: Probability of rain.  
- **Cloud Cover**: Weather description (e.g., clear, overcast).  
- **Atmospheric Pressure**: Measured in hPa.  
- **UV Index**: Intensity of ultraviolet radiation.  
- **Season**: Season when data was recorded (e.g., Winter, Spring).  
- **Visibility (km)**: Distance visible in kilometers.  
- **Location**: Geographical classification (e.g., inland, coastal).  
- **Weather Type**: Target label (e.g., Sunny, Rainy, Cloudy).  

---

## **Machine Learning Models and Results**  

### **Random Forest Classifier**  
- **Accuracy**: 91.16%  
- Best performing model with high precision and recall across all weather types.  

### **Logistic Regression**  
- **Accuracy**: 84.97%  
- Shows moderate performance but slightly lower recall for some classes.  

### **Decision Tree Classifier**  
- **Accuracy**: 90.08%  
- Close in performance to Random Forest but less robust.  

### **Entropy Decision Tree**  
- **Accuracy**: 90.58%  
- Improved slightly over the standard Decision Tree model.  

---

## **Classification Reports**  

### Random Forest Classification Report:
```plaintext
               precision    recall  f1-score   support

           0       0.87      0.90      0.88       955
           1       0.90      0.92      0.91       982
           2       0.93      0.93      0.93      1033
           3       0.94      0.90      0.92       990

    accuracy                           0.91      3960
   macro avg       0.91      0.91      0.91      3960
weighted avg       0.91      0.91      0.91      3960
