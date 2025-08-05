# 🛳 Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs beginner-level Exploratory Data Analysis (EDA) on the Titanic dataset. The goal is to identify survival patterns based on features like age, gender, and class using Python, Pandas, and Seaborn.

---

## 📌 Problem Statement

Perform EDA on the Titanic dataset to analyze and visualize survival patterns.

---

## 📁 Dataset Features Used

- **PassengerID**
- **Name**
- **Age**
- **Gender** (converted from 'Sex')
- **Class** (converted from 'Pclass')
- **Survived** (0 = No, 1 = Yes)

---

## 🔧 Tools & Libraries

- Python 🐍
- Pandas 📊
- Seaborn 🎨
- Matplotlib
- Jupyter Notebook

---

## 🧹 Data Preprocessing

- Loaded dataset from CSV
- Selected required columns
- Renamed columns for readability
- Filled missing age values using the median age

---

## 📊 Visualizations

1. **Countplot**: Survived vs Not Survived  
2. **Bar Plot**: Survival by Gender and Class  
3. **Pie Chart**: Passenger Class Distribution  
4. **Histogram**: Age Distribution  

---

## 📈 Key Insights

- Females had a significantly higher survival rate.
- Passengers in Class 1 were more likely to survive.
- Most passengers were in Class 3.
- The majority of passengers were young adults and middle-aged.

---

## 📦 How to Run

```bash
git clone https://github.com/Rish-bh/titanic-eda.git
cd titanic-eda
jupyter notebook
```

Open the `titanic_eda.ipynb` file to explore the notebook.

---

## 📁 Project Structure

```
├── titanic_eda.ipynb
├── titanic.csv
├── titanic_cleaned.csv
└── README.md
```

---

## 🧑‍💻 Author

**Rishabh Goyal**  
BSc in Computer Science and Data Analytics, IIT Patna  
Aspiring Data Scientist | Python | Machine Learning

---

## 🌐 License

This project is open-source and free to use for educational purposes.

