🏏 **Cricket Emotion Detection & Performance Intelligence System**

An end-to-end computer vision and machine learning system that analyzes **player emotions from cricket broadcast videos** and correlates them with **match performance events**.

---

## 🚀 What this project does

* Extracts **facial emotions from cricket videos**
* Converts emotions into **ball-level features**
* Combines emotion data with **match scorecard data**
* Predicts **high-impact events (boundary/wicket)**

---

## 🧠 Key Features

* 🎥 Computer Vision pipeline for video processing
* 😊 7-class facial emotion detection
* 🔗 Fusion of **unstructured (emotion)** + **structured (scorecard)** data
* 📈 Temporal feature engineering (momentum, lags, progression)
* 🌲 Random Forest model for prediction
* 📊 Cross-format evaluation (T20 → ODI)

---

## ⚙️ Pipeline Overview

1. Extract frames from cricket broadcast video
2. Detect faces and classify emotions
3. Generate emotion probability distributions
4. Aggregate into **ball-level features**
5. Merge with scorecard data
6. Train ML model for event prediction

---

## 🧪 Feature Engineering

* Emotion probabilities per ball
* Emotion lag features
* Previous ball impact
* Rolling momentum
* Match progression normalization

---

## 🤖 Model

* **Random Forest Classifier**
* Trained on T20 data
* Tested on ODI data (cross-format generalization)

---

## 📊 Results

* **83% Accuracy**
* **0.91 ROC-AUC**
* Successfully identifies **high-impact events (boundary/wicket)**

---

## 🔬 Experiments

* Compared:

  * Current-ball prediction
  * Next-ball prediction

📌 Insight:

* Strong **emotional correlation with current events**
* Limited predictive power for future events

---

## 📊 Visualizations

* Emotion distribution across match phases
  <Figure size 2000x600 with 2 Axes><img width="1545" height="560" alt="image" src="https://github.com/user-attachments/assets/26612c57-73ce-4c71-82f5-7be4bc932533" />
  <Figure size 1200x600 with 1 Axes><img width="1052" height="547" alt="image" src="https://github.com/user-attachments/assets/a1bade59-90c5-4c29-9ae8-1845f68d377b" />
  <Figure size 800x500 with 1 Axes><img width="680" height="470" alt="image" src="https://github.com/user-attachments/assets/23bad3f0-5bd5-4542-9173-efe5e781c089" />
  <Figure size 1000x800 with 2 Axes><img width="895" height="801" alt="image" src="https://github.com/user-attachments/assets/a5e5d780-9240-458b-8afa-008be7d1f365" />
  *Player-wise Performance Score over balls
  <Figure size 1800x800 with 1 Axes><img width="1792" height="790" alt="image" src="https://github.com/user-attachments/assets/7ab9bd03-9d89-474b-80a3-5b62cb9dfeee" />
*past emotion in previous ball impact on player current performance
<Figure size 800x500 with 1 Axes>
*performance in future prediction
<Figure size 800x500 with 1 Axes>
  
* Clutch performance analysis
  <Figure size 1000x600 with 1 Axes><img width="924" height="547" alt="image" src="https://github.com/user-attachments/assets/06818ab5-5580-45a9-8fab-363f6ad9cc45" />

* Team momentum trends
<Figure size 1200x600 with 1 Axes>
  *Results
  <img width="453" height="130" alt="image" src="https://github.com/user-attachments/assets/fd6c832a-04f2-47af-ae66-2a19328dfe41" />
  <img width="581" height="768" alt="image" src="https://github.com/user-attachments/assets/078ec70a-c506-4073-bdb4-f063e7553f94" />
---

## 📁 Project Structure

```bash
cricket-emotion-performance-analysis/
├── data/
├── notebooks/
├── src/
├── results/
├── README.md
```

---

## ⚙️ Tech Stack

* Python
* OpenCV
* NumPy, Pandas
* Scikit-learn
* Matplotlib

---

## 🔮 Future Improvements

* Real-time emotion tracking
* Deep learning models (LSTM / Transformers)
* Player-level behavioral analysis

---

## 👤 Author

**Jyotiraditya Biswas**
**Mtech Data Science Dtu**
