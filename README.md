# mnist-handwritten-digit-classifier

This project demonstrates a digit classifier trained on the MNIST dataset using a deep learning model built with TensorFlow. The model can recognize handwritten digits (0-9) with high accuracy. The web application is built using Streamlit, which allows for interactive prediction and visualization.

## Prerequisites
- Python 3.8 or later
- Git
- Virtual environment tools (optional but recommended)

## Setup Instructions

Create and activate a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Install system dependencies (if using Streamlit Cloud, ensure apt-packages is set up):

bash
Copy code
sudo apt-get update
sudo apt-get install -y libgl1
Usage
Run the Streamlit app:

bash
Copy code
streamlit run app.py
Open your browser and navigate to:

arduino
Copy code
http://localhost:8501
Interact with the app:

Upload a digit image to classify
View the prediction and confidence score
Model Training
To train the model from scratch:

Run the training script:

bash
Copy code
python train_model.py
The trained model will be saved to the models/ directory.

Deployment
Streamlit Cloud
Push your project to a GitHub repository.
Sign in to Streamlit Cloud with your GitHub account.
Deploy the app by selecting the repository and branch.
Ensure requirements.txt and apt-packages (if needed) are present in the repository.
Local Deployment
Follow the usage instructions above to run the app locally.

Acknowledgements
The MNIST dataset: Yann LeCun's website
TensorFlow: TensorFlow
Streamlit: Streamlit
