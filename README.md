# 🧠 Oracle Machine Learning with PL/SQL  
### 🧪 Diabetes Prediction Model – BDA Project #2  
**2nd Cycle Software Engineering (2CS SIL)**  
**2024–2025**  
**Contributors**: Mahdia Toubal, Dina Keddour, Louni Imene, Guitoun Djihen  

---

## 📘 Project Overview

This project demonstrates how to build, train, and evaluate a **classification model for diabetes prediction** using **Oracle Machine Learning (OML)** and **PL/SQL**, directly inside the Oracle Autonomous Database environment.

By leveraging in-database processing, the solution avoids data movement, ensures performance, and aligns well with Oracle-based systems.

---

## ⚙️ Environment Setup

- **Platform**: Oracle Cloud Free Tier  
- **Database**: Autonomous Data Warehouse (ADW)  
- **Resources**: 2 OCPUs, 1TB storage  
- **Tools Used**:  
  - OML Notebooks  
  - Oracle SQL Developer (for PL/SQL scripting)  

---

## 🗃️ Data Preparation

1. **Creating the Diabetes Table**  
   Designed a structured table for storing patient features and diabetes outcomes (`1` = diabetic, `0` = non-diabetic).

2. **Inserting Sample Data**  
   Populated the table with representative medical records.

3. **Splitting into Training and Test Sets**  
   Used an 80/20 split for training and evaluation purposes.

---

## 🏗️ Model Creation (PL/SQL + OML)

1. **Dropping Existing Models**  
   Used anonymous PL/SQL blocks to remove any pre-existing model named `DIABETES_MODEL`.

2. **Defining Model Parameters**  
   Created a model settings table using SQL, specifying the `ALGO_DECISION_TREE` algorithm for classification.

3. **Training the Model**  
   Leveraged the `DBMS_DATA_MINING.CREATE_MODEL` procedure to build the model directly within the database.

---

## 📈 Model Evaluation

1. **Generating Predictions**  
   Applied the `PREDICTION` SQL function to test data and compared results against actual labels.

2. **Accuracy Calculation**  
   Evaluated prediction accuracy purely through SQL queries, without external tools.

---

## ✅ Conclusion

This project showcases how **PL/SQL and Oracle Machine Learning** can be effectively used for:

- Data preprocessing  
- Model training  
- Prediction and evaluation  

All operations are executed **within the Oracle database**, improving speed, reducing risk, and simplifying integration.

---

## 🤖 AI Tools Utilization

AI-assisted tools were used to:

- Understand OML and PL/SQL concepts  
- Write and debug code  
- Resolve Oracle errors  
- Structure and refine the report  

---

## 📧 Contact

- Mahdia Toubal — [km_toubal@esi.dz](mailto:km_toubal@esi.dz)  
- Dina Keddour — [kd_keddour@esi.dz](mailto:kd_keddour@esi.dz)  
- Louni Imene — [li_louni@esi.dz](mailto:li_louni@esi.dz)  
- Guitoun Djihen — [d_guitoun@esi.dz](mailto:d_guitoun@esi.dz)

---

> _“A modern use of PL/SQL in the era of cloud-based AI services.”_
