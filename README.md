# AI System for Personalized Content Creation in Media

**Internship Project | Infosys Springboard**

---

## Milestone-1: Personalized News Recommendation

### Objective
- Load and preprocess the News Category Dataset.
- Implement a basic personalized news recommendation system.
- Demonstrate recommendations based on user-selected interests.

---

### Dataset
- **Source:** Kaggle - News Category Dataset  
- **Format:** JSON Lines (.json)  
- **Columns used:** `category`, `headline`, `short_description`  
- **Total articles loaded:** 176189

---

### Methodology
1. Loaded the dataset into a Pandas DataFrame.
2. Selected relevant columns and removed missing values.
3. Built a recommendation function that filters news articles based on user interest.
4. Sampled a few articles from matching categories for personalized recommendations.
5. Demonstrated interactive output using user input in Jupyter/Colab.

---

### How to Run
1. Download the repository and open the notebook `Milestone1_PersonalizedContentAI.ipynb` in Jupyter Notebook or Google Colab.
2. Make sure the dataset file `News_Category_Dataset_v3.json` is in the same directory as the notebook.
3. Run all cells sequentially.
4. When prompted, enter a category of interest (e.g., `Tech`, `Sports`, `Business`, `Entertainment`) to get personalized news recommendations.

---

### Sample Output
