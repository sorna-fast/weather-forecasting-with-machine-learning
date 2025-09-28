# ***Description in English***

# Weather Forecasting with Machine Learning

## Introduction
This project focuses on weather forecasting using machine learning techniques. It includes data preprocessing, model training, and evaluation to predict weather parameters such as temperature and humidity.

## Features
- Weather dataset processing and visualization.
- Implementation of multiple machine learning models.
- Performance evaluation of models using standard metrics.
- Notebooks available in both English and Persian.

## Installation
### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Required dependencies from `requirements.txt`

### Steps to Install
1. Clone the repository:
   ```sh
   git clone https://github.com/sorna-fast/Weather-forecasting-with-machine-learning.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Weather-forecasting-with-machine-learning
   ```
3. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: `venv\Scripts\activate`
   ```
4. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Open Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
2. Run one of the available notebooks:
   - `Weather_forecasting_with_machine_learning_in_English.ipynb`
   - `Weather_forecasting_with_machine_learning_in_Persian.ipynb`

## Project Structure
```
Weather-forecasting-with-machine-learning/
│── dataset.csv                # Weather dataset
│── Weather_forecasting_with_machine_learning_in_English.ipynb  # English notebook
│── Weather_forecasting_with_machine_learning_in_Persian.ipynb  # Persian notebook
│── requirements.txt           # Project dependencies
│── README.md                  # Project documentation
```

## Models Used
- **Linear Regression**
- **Random Forest Regressor**
- **Gradient Boosting**

## Results & Performance
The models are evaluated using **Mean Absolute Error (MAE)** and **Root Mean Square Error (RMSE)**. The best-performing model results are documented within the notebooks.
## Optimizing the best learning model
**Gradient Boosting**
Used for optimization via (Random Search) via `scikit-learn` library.
Best parameters: {'subsample': 0.7, 'n_estimators': 100, 'min_samples_split': 5, 'min_samples_leaf': 6, 'max_features': None, 'max_depth': 4, 'loss': 'huber', 'learning_rate': 0.05}
Test R²: 0.8604
train r2: 0.8658



## License
This project is licensed under the **MIT License**.

## Contact
For inquiries, reach out to:
   Email:(masudpythongit@gmail.com)
🔗 GitHub: [sorna-fast](https://github.com/sorna-fast)

____________________________________________________________________________________________________________


# ***توضیحات فارسی***

# پیش‌بینی آب‌وهوا با یادگیری ماشین  

## مقدمه  
این پروژه بر روی پیش‌بینی آب‌وهوا با استفاده از تکنیک‌های یادگیری ماشین تمرکز دارد. این پروژه شامل مراحل پیش‌پردازش داده، آموزش مدل و ارزیابی برای پیش‌بینی پارامترهای آب‌وهوایی مانند دما و رطوبت می‌شود.  

## ویژگی‌ها  
- پردازش و تجسم داده‌های آب‌وهوایی  
- پیاده‌سازی چندین مدل یادگیری ماشین  
- ارزیابی عملکرد مدل‌ها با معیارهای استاندارد  
- ارائه نوتبوک‌های آموزشی به دو زبان **انگلیسی** و **فارسی**  

## نصب و راه‌اندازی  
### پیش‌نیازها  
- پایتون ۳.۸ یا بالاتر  
- Jupyter Notebook  
- نصب کتابخانه‌های مورد نیاز از فایل `requirements.txt`  

### مراحل نصب  
۱. کلون کردن ریپوزیتوری:  
   ```sh  
   git clone https://github.com/sorna-fast/Weather-forecasting-with-machine-learning.git  
   ```  

۲. ورود به پوشه پروژه:  
   ```sh  
   cd Weather-forecasting-with-machine-learning  
   ```  

۳. ایجاد و فعال‌سازی محیط مجازی:  
   ```sh  
   python -m venv venv  
   source venv/bin/activate  # در ویندوز: `venv\Scripts\activate`  
   ```  

۴. نصب کتابخانه‌های مورد نیاز:  
   ```sh  
   pip install -r requirements.txt  
   ```  

## نحوه استفاده  
۱. اجرای Jupyter Notebook:  
   ```sh  
   jupyter notebook  
   ```  

۲. اجرای یکی از نوتبوک‌های موجود:  
   - `Weather_forecasting_with_machine_learning_in_English.ipynb`  
   - `Weather_forecasting_with_machine_learning_in_Persian.ipynb`  

## ساختار پروژه  
```
Weather-forecasting-with-machine-learning/
│── dataset.csv                # دیتاست آب‌وهوایی  
│── Weather_forecasting_with_machine_learning_in_English.ipynb  # نوتبوک انگلیسی  
│── Weather_forecasting_with_machine_learning_in_Persian.ipynb  # نوتبوک فارسی  
│── requirements.txt           # کتابخانه‌های مورد نیاز  
│── README.md                  # مستندات پروژه  
```  

## مدل‌های استفاده شده  
- **رگرسیون خطی (Linear Regression)**  
- **رگرسیون جنگل تصادفی (Random Forest Regressor)**  
- **گرادیان بوستینگ (Gradient Boosting)**  

## نتایج و عملکرد  
مدل‌ها با استفاده از **میانگین خطای مطلق (MAE)** و **ریشه میانگین مربعات خطا (RMSE)** ارزیابی شده‌اند. نتایج بهترین مدل در داخل نوتبوک‌ها مستندسازی شده است.

## بهینه سازی بهترین مدل یادگیری
**Gradient Boosting**
برای بهینه سازی از طریق   (Random Search) از طریق کتابخانه `scikit-learn` استفاده شده‌اند.  
بهترین پارامترها: {'subsample': 0.7, 'n_estimators': 100, 'min_samples_split': 5, 'min_samples_leaf': 6, 'max_features': None, 'max_depth': 4, 'loss': 'huber', 'learning_rate': 0.05}
Test R²: 0.8604
train r2: 0.8658


## مجوز  
این پروژه تحت **مجوز MIT** منتشر شده است.  

## ارتباط با توسعه‌دهنده  
    Email:(masudpythongit@gmail.com)(masudpythongit@gmail.com)
🔗 حساب گیتهاب: [sorna-fast](https://github.com/sorna-fast)
