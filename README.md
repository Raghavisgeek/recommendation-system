# recommendation-system


 *COMPANY*: CODTECH IT SOLUTIONS

 *NAME*: RAGHAV PANDEY
 
 *INTERN ID*: CT04DF122
 
 *DOMAIN*: MACHINE LEARNING
 
 *DURATION*: 4 WEEKS
 
 *MENTOR*: NEELA SANTOSH

 
This project builds a basic **Book Recommendation System** using collaborative filtering techniques. The goal is to suggest books to users based on their past preferences and ratings of similar users. This system is implemented in Python using the `pandas`, `numpy`, and `scikit-learn` libraries.

## 📘 Dataset

The system uses a book rating dataset, typically involving three key CSV files:
- `Books.csv`: Contains book details (title, author, etc.)
- `Users.csv`: Contains user demographic information
- `Ratings.csv`: Contains user ratings for various books

## 🛠️ Methodology

The approach primarily uses **Collaborative Filtering** based on user-book interaction matrix. The process includes:

1. **Data Loading & Cleaning**
   - Handling missing values and filtering low-rated books/users
   - Merging datasets to construct a user-item interaction matrix

2. **Pivot Table Creation**
   - Creating a matrix of books vs. users with ratings as values

3. **Cosine Similarity**
   - Calculating similarity between books based on rating patterns

4. **Generating Recommendations**
   - For a given book, find similar books using similarity scores

## 🔧 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn (`cosine_similarity` from sklearn.metrics.pairwise)
- Jupyter Notebook

## 🧪 How to Use

1. Install required libraries:
```bash
pip install pandas numpy scikit-learn
```

2. Run the notebook:
```bash
jupyter notebook book-recommender-system.ipynb
```

3. Enter a book name and get recommendations based on collaborative filtering.

## 📊 Sample Output

Example:
```
If you liked 'Harry Potter and the Sorcerer's Stone', you might also enjoy:
- Harry Potter and the Chamber of Secrets
- The Hobbit
- Eragon
- The Chronicles of Narnia
```

## 📌 Learnings

This project helped in understanding:
- How collaborative filtering works using similarity matrices
- How to handle sparse data in recommendation systems
- The importance of filtering and data preprocessing

## 🔮 Future Improvements

- Incorporate matrix factorization techniques (SVD, NMF)
- Add content-based filtering using book metadata (genre, author, etc.)
- Build a hybrid recommender system

---

Created by Raghav Pandey
