#  Crop Recommendation System

A machine learning-based system that recommends the most suitable crop to grow based on soil and environmental conditions.

##  Overview

This project uses a supervised machine learning model to predict the most suitable crop to cultivate, given parameters such as:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH value
- Rainfall

##  Features

- Predicts the best crop to grow in given conditions
- Built using Python and Scikit-learn
- Jupyter Notebook for model training and evaluation
- Dataset sourced from public agricultural data

##  Tech Stack

- Python
- Jupyter Notebook
- Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

##  Project Structure

```
crop-recommendation-system/
│
├── CropRecommendation.ipynb       # Jupyter notebook
├── requirements.txt               # Python dependencies
├── README.md                      # Project documentation
└── data/
    └── crop_data.csv              # Dataset used for training
```

##  How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YourUsername/crop-recommendation-system.git
   cd crop-recommendation-system
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the notebook:**
   ```bash
   jupyter notebook CropRecommendation.ipynb
   ```

4. **Run all cells** to train the model and test predictions.

##  Sample Output

> Predicted Crop: **Rice**  
> Based on input conditions like N=90, P=40, K=40, temperature=25°C, pH=6.5, etc.

##  License

This project is open source under the [MIT License](LICENSE).
