# 📊 Netflix Data: Cleaning, Analysis, and Visualization  
Analyzing and visualizing **Netflix content data (2008-2021)** to explore trends in movies, TV shows, and original content using **SQL, Python, and Tableau**.  

## 📂 Dataset  
This dataset contains details about **Netflix's vast catalog** of movies and TV shows, including **release years, genres, ratings, and addition dates**. It has been cleaned and structured for analysis.  

📥 **[Download Dataset](https://drive.google.com/file/d/1AfAnp2SH_GQTmEe69tUYpaI-vpkOsuv4/view?usp=sharing)** 

### **Dataset Features**  
- **Show ID**: Unique identifier for each show  
- **Type**: Movie or TV Show  
- **Title**: Name of the content  
- **Director**: Director of the movie or show  
- **Cast**: Lead actors in the movie or show  
- **Country**: Country where the content was produced  
- **Date Added**: When the content was added to Netflix  
- **Release Year**: Year the content was released  
- **Rating**: Audience rating (e.g., PG-13, TV-MA)  
- **Duration**: Length of the content (minutes for movies, seasons for TV shows)  
- **Genres**: Categories or genres of the content  
- **Description**: Short summary of the movie or show  

### **Use Cases**  
- **📊 Data Analysis**: Identify trends in Netflix content additions  
- **🎥 Genre Trends**: Explore most popular content categories  
- **🕒 Release Year Patterns**: Find how Netflix's content library evolved  
- **🌍 Country-Based Insights**: Discover content distribution across countries  
- **🔍 Rating Analysis**: Analyze viewer ratings and audience preferences  

## 🛠️ Tools & Technologies  
- **Python, SQL, Excel**: Data cleaning and analysis  
- **PostgreSQL**: Data storage and processing  
- **Tableau**: Data visualization and dashboard creation  
- **Jupyter Notebook / VS Code**: Development environment  
- **Pandas & NumPy**: Data manipulation  
- **Matplotlib & Seaborn**: Data visualization  

## 🔍 Data Cleaning Process  
To ensure high-quality analysis, the dataset is cleaned using **PostgreSQL** with the following steps:  

1. **🛑 Handling Null Values**  
   - Fill missing values in key columns (e.g., `Director`, `Cast`)  
   - Remove rows with excessive missing data  

2. **📌 Removing Duplicates**  
   - Identify and remove duplicate records  

3. **📊 Populating Missing Rows**  
   - Infer missing values using available data  

4. **🗑️ Dropping Unneeded Columns**  
   - Remove irrelevant features to improve dataset efficiency  

5. **🔍 Splitting Columns**  
   - Extract key details from columns like `Duration`, `Genres`, etc.  

🔹 *Detailed cleaning steps and justifications are included in the code comments.*  

## 📈 Data Visualization  
After cleaning, the dataset is visualized using **Tableau** to generate insights.   

## 📌 Steps & Implementation  
1. **Dataset Exploration**  
   - Load and inspect the raw data  
   - Identify missing values and duplicates  

2. **Data Cleaning with SQL & Pandas**  
   - Perform **data transformation, cleaning, and formatting**  

3. **Exploratory Data Analysis (EDA)**  
   - Find trends in **content additions, ratings, and genre popularity**  

4. **Data Visualization with Tableau**  
   - Build **interactive dashboards** showcasing insights  

## 📊 Project Difficulty Level  
**Intermediate**  

## 🚀 Getting Started  
1. Clone the repository:  
   ```sh
   git clone https://github.com/AgnideepPoddar/Netflix-Data-Analysis.git
   ```  
2. Run the analysis scripts to explore insights.  

## 🤝 Contributions  
Contributions are welcome! Feel free to open issues or submit pull requests.  

## 📜 License  
This project is for educational purposes and follows the **MIT License**.  
