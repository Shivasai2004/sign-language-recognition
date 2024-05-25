# Indian Sign Language Recognition

This repository contains a project for recognizing Indian Sign Language using deep learning techniques. The project includes various scripts and models to collect data, train the model, and deploy a real-time sign language recognition system.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Models](#models)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Shivasai2004/sign-language-recognition.git
Change into the project directory:
bash
Copy code
cd sign-language-recognition
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Usage
Data Collection
To collect data for training the model, use collectdata.py. This script captures images from your webcam and stores them in the appropriate folders.

bash
Copy code
python collectdata.py
Show the sign in front of the camera and press the corresponding alphabet key. The script will save the images in grayscale format (48x48 size) in the respective alphabet folder.

Train the Model
The training process is documented in the model.ipynb notebook. Open this file in Jupyter Notebook to train your model.

Split the Dataset
To split the dataset into training and testing sets, use split.py.

bash
Copy code
python split.py
Real-Time Detection
To run the real-time sign language detection, use detect.py.

bash
Copy code
python detect.py
Web Application
To deploy the web application using Streamlit, run app.py.

bash
Copy code
streamlit run app.py
Project Structure
perl
Copy code
sign-language-recognition/
│
├── models/
│   ├── model1.h5
│   ├── model2.h5
│   └── ...
│
├── app.py
├── collectdata.py
├── detect.py
├── model.ipynb
├── split.py
├── requirements.txt
└── README.md
models/: Contains the pre-trained model files in .h5 format.
app.py: Streamlit-based UI code for deploying the web application.
collectdata.py: Script to collect training data using webcam.
detect.py: Script for real-time sign language detection.
model.ipynb: Jupyter Notebook containing the deep learning model and training process.
split.py: Script to split the dataset into training and testing sets.
requirements.txt: List of dependencies required to run the project.
README.md: Project documentation.
Models
The models folder contains various pre-trained models in .h5 format. You can use these models for prediction or further training.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
This project was developed by Shivasai2004. Special thanks to the contributors and the open-source community for their support.

For more information, visit the GitHub repository.

css
Copy code

This README file provides a comprehensive overview of the project, instructions for installation and usage, a detailed project structure, and other relevant information.




