# Content-Based Recommender System

A machine learning project that recommends items (movies, books, products, etc.) based on their **content similarity**.  
This system uses **feature extraction** and **similarity measures** to suggest items similar to the one selected by the user.

---

## 🚀 Features
- Content-based filtering using item metadata (title, description, tags, etc.)
- Cosine similarity / TF-IDF vectorization for recommendation
- Scalable design for multiple datasets
- Easy to extend with new features

---

## 🛠️ Tech Stack
- **Python 3.9+**
- **Libraries**:  
  - `numpy`  
  - `pandas`  
  - `scikit-learn`  
  - `flask` (if web app)  
  - `pickle` (for saving models)

---

## 📂 Project Structure
- **Whole Recommendation System:**

  - Recommendation System:
    - `movie_dict.pkl`
    - `movie_recommendation_system.ipynb`
    - `movies.pkl`
    - `requirements.txt`
    - `tmdb_5000_credits.csv.zip`
    - `tmdb_5000_movies.csv.zip`

  - Web Recommendation System:
    - `app.py`
    - `movie_dict.pkl`
    - `movies.pkl`
    - `requirements.txt`

- `.gitignore`
- `README.md`

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/SHOBHIT-SG31/Content-Based-Recommendation-System.git
   cd Whole Recommendation System


2. **Create Virtual Enviroment (Recommended per folder)**
   ```bash
   python -m venv .venv
   .venv\Scripts\activate

3. **Install Dependencies**
    ```bash
    pip install -r Folder1/requirements.txt
    pip install -r Folder2/requirements.txt

---

## ▶️ Usage

- **Run the Backend Model:**
  ```bash
  python Recommendation System/movie_recommendation_system.ipynb

- **Run the Frontend Model:**
  ```bash
  python Web Recommendation System/streamlit run app.py

- Enter an item name (e.g., movie title) → system returns top-N similar items.

---

## 📊 Example Output

**Input: "Inception"**
- Recommendations:
  - `Interstellar`
  - `The Matrix`
  - `Shutter Island`
  - `Memento`

---

## 📌 Notes

- `similarity.pkl` is ignored in `.gitignore` because it exceeds 100MB.
- Large datasets/models should be stored externally (Google Drive, Kaggle, etc.) and linked in README.
 
---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 License

This project is licensed under the MIT License - see the `[Looks like the result wasn't safe to show. Let's switch things up and try something else!]` file for details
