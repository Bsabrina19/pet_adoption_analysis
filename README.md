# 🐶 **Animal Shelter Data Analysis**  

## 📌 **Project Overview**  
This project analyzes **animal shelter intake and adoption trends** using **data visualization, categorization, and statistical insights**. It processes shelter records from  **Long Beach Animal Shelter Dataset** to explore patterns in intake reasons, adoption preferences, length of stay, and other factors influencing pet outcomes.  

## 📂 **Datasets Used**  
- **Long Beach Animal Shelter Dataset** (API & Excel)   

## ⚙ **Tech Stack**  
- Python 🐍  
- Pandas 📊  
- NumPy 🔢  
- Matplotlib 📈  
- Seaborn 🎨  
- Requests 🌐  

## 🏗 **Project Structure**  
### **1️⃣ Data Collection & Cleaning**  
✅ **API Authentication & Data Retrieval**   
- Pull shelter records using **Long Beach API**  

✅ **Cleaning & Standardization**  
- Fix **spelling inconsistencies**  
- Normalize **categorical values**  
- Handle **missing values** intelligently  

### **2️⃣ Shelter Intake & Adoption Analysis**  
✅ **Intake Trends**  
- Categorize intake reasons (e.g., **stray, owner surrender, rescue cases**)  
- Track yearly intake volumes  

✅ **Adoption Insights**  
- Analyze adoption rate by **age, sex, and color**  
- Compare **adopted vs. total dogs** across years  

### **3️⃣ Population & Stay Duration Analysis**  
✅ **Shelter Capacity Trends**  
- Compute **peak occupancy per year**  
- Track **remaining dogs** after yearly adoption cycles  

✅ **Length of Stay & Age Impact**  
- Evaluate how **age at intake affects shelter stay**   

### **4️⃣ Visualizations & Reporting**  
✅ **Charts & Graphs**  
- **Stacked bar charts** for intake trends  
- **Pie charts** for adoption breakdowns  
- **Scatter plots** for length of stay vs. intake age  
- **Comparative bar charts** for adoption rate by sex & color  

✅ **Export & Data Storage**  
- Save structured **CSV & Excel reports** for analysis  
- Merge **pet & shelter records** for a consolidated view

## 📚 Sources & Références

- [Petfinder API Documentation](https://www.petfinder.com/developers/)
- [Long Beach Animal Shelter Dataset](https://data.longbeach.gov/)
- [Matplotlib Official Guide](https://matplotlib.org/stable/contents.html)
- [Pandas Documentation](https://pandas.pydata.org/docs/)

## 🏁 **How to Run the Project**  
1️⃣ Install dependencies:  
```bash
pip install -r requirements.txt