# MACHINE-LEARNING-MODEL-IMPLEMENTATION

COMPANY : CODTECH IT SOLUTION PVT.LTD

NAME : SHARIKAA.D

INTERN ID : CT06DH344

CONTENT : PYTHON PROGRAMMING

DURATION : 4 WEEKS

MENTOR NAME : NEELA SANTHOSH KUMAR

ABOUT THE PROJECT:

🎵 Music Genre Classification - ML Project

👩‍💻 Task 4: ML Model Implementation | CodTech Internship

Hi there! 👋  
This project is part of my internship at **CodTech**, where I was asked to implement a machine learning model using **Scikit-learn** to solve a classification problem. I chose something fun and unique — predicting **music genres** using numerical song features like tempo, energy, and danceability. 🎶

---

🎯 What’s the Goal?

To build a predictive model that can guess the **genre of a song** based on its musical attributes. Imagine giving it a song’s features and getting back “Pop” or “Hip-Hop” — that’s the idea!

---

📊 What Data Did I Use?

I created a small custom dataset with features like:
- **BPM (Beats Per Minute)**
- **Energy**
- **Danceability**
- **Loudness**
- **Valence**
- **Length (in seconds)**
- **Acousticness**
- **Speechiness**
- **Popularity**
- **Genre** (the target label)

I used only 5 sample songs to keep it simple and focus on the model-building part.

---

🧠 Tools & Libraries

- **Python**
- **Pandas** for data handling
- **Scikit-learn** for ML model and preprocessing
- **Matplotlib** & **Seaborn** for visualizations

---

⚙️ How It Works

Here’s a quick breakdown of the process:

1. **Data Setup:**  
   Manually created a DataFrame with song features and genres.

2. **Preprocessing:**  
   - Encoded genres (like "Pop" → 2).
   - Scaled the feature values.

3. **Model Training:**  
   Used a **Random Forest Classifier** for its simplicity and power.

4. **Evaluation:**  
   - Printed accuracy score  
   - Generated a **confusion matrix**  
   - Displayed a detailed **classification report**

5. **Prediction:**  
   Tested the model by predicting the genre of a new, made-up song.

---
🧪 Sample Prediction

```python
sample = [[120, 75, 85, -3, 12, 60, 215, 15, 5, 80]]

📊 Visual Output
Confusion Matrix ✅

Classification Report ✅

Accuracy Score ✅

Everything is clean and displayed in the notebook using Seaborn & Matplotlib.

🌟 What I Learned
Even with a small dataset, machine learning models like Random Forest can pick up patterns and make solid predictions. It was fun to work on something related to music and apply the theory in a creative way.

🚀 What’s Next?
If I expand this project later, I’d like to:

Use a real-world dataset (like Spotify or GTZAN from Kaggle)

Include lyrics or audio signals (like MFCCs)

Experiment with different models or deep learning

🙋‍♀️ About Me
Sharikaa D
Python Programming Intern at CodTech
This is Task 4 of my internship — hope you enjoyed checking it out! 😊

OUTPUT OF THE PROJECT:
![Image](https://github.com/user-attachments/assets/bf1d4329-1353-4725-bfbc-98cd6918bd80)
