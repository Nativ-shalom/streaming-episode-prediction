# streaming-episode-prediction
# 🎬 Predicting Episode Continuation in a Streaming Platform

This project explores how user behavior affects the likelihood of continuing to the next episode on a streaming platform like Netflix.

## 📊 Problem Statement

Can we predict whether a user will **continue watching the next episode** based on features like:

- Time of day
- Device type
- Percent of current episode watched
- Auto-play delay
- Day of the week
- Episode length

## 🛠️ Technologies Used

- Python 🐍
- Pandas, NumPy
- Scikit-learn
- RandomForestClassifier
- Seaborn & Matplotlib for visualization

## 🧪 Model & Results

We built a **Random Forest classifier** on a balanced dataset.

### ✅ Accuracy: **87%**
### 🔍 Top features influencing continuation:
- `finished_percent`
- `hour_of_day`
- `episode_length`
- `auto_play_delay`

## 📈 Visual Example

![Feature Importance](feature_importance_chart.png)  <!-- העלה את התמונה לגיטהאב ושם אותה בשם הזה -->

## 🧠 Key Insights

- Watching during **evening hours** increases continuation.
- **Finishing the episode** is the strongest indicator.
- **Auto-play delay below 7 seconds** encourages binge-watching.
- **PCs and TVs** have higher continuation rates than tablets.

## 🚀 Future Work

- Test with real-world datasets from public streaming analytics
- Add more behavioral features like pause frequency, skip rate, etc.
- Build a web interface to visualize continuation probability

## 🤝 Contact

Project by **Nativ Shalom**  
Feel free to connect with me on [LinkedIn](https://www.linkedin.com/) or contribute to the project!
