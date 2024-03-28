# MedicalChargesPrediction

**Project Description:**

Embarking on a data-driven journey, I employed PySpark to predict medical charges based on various influencing factors. Leveraging regression analysis techniques, I sought to develop models capable of estimating charges, crucial for healthcare planning and resource allocation.

**Objective:**

The primary objective of this project was to utilize PySpark for regression analysis to predict medical charges accurately. By exploring different regression algorithms, including Linear Regression, Decision Trees, Random Forest, and Gradient Boosting, I aimed to construct models that closely approximate the actual charges based on available data.

**Methodology:**
1. **Data Acquisition and Preprocessing:**
   - The dataset was obtauned from kaggle. It contained pertinent information including age, BMI, smoking status, region, etc., with charges being the target variable.
   - Using PySpark's DataFrame API, I preprocessed the data, handling missing values, encoding categorical variables, and ensuring feature scalability.

2. **Model Development:**
   - Employing PySpark's MLlib library, I implemented various regression algorithms including Linear Regression, Decision Trees, Random Forest, and Gradient Boosting.
   - Each algorithm was trained using 70-80% of the data, with the remaining reserved for validation.

3. **Model Evaluation:**
   - Model performance was assessed using key regression metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared.
   - By comparing the performance of different models, I was able to identify the most accurate predictor of medical charges.

4. **Deployment and Prediction:**
   - Upon selecting the best-performing model, I deployed it to make predictions on new data.
   - PySpark's deployment capabilities ensured scalability and efficiency for real-time charge estimation.

**Expected Outcome:**
Through rigorous regression analysis in PySpark, I anticipated developing models that closely approximate medical charges based on input features. By comparing the performance of various regression algorithms, I aimed to identify the most accurate predictor, aiding in better understanding and management of healthcare costs.

**Conclusion:**
By leveraging PySpark's capabilities for regression analysis, this project aimed to contribute to the field of healthcare analytics by providing accurate predictions of medical charges. The insights gained from this endeavor are valuable for healthcare administrators, insurers, and policymakers in making informed decisions regarding resource allocation and cost management.
