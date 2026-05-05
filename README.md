# House Price Prediction

A machine learning web application built with Streamlit that predicts house prices in Bengaluru based on property features.

## Features

- **ML Model**: Random Forest Regressor trained on Bengaluru house price data
- **Interactive UI**: User-friendly interface to input property details
- **Real-time Predictions**: Instant price predictions based on user inputs
- **Responsive Design**: Works seamlessly on desktop and mobile

## Project Structure

```
├── app.py                      # Main Streamlit application
├── eda.ipynb                   # Exploratory Data Analysis notebook
├── requirements.txt            # Python dependencies
├── rf_model.joblib            # Trained Random Forest model
├── model_columns.joblib       # Model feature columns
├── cleaned_df.csv             # Processed dataset
├── Bengaluru_House_Data.csv   # Original dataset
├── design.streamlit/
│   └── config.toml            # Streamlit configuration
└── house_logo.png             # UI assets
```

## Installation

### Local Setup

1. Clone the repository:
```bash
git clone https://github.com/akshatakonakeri/house-price-prediction.git
cd house-price-prediction
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
streamlit run app.py
```

The app will open at `http://localhost:8501`

## Deployment

### Deploy on Streamlit Cloud (Recommended)

1. **Sign up** at [Streamlit Cloud](https://streamlit.io/cloud)
2. **Connect your GitHub account**
3. **Click "New app"** and select:
   - Repository: `house-price-prediction`
   - Branch: `main`
   - Main file path: `app.py`
4. **Deploy** - Your app will be live in minutes!

Your public URL will be: `https://house-price-prediction-<username>.streamlit.app`

### Alternative Deployment Options

- **Heroku**: Deploy using `Procfile` (free tier limitations)
- **AWS**, **Google Cloud**, **Azure**: For production-scale deployments
- **Railway**, **Render**: Other modern deployment platforms

## Technologies Used

- **Python 3.12**
- **Streamlit** - Web framework
- **Scikit-learn** - Machine Learning
- **Pandas** - Data processing
- **NumPy** - Numerical computing
- **Seaborn** - Data visualization

## Model Performance

- Algorithm: Random Forest Regressor
- Training Data: Bengaluru house prices dataset
- Features: Location, size, amenities, and property characteristics

## Usage

1. Select a location from the dropdown
2. Enter property details (size, bedrooms, bathrooms, etc.)
3. Click predict to see the estimated price
4. Results are displayed with visualization

## Author

[Your Name](https://github.com/akshatakonakeri)

## License

This project is open source and available under the MIT License.
