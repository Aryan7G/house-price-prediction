# House Price Prediction

My first machine learning project for predicting house prices using Python and scikit-learn.

## Project Goal
This project predicts house prices based on features like:
- area
- bedrooms
- bathrooms
- stories
- parking
- furnishing status
- and other house-related features

The model is trained using **Linear Regression**.

---

## Project Structure

house-price-prediction/
│
├── data/
│   └── Housing.csv
│
├── notebooks/
│   └── house_price_prediction.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore

---

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook / Google Colab

---

## Model Workflow
1. Load the dataset
2. Preprocess categorical columns using one-hot encoding
3. Split data into training and testing sets
4. Train a Linear Regression model
5. Evaluate performance using:
   - MAE
   - MSE
   - R² Score

---

## Results
Example model performance:

- **MAE:** 970043.40
- **MSE:** 1754318687330.66
- **R² Score:** 0.65

---

## How to Run

### 1) Download the project
You can either:

#### Option A — Download ZIP
- Click the green **Code** button on GitHub
- Click **Download ZIP**
- Extract the ZIP file
- Open the project folder

#### Option B — Clone with Git
```bash
git clone https://github.com/Aryan7G/house-price-prediction.git
cd house-price-prediction
```

---

### 2) Install Python
Make sure Python 3 is installed.

Check with:

```bash
python --version
```

---

### 3) Install required libraries
Open terminal / command prompt inside the project folder and run:

```bash
pip install -r requirements.txt
```

---

### 4) Open the notebook
Open this notebook in **Jupyter Notebook** or **Google Colab**:

```bash
notebooks/house_price_prediction.ipynb
```

---

### 5) Make sure dataset path is correct
The dataset should be inside:

```bash
data/Housing.csv
```

If you are running the notebook from the `notebooks` folder, use this path in your code:

```python
df = pd.read_csv("../data/Housing.csv")
```

---

### 6) Run all notebook cells
Run all cells from top to bottom.

The notebook will:
- load the dataset
- preprocess the data
- train the model
- evaluate predictions

---

## Future Improvements
- Try better models like Random Forest or XGBoost
- Add feature scaling and feature engineering
- Build a Streamlit web app for predictions
- Improve model accuracy with hyperparameter tuning

---

## Author
**Aryan**  
Beginner in AI/ML, building projects and learning in public 🚀
