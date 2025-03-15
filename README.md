 📊 IMDb Top 250 Movies Analysis  

## 📌 Project Overview  
This project extracts, processes, and analyzes IMDb's **Top 250 Movies** using **web scraping, data preprocessing, and data cleaning** techniques. The goal is to gather movie details, handle missing data, and prepare a clean dataset for further analysis.  

---

## 🛠 Features  
✅ **Web Scraping** – Extract movie details (titles, descriptions, ratings, URLs) from IMDb.  
✅ **Data Processing** – Convert raw data into a structured format, handle missing values, and clean text.  
✅ **Data Cleaning** – Remove duplicates, fix errors, and normalize the dataset.  
✅ **Final Dataset** – A well-structured CSV file ready for visualization or further analysis.  

---

## 💂‍♂️ Project Structure  
```
💚 imdb_top250_project/
│── 📄 IMDb_Top250_Analysis.ipynb  # Jupyter Notebook with the entire code
│── 📂 data/                       # Folder for datasets
│   ├── raw_imdb_data.json         # Raw scraped data
│   ├── initial_sample.csv         # Initial dataset sample
│   ├── cleaned_full_dataset.csv    # Final cleaned dataset
│── 📂 docs/                        # Documentation folder
│   ├── README.md                   # Project overview & instructions
│   ├── Project_Report.md           # Detailed project report
│── 📄 requirements.txt               # List of required Python libraries
```

---

## 🚀 How to Run the Project  

### 🔹 1. Install Dependencies  
Make sure you have Python installed, then install the required libraries:  
```bash
pip install -r requirements.txt
```

### 🔹 2. Run Jupyter Notebook  
```bash
jupyter notebook
```
Open `IMDb_Top250_Analysis.ipynb` and execute the cells step by step.  

---

## 📝 Dataset Information  
| Column | Description |
|---------|------------|
| **Title** | Movie title |
| **URL** | IMDb page link |
| **Description** | Short movie description |
| **Rating** | IMDb user rating |

---

## ⚙️ Data Processing Steps  

### **Step 1: Web Scraping**  
- Used `requests` and `BeautifulSoup` to extract movie details.  
- Saved raw JSON data in `raw_imdb_data.json`.  

### **Step 2: Data Preprocessing**  
- Converted raw JSON data to a structured format.  
- Stored initial data sample in `initial_sample.csv`.  

### **Step 3: Data Cleaning**  
- Filled missing values (`N/A` for text, mean value for ratings).  
- Removed duplicates and normalized text fields.  
- Cleaned dataset saved as `cleaned_full_dataset.csv`.  

---

## 📊 Results  
- Successfully extracted and cleaned **IMDb Top 250 Movies** data.  
- The final dataset is well-structured and ready for further analysis.  

---



## 📌 Author  
**Nithish Nuthalapati**  
Master’s in Business Analytics | Data Science Enthusiast  

---

## 📚 License  
This project is for educational purposes only. IMDb data is publicly available but belongs to IMDb.

