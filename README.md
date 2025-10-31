# Handling Mixed Variable Data Columns  
**🧠 AI-Generated README (custom prompt used for conceptual clarity and learning ease)**  

---

## 📘 Overview  
This notebook explains how to handle **mixed data columns** — those containing both numeric and alphabetic values — using the **Titanic dataset** (available in the repository).  
Such columns often appear messy but can be separated into meaningful categorical and numerical parts for better analysis.

---

## 🧩 Steps and Implementation  

### 1. Dataset  
- Used the **Titanic dataset** from the repository.  
- Identified columns where both numbers and alphabets were mixed, such as Passenger ID, Cabin, and Ticket.  

---

### 2. Visualization  
- Created a bar plot to visualize value frequencies in the mixed column.  
- (Image attached as **<img width="552" height="450" alt="mixv1" src="https://github.com/user-attachments/assets/15e22c88-e59d-43f8-a44d-199dbe3f93c4" />
**)  
- Observed that many values contained both digits and letters.  

---

### 3. Extracting Numeric Data  
- Converted the mixed column into numeric form while keeping non-numeric values as NaN.  
- This resulted in two columns — one numeric and one categorical.  

---

### 4. Handling Null Values  
- Replaced missing numeric entries with NaN for clarity.  
- Ensured that both numeric and categorical versions of the column were available for analysis.  

---

### 5. Handling the Cabin Column  
- The **Cabin** column contained both alphabets and numbers (e.g., C123).  
- Extracted the alphabetic portion as a categorical column and the numeric portion as another column.  
- Created a bar plot of cabin categories to visualize their frequency (attached as **<img width="543" height="429" alt="mixv2" src="https://github.com/user-attachments/assets/2416cea0-146e-4f82-8bdf-d9cea5065b25" />
**).  

---

### 6. Handling the Ticket Column  
- The **Ticket** column included prefixes and numeric codes (e.g., PC 17599).  
- Split the column into a categorical prefix and a numeric ticket number.  
- This made ticket data more structured and analyzable.  

---

## 🧠 Observations  
- Mixed data columns are common in real-world datasets like Titanic.  
- Separating them into categorical and numeric parts improves interpretability and model performance.  
- Methods like numeric extraction, string operations, and category grouping are key to clean transformation.  

---

## 🧰 Tools Used  
- **Libraries:** pandas, matplotlib.pyplot, seaborn, numpy  
- **Dataset:** Titanic dataset (available in the repository)  

---

## 🖼️ Attached Visuals  
1. Bar plot of the initial mixed column distribution  
2. Cabin category frequency bar plot  

---

## ✅ Conclusion  
By properly handling mixed variable columns, data becomes more structured and ready for statistical or machine learning modeling.  
This approach enhances clarity, data quality, and algorithm performance.  

---

📎 *Note: This README was AI-generated using a custom prompt for educational and clarity purposes.*
