Handling Missing Values in University Ranking Data
The dataset used in this project was provided by UCL for a recruitment task and is not publicly available. Therefore, it has not been included in this repository.
This repository contains the complete code used for processing and handling missing values in a real-world university ranking dataset. The project was completed as part of the application process for a Data Analyst role at UCL and demonstrates effective preprocessing, analysis, and imputation strategies using Python.
________________________________________
📌 Project Description
The dataset contains university performance metrics from The Guardian University Guide, including missing values across several numerical features. This project:
•	Loads and cleans the data
•	Identifies and summarizes missing data
•	Applies multiple imputation strategies (e.g., mean, median, KNN, and Random Farest)
•	Compares the effectiveness of imputation methods
•	Outputs cleaned datasets for downstream analysis
The main Python scripts are:
•	handling_missing_values.py: Cleans and imputes missing values using several strategies to find out the best method.
•	filling_missing_values.py: Performs imputations.
________________________________________
📁 Project Structure
├── README.md                     # Project overview
├── requirements.txt              # Python dependencies
├── handling_missing_values.py    # Script for handling missing values
├── filling_missing_values.py     # Script for additional analysis and visualizations
________________________________________
⚙️ Installation
To run this project:
1.	Clone the repository:
git clone https://github.com/Fatemeh_Rajaei_Nesheli/Missing-values.git
cd Missing-values
2.	Install required packages:
pip install -r requirements.txt
________________________________________
🚀 Usage
1. Preprocessing
To clean the dataset and apply imputation methods, run:
python handling_missing_values.py
This script generates multiple versions of the cleaned dataset using different imputation techniques.
2. Exploratory Analysis
For imputation, run:
python filling_missing_values.py
________________________________________
📊 Features in the Dataset
•	Year
•	Institution
•	Subject
•	Satisfied with Teaching
•	Satisfied with Course
•	Satisfied with Assessment
•	Continuation
•	Student: staff ratio
•	Career prospects
•	Value added score / 10
•	Expenditure per student
•	Average Entry Tariff
•	Guardian Score / 100
________________________________________
📄 License
This project is released under the MIT License.
________________________________________
👩‍💻 Author
Fatemeh Rajaei Nesheli
Research Assistant in AI and Robotics
📧 fatemeh.raj [at] gmail [dot] com


