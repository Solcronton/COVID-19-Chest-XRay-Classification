# COVID-19 Chest X-Ray Classification

## About the Project

This project uses Deep Learning and Convolutional Neural Networks (CNN) to classify chest X-ray images into two categories: **NORMAL** and **PNEUMONIA**.

The model learns image features from chest X-ray images through training and uses them to classify new images.

## Dataset

**COVID-19 X-ray Dataset (Train & Test Sets)**

The dataset contains chest X-ray images organized into training and testing directories.

**Dataset Categories:**
- NORMAL
- PNEUMONIA

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Deep Learning
- Convolutional Neural Networks (CNN)

## Project Workflow

1. Load the chest X-ray dataset.
2. Perform image preprocessing.
3. Prepare training and testing datasets.
4. Build a Convolutional Neural Network (CNN).
5. Train the model using training images.
6. Evaluate the trained model using test images.
7. Predict the class of new chest X-ray images.

## Model Architecture

The project uses a Convolutional Neural Network (CNN) for image classification.

CNN automatically extracts important visual features from chest X-ray images using convolutional and pooling layers and uses these features to classify images.

The trained model is saved in the `.keras` format.

**Saved Model:** `pneumonia_cnn_model.keras`

## Project Structure

```text
COVID-19-Chest-XRay-Classification/
│
├── train/
│   ├── NORMAL/
│   └── PNEUMONIA/
│
├── test/
│   ├── NORMAL/
│   └── PNEUMONIA/
│
├── Notebook.ipynb
├── pneumonia_cnn_model.keras
└── README.md
```

## Installation

**1. Clone the repository**

```bash
git clone https://github.com/Solcronton/COVID-19-Chest-XRay-Classification.git
```

**2. Navigate to the project directory**

```bash
cd COVID-19-Chest-XRay-Classification
```

**3. Install the required libraries**

```bash
pip install tensorflow numpy pandas matplotlib opencv-python
```

## How to Run

1. Open the project folder in VS Code or Jupyter Notebook.
2. Open `Notebook.ipynb`.
3. Install the required dependencies.
4. Execute the notebook cells sequentially.
5. Train and evaluate the CNN model.
6. Use the trained model to classify new chest X-ray images.

## Key Features

- Chest X-ray image preprocessing.
- CNN-based image classification.
- Training and testing using separate datasets.
- Saving the trained model in Keras format.
- Prediction on new chest X-ray images.

## Applications

- Medical image classification research.
- Deep Learning-based chest X-ray analysis.
- Understanding CNN-based image classification.
- Educational experimentation with medical imaging datasets.

## Future Improvements

- Improve model performance through hyperparameter tuning.
- Experiment with transfer learning models such as VGG16 and ResNet50.
- Add model evaluation metrics such as precision, recall, F1-score and confusion matrix.
- Develop a simple web interface for image classification.

## Disclaimer

This project is developed for educational and research purposes only. It is not a medically validated diagnostic system and should not be used as a substitute for professional medical advice or diagnosis.

## Author

**Harshith Kumar Chitluri**

- GitHub: [Solcronton](https://github.com/Solcronton)
- LinkedIn: [Harshith Chitluri](https://linkedin.com/in/harshith-chitluri)