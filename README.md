second_drivrs is a Python-based data science application that performs data cleaning, exploratory data analysis (EDA), and runs a predictive model via a web app (app.py). The model is saved in model.pkl.

📁 Repository Structure
second_drivrs/
│
├── Part1 Cleaning.ipynb        # Data cleaning notebook
├── Part2 EDA.ipynb             # Exploratory Data Analysis
├── app.py                     # Flask app to serve the model
├── model.pkl                  # Trained ML model file
├── requirement.txt            # Required Python packages
└── README.md                  # (Add this file)
🧰 Requirements

Before running the app, install Python and the dependencies:

# create and activate virtual environment (optional but recommended)
python3 -m venv venv
source venv/bin/activate  # (Windows: venv\Scripts\activate)

# install required packages
pip install -r requirement.txt

⚠️ Make sure you are using Python 3.8+.

▶️ Running Locally (Development)

Clone the repository

git clone https://github.com/Jags512/second_drivrs.git
cd second_drivrs

Install dependencies

pip install -r requirement.txt

Run the app

python app.py

Open in browser

Navigate to:

http://127.0.0.1:5000

You should see the application running.
