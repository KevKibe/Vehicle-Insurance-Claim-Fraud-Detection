## Problem Statement
Fitting a model that will be able to classify a vehicle insurance claim as either fraud or legitimate.

## Dataset
The data used are samples of vehicle claim data with a target variable as fraud represented as 1 and legitimate represented as 0.

## Deployment
I deployed the model as a Flask API through Docker image to Google Cloud Run.

## Prerequisites
- Python3.7
- Docker
## Installation
- Clone the repository: `git clone https://github.com/KevKibe/Fraud-Detection-for-Vehicle-Insurance-Claims`
- Navigate to the project directory: `cd Fraud-Detection-for-Vehicle-Insurance-Claims`
-  Install the dependencies: `pip install -r requirements.txt`
## Usage
- Start the Flask API: `python main.py`
- Access the web interface at: `https://claim-fraud-detection-f5m2fxxbbq-uc.a.run.app` or your local server `http://localhost:5000`
- Run the model on test data: `python test.py`
   
