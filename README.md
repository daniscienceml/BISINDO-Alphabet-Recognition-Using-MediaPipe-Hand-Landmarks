# BISINDO Alphabet Recognition Using MediaPipe Hand Landmarks

A complete deep learning pipeline for Indonesian Sign Language (BISINDO) alphabet recognition using MediaPipe hand landmark coordinates.

## Features

- Data Exploration & Visualization
- Feature Analysis
- PCA Visualization
- Deep Neural Network Classification
- Confusion Matrix
- Classification Report
- SHAP Explainability
- MLflow Experiment Tracking
- Gradio Web Application

## Dataset

The project uses MediaPipe hand landmark coordinates extracted from BISINDO alphabet gestures (A-Z).

Each sample contains:

- 21 hand landmarks
- X, Y, Z coordinates
- Alphabet label

## Model

Architecture:

- Dense(1024)
- Dense(512)
- Dense(256)
- Dense(128)
- Softmax Output

## Results

Achieved high classification accuracy on the BISINDO validation dataset using landmark-based deep learning.

## Author

Muhammad Danyal Malik

### Connect

- LinkedIn: https://www.linkedin.com/in/danyal-ai/
- GitHub: https://github.com/daniscienceml
- Google Scholar: https://scholar.google.com/citations?user=ngRPipAAAAAJ&hl=en
- Email: dani.ai.practitioner@gmail.com

## License

This project is intended for educational and research purposes.
