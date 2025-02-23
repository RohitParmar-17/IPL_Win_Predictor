# IPL_Win_Predictor

## Overview
IPL_Win_Predictor is a machine learning-based application that predicts the winning probability of IPL cricket teams based on match conditions. It utilizes two datasets: `matches.csv` and `deliveries.csv`, and a trained machine learning model to generate predictions. The application is built using Streamlit, offering an interactive and user-friendly interface for match outcome predictions.

## Screenshots
<img src="screenshots/home.png" alt="Home Page" width="100%">
<img src="screenshots/prediction.png" alt="Prediction Output" width="100%">


## Features
- **Predicts Winning Probability**: Provides the probability of winning for both teams.
- **Data-Driven Predictions**: Uses past match data and ball-by-ball deliveries for analysis.
- **User-Friendly Interface**: Built with Streamlit for ease of use.
- **Machine Learning Model**: A trained `.pkl` model is used for predictions.

## Tech Stack
- **Programming Language**: Python
- **Libraries Used**: Pandas, NumPy, Scikit-Learn, Streamlit, Matplotlib, Seaborn
- **Database**: CSV Files (`matches.csv`, `deliveries.csv`)
- **Machine Learning Model**: Pre-trained `.pkl` file

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Required Python libraries (`pandas`, `numpy`, `scikit-learn`, `streamlit`, `matplotlib`, `seaborn`)

### Steps to Run Locally
1. **Clone the Repository**
   ```sh
   git clone https://github.com/RohitParmar-17/IPL_Win_Predictor.git
   cd IPL_Win_Predictor
   ```
2. **Create and Activate Virtual Environment (Optional)**
   ```sh
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```
3. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```
4. **Run the Streamlit App**
   ```sh
   streamlit run app.py
   ```
   The app will be available at `http://localhost:8501/`

## Deployment
To deploy the project:
1. **Prepare the Model**: Ensure the trained `.pkl` model is included in the project directory.
2. **Deploy on Streamlit Cloud or Heroku**:
   - Upload the code to a GitHub repository.
   - Follow deployment steps on the respective platform.

## Contributing
- Fork the repository
- Create a new branch (`git checkout -b feature-branch`)
- Make your changes and commit (`git commit -m "Added new feature"`)
- Push to the branch (`git push origin feature-branch`)
- Open a pull request

## Contact
For any issues or suggestions, feel free to reach out:
- **Email**: rohitghost5050@gmail.com

