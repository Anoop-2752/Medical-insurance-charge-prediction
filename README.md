# Medical-insurance-charge-prediction.

# Project Overview

This project focuses on analyzing a data related to medical insurance costs using Python. The dataset contains various features such as age, sex, BMI, number of children, smoking status, region, and insurance charges. The goal of this project is to perform an exploratory data analysis (EDA) to understand the dataset, identify patterns, and we use  **FastAPI-based web application** that predicts **medical insurance charges** based on user-provided details like age, BMI, smoking status, and more.

![Image](https://github.com/user-attachments/assets/f34924db-2c2b-44c6-8fae-6337c21c1126)



## About Dataset
The dataset used in this project is stored in a CSV file named insurance.csv. It contains the following columns:

- age: Age of the primary beneficiary.
- sex: Gender of the primary beneficiary (male/female).
- bmi: Body Mass Index (BMI) of the primary beneficiary.
- children: Number of children covered by the insurance.
- smoker: Smoking status of the primary beneficiary (yes/no).
- region: Region where the beneficiary resides (northeast, southeast, southwest, northwest).
- charges: Individual medical costs billed by the insurance.

## 🚀 Features
- Uses **Machine Learning** (pre-trained `model.pkl`) to predict charges.
- Provides a **REST API** using FastAPI.
- Supports **CORS** for seamless frontend integration.
- Accepts user inputs via a **POST request** to `/predict`.

## 📂 Project Structure
```
📁 insurance-predictor/

│── 📂 data                  
│   ├── medical insurance.csv
│── 📂 notebook              
│   ├── eda.ipynb
│── 📂 templates              
│   ├── index.html             
│── 📜 .gitignore             
│── 📜 README.md
│── 📜 model.pkl           
│── 📜 app.py                 
│── 📜 requirements.txt      

```
 
  

## 🛠️ Installation & Setup

### 1️⃣ **Clone the Repository**
```sh
git clone https://github.com/yourusername/insurance-predictor.git
cd insurance-predictor
```
### 2️⃣ Install Dependencies
```
pip install -r requirements.txt
```
### 3️⃣ Run the Application
```
uvicorn app:app --reload
```
