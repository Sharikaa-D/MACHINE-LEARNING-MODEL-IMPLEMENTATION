# MACHINE-LEARNING-MODEL-IMPLEMENTATION

COMPANY : CODTECH IT SOLUTION PVT.LTD

NAME : SHARIKAA.D

INTERN ID : CT06DH344

CONTENT : PYTHON PROGRAMMING

DURATION : 4 WEEKS

MENTOR NAME : NEELA SANTHOSH KUMAR

ABOUT THE PROJECT:

# Music Genre Classification - Machine Learning Project

## Task 4 - Machine Learning Model Implementation (CodTech Internship)

This project implements a machine learning model using **Scikit-learn** to classify music genres based on various audio features like tempo, energy, danceability, and more.

---

## Objective

The goal is to create a predictive model that can classify songs into genres such as **Pop**, **Hip-Hop**, or **Electronic** using numerical audio attributes.

---

## Dataset

For simplicity, a small sample dataset was created manually containing features such as:
- BPM (Beats Per Minute)
- Energy
- Danceability
- Loudness
- Liveness
- Valence
- Length (in seconds)
- Acousticness
- Speechiness
- Popularity

Genre labels were encoded using `LabelEncoder` for training.

---

## Tools and Libraries

- Python
- Pandas
- Scikit-learn (Random Forest Classifier)
- Seaborn & Matplotlib (for visualizations)

---

## Model Used

- **Random Forest Classifier**  
A strong ensemble model used for classification tasks, well-suited for structured or tabular data.

---

## Evaluation Metrics

- Accuracy Score
- Classification Report
- Confusion Matrix

---

## Sample Prediction

You can input a custom set of audio features to predict the genre of a new song.

```python
sample = [[120, 75, 85, -3, 12, 60, 215, 15, 5, 80]]
predicted_genre = model.predict(sample)
Results
Even with a small dataset, the model was able to classify music genres with decent accuracy. Adding more data will improve performance and generalization.

Future Improvements
Use a larger dataset like GTZAN

Try other models like KNN, SVM, or Neural Networks

Include lyrics or waveform data for richer classification

Author
Sharikaa D
CodTech Python Programming Internship – Task 4

OUTPUT OF THE PROJECT:

![Image](https://github.com/user-attachments/assets/1a7f3572-5c61-4042-9766-e3444ad60843)
