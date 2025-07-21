# California Housing Price Predictor 🏡

This project is a simple yet complete machine learning pipeline to predict housing prices in California using the [California Housing dataset](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset) from scikit-learn.

## 💡 Objective

Train a regression model that can estimate the average housing price of a neighborhood based on socio-economic and geographic features.

## 📊 Dataset

Each row represents a block (neighborhood) in California, not a single house. Features include:

- **MedInc**: Median income in the block
- **HouseAge**: Average age of houses
- **AveRooms**: Average number of rooms per household
- **AveBedrms**: Average number of bedrooms
- **Population**: Total population in the block
- **AveOccup**: Average number of residents per household
- **Latitude / Longitude**: Location of the block
- **Target**: Median house price (in $100,000s)

## 🧠 Model

The project uses:

- 📦 `XGBoost` as the core regressor  
- ⚙️ `train_test_split` for dataset splitting  
- 📈 Evaluation with **Mean Squared Error** and **R² Score**

## 📌 Results

- **MSE**: ~0.26  
- **R² Score**: ~0.80 → good performance on real-world data  
- Includes a visualization of predicted vs. actual values

## 🛠️ Stack

- Python 3.12
- Scikit-learn
- XGBoost
- Pandas
- Matplotlib

## 📂 How to Run

1. Clone the repo
2. Create a virtual environment  
   `python3 -m venv .venv && source .venv/bin/activate`
3. Install dependencies  
   `pip install -r requirements.txt`
4. Launch Jupyter  
   `jupyter notebook`
5. Open `main.ipynb`

## 🔜 Next steps

The next project will include image classification and adversarial attacks (FGSM) as part of AI Red Teaming practice.

---

Made with ☕ and curiosity by [Ema-reds](https://github.com/Ema-reds)
