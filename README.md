# 🏝️ Villager Popularity and Attribute Patterns in Animal Crossing: New Horizons

🎥 **Project Video:** *https://youtu.be/iRhRQd6YiiM*

## 📌 Overview
This project explores what drives villager popularity in *Animal Crossing: New Horizons* by analyzing in-game attributes such as personality, species, hobbies, and aesthetics. Using clustering, association rule mining, and statistical analysis, I uncover patterns that explain why certain villagers are more popular within the community. This project demonstrates how data mining techniques can extract meaningful insights from categorical datasets, similar to real-world applications like recommendation systems and user preference modeling.

👉 **Main Deliverable:** `main_notebook.ipynb`

---

## ❓ Research Questions
- **RQ1:** Which villager attributes are associated with high popularity, and are these relationships statistically significant?
- **RQ2:** What clusters of villagers emerge based on their attributes (species, personality, hobby, styles), and do these clusters relate to popularity?

---

## 📊 Datasets
- **Animal Crossing New Horizons Catalog (Villagers)**
  - **Source:** *https://www.kaggle.com/datasets/jessicali9530/animal-crossing-new-horizons-nookplaza-dataset/data?select=villagers.csv*
- **Animal Crossing Portal Villager Popularity**
  - **Source:** *https://www.kaggle.com/datasets/ampiiere/acnh-villager-popularity*

### 🔧 Preprocessing
- Merged popularity data into villager data
- Cleaned missing or inconsistent values, lowercased  
- Encoded categorical variables (one-hot encoding)  
  
More detailed preprocessing code in `main_notebook.ipynb`

---

## 🔁 How to Reproduce
This project was developed using **Google Colab**. 

Most simply, download `main_notebook.ipynb`, upload to Google Colab, and Run All cells. 
OR:

1. Clone the repository  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt```
3. Open and run: `main_notebook.ipynb`
4. Run all cells in order (top -> bottom)

---
## ⚙️ Key Dependencies
- Python 3.12.13  
- pandas 2.2.2  
- numpy 2.0.2  
- scikit-learn 1.6.1  
- mlxtend 0.23.4  
- matplotlib 3.10.0  
- seaborn 0.13.2  
- scipy 1.16.3
- kagglehub 1.0.0

*(Full dependency list is available in `requirements.txt` for full reproducibility.)*

---
## 📁 Repo Structure

- `main_notebook.ipynb`                        Main notebook (all code + final results)
- `checkpoints/`                               Checkpoint notebooks
  - `DataMiningProject_checkpoint1.ipynb`
  - `DataMiningProject_checkpoint2.ipynb`
- `requirements.txt`                           Dependencies
- `README.md`                                  Project overview

---
## 📈 Results Summary

- Popularity can be determined by single attributes, but also by combinations of traits.
- Clustering reveals meaningful villager archetypes
- Statistical tests confirm that these patterns are not due to random chance, and provide insight into the strength of association between popularity and attributes.
- Association rules highlight specific attribute combinations linked to high, medium, and low popularity levels.

