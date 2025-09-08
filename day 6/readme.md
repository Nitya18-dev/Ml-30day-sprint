
---

# 📑 REPORT.md  
```markdown
# 📊 Titanic Dataset - EDA Report

## 📌 Dataset Overview
- Rows: 891  
- Columns: 12 (PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked)  
- Target column: **Survived** (0 = No, 1 = Yes)  

---

## 🔍 Key Questions & Insights

### 1. What percentage survived?
- Around **38% passengers survived** the disaster.  
- Survival rate was low overall.

---

### 2. Did gender affect survival?
- **Women survival rate:** ~74%  
- **Men survival rate:** ~19%  
➡️ Women were prioritized for lifeboats.

---

### 3. Did class affect survival?
- **1st Class:** Highest survival (~63%)  
- **2nd Class:** Moderate survival (~47%)  
- **3rd Class:** Lowest survival (~24%)  
➡️ Social class had a strong impact.

---

### 4. Did age matter?
- Children had higher survival rates.  
- Younger passengers had better chances than seniors.  

---

### 5. Does fare influence survival?
- Higher ticket price → higher survival chance.  
- Rich passengers in 1st class mostly survived.  

---

### 6. What about family size?
- Passengers traveling with **small families (2–4 members)** survived more.  
- Solo travelers and very large families had lower survival rates.  

---

### 7. Does port of embarkation matter?
- Passengers boarding at **Cherbourg (C)** had higher survival rates compared to Southampton (S) and Queenstown (Q).  

---

## 📌 Final Insights
1. **Gender and Class were the strongest survival factors.**  
2. **Women and children were more likely to survive.**  
3. **Wealthier passengers (higher fare, 1st class) survived more.**  
4. **Family size and boarding port also influenced survival.**  

---

## 📂 Deliverables
- 📓 `notebook.ipynb` → Detailed analysis with visuals  
- 📝 `REPORT.md` → Summary of key findings  
- 📁 `data/titanic.csv` → Dataset  

---
