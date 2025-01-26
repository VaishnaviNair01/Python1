

# Movie Data Analysis

This repository contains an exploratory data analysis (EDA) project on a movie dataset. The project provides insights into movie genres, popularity, votes, and trends over time. The analysis was conducted using Python and Jupyter Notebook, with a focus on extracting meaningful insights and presenting them effectively.

---

## 📊 Features of the Analysis

1. **Most Frequent Genre**
   - Identified the most frequent movie genre and its representation in the dataset.

2. **Genres with the Highest Votes**
   - Determined the genres with the highest number of popular votes.

3. **Most and Least Popular Movies**
   - Highlighted the movie with the highest popularity and its associated genres.
   - Identified the movie with the lowest popularity along with its genres.

4. **Year with the Most Filmed Movies**
   - Analyzed the dataset to find the year with the highest number of movies produced.

---


## 🔄 Data Preprocessing

To ensure accurate and meaningful analysis, the dataset was preprocessed with the following steps:

1. **Handling Missing Values**
   - Checked for missing data and handled null values appropriately (e.g., replacing with mean/median or dropping rows/columns).

2. **Data Cleaning**
   - Removed duplicates and irrelevant columns.
   - Standardized data formats (e.g., converting date fields to datetime, ensuring consistent text formatting).

3. **Feature Engineering**
   - Extracted relevant information such as year from date fields.
   - Created new features for enhanced analysis, such as aggregated popularity scores.

4. **Outlier Detection**
   - Identified and treated outliers in numeric columns like popularity and votes to avoid skewed results.

---


## 🔍 Key Insights

- **Most Frequent Genre:** Drama is the most common genre, representing over 14% of the dataset.  
- **Highest Votes:** Drama again leads in popularity, with over 18.5% of movies having the highest votes.  
- **Most Popular Movie:** *Spider-Man: No Way Home* holds the highest popularity rate and spans genres of Action, Adventure, and Science Fiction.  
- **Least Popular Movie:** *The United States, thread* (possible typo) has the lowest popularity and belongs to Music, Drama, War, Sci-Fi, and History genres.  
- **Most Filmed Year:** 2020 has the highest number of movies in the dataset.

---

## 📈 Sample Visualizations

[Genre distribution][https://github.com/VaishnaviNair01/Python1/blob/main/genre%20distribution.png "distribution of genre"]

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Notebook:** Jupyter Notebook  
- **Libraries Used:** Pandas, NumPy, Matplotlib, Seaborn, etc.

---

## 📁 Repository Structure

```
movie-data-analysis/
│
├── movie_data_analysis.ipynb   # Jupyter Notebook with the analysis
├── data/                       # Folder for raw/processed data 
├── README.md                   # Project documentation
└── images/                     # Visualizations and plots 
```

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-data-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd movie-data-analysis
   ```
3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook movie_data_analysis.ipynb
   ```

---


## 🖋️ Author

- **Vaishnavi Nair**  
  Mathematics and Computing Student, NIT Hamirpur  
  

---

## 🌟 Acknowledgments

This project was inspired by the exploration of movie trends and insights. Data sources and libraries were crucial in enabling the analysis.


