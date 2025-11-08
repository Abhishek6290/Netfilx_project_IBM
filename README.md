# 🎬 Netflix Data Analysis Project

## 📘 Overview
This project focuses on exploring and analyzing the **Netflix Movies and TV Shows dataset** to uncover meaningful insights about its content distribution, popular genres, release trends, and audience ratings.  
It is an **academic project** built to demonstrate practical skills in **data analysis and visualization using Python**.

---

## 🧠 Objective
The main objectives of this analysis are:
- To understand the growth and trends of Netflix content over time.  
- To find which **countries** produce the most Netflix content.  
- To analyze the distribution of **Movies vs. TV Shows**.  
- To identify the **most common ratings and genres**.  
- To visualize the evolution of Netflix’s content library.  

---

## 🛠️ Tools & Technologies Used
- **Python 3**
- **Pandas** → Data cleaning and manipulation  
- **Matplotlib** & **Seaborn** → Data visualization  
- **Jupyter Notebook / Google Colab** → Code execution and exploration  
- **PowerPoint (MS PPT)** → Final presentation for academic submission  

---

## 📂 Dataset Information
**Dataset Name:** Netflix Titles Dataset  
**Source:** [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
**Size:** ~7,800 records  

**Key Columns:**
- `show_id` – Unique identifier  
- `type` – Movie or TV Show  
- `title` – Name of the content  
- `country` – Country of production  
- `date_added` – Date added on Netflix  
- `release_year` – Original release year  
- `rating` – Audience rating (e.g., TV-MA, PG, R)  
- `listed_in` – Genre/category  
- `duration` – Runtime or number of seasons  

---

## 🧩 Process Workflow

### 1. Data Loading
- Loaded the dataset using Pandas.
- Displayed the first few rows and data summary using `df.head()` and `df.info()`.

### 2. Data Cleaning
- Filled missing values in `country`, `rating`, and `date_added` columns.
- Removed duplicate rows.
- Converted `date_added` into proper **datetime** format.
- Ensured data consistency for analysis.

### 3. Exploratory Data Analysis (EDA)
Performed data exploration to understand:
- Type-wise content distribution  
- Country-wise content production  
- Ratings distribution  
- Genre frequency  
- Release year trends  

### 4. Visualization
Created simple and effective visualizations using Matplotlib and Seaborn:
- **Bar Chart**: Comparison of Movies vs TV Shows  
- **Pie Chart**: Top 10 Content-Producing Countries  
- **Count Plot**: Distribution of Content Ratings  
- **Horizontal Bar Chart**: Top 10 Most Common Genres  
- **Line Chart**: Growth of Netflix Content Over the Years  

---

## 📈 Key Insights
- **Movies dominate** Netflix’s library, with significantly more entries than TV Shows.  
- The **United States** produces the highest number of Netflix titles.  
- The most frequent rating is **TV-MA**, indicating a focus on mature audience content.  
- **Dramas** and **Comedies** are the most popular genres globally.  
- A massive increase in content production was seen **after 2015**, marking Netflix’s expansion phase.  

---

## 📊 Visual Highlights
Below are some of the main visualizations used:
1. Movies vs TV Shows Comparison  
2. Top 10 Countries with Most Titles  
3. Ratings Distribution Overview  
4. Most Common Genres  
5. Content Growth by Release Year  

---

## 🎓 Author
**Abhishek Verma**  
📘 *Bachelor of Computer Application (BCA)*  
🏫 *Shri Ramswaroop Memorial University*  
📍 India  

---

## 📎 Project Files
- **Dataset:** `netflix_titles.csv`  
- **Notebook:** `Netflix_Data_Analysis.ipynb`  
- **Presentation:** `Netflix_Data_Analysis_Project_Abhishek_Verma.pptx`

---

## 🏷️ Tags
`#Python` `#Pandas` `#Matplotlib` `#Seaborn` `#Netflix` `#DataAnalysis` `#EDA` `#DataVisualization` `#Project`

---

## 💬 How to Run
1. Download or clone this repository.  
2. Install dependencies using:  
   ```bash
   pip install pandas matplotlib seaborn
