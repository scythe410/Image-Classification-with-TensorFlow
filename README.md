# Machine Learning Notebooks - Focussed on CNNs 📓🤖

Welcome to this repository of Jupyter Notebooks where I explore and document key concepts, techniques, and models in **Machine Learning** and **Artificial Intelligence**. Each notebook is designed to be beginner-friendly yet informative, covering both theory and implementation.

## 📁 Current Notebooks

1. **Foundations of Machine Learning**
- `foundations.ipynb`: A practical walkthrough explaining how machine learning models are trained, including data splitting, model fitting, loss calculation, and optimization.

2. **Computer Vision Basics**
- `0 neural networks.ipynb`: Introduction to neural networks
- `1 model.ipynb`: Building a neural network to classify images of clothing using Fashion MNIST
- `2 callback model.ipynb`: Implementation of callbacks for model training optimization
- `3 updating model.ipynb`: Exploring model architecture modifications and their impacts

3. **Convolutional Neural Networks**
- `convolutions and pooling.ipynb`: Deep dive into CNN fundamentals

4. **Training in Cloud vs Local**
- `model to run in vertex ai.ipynb`: Training a CNN model in Google Cloud Vertex AI
- `model to run locally.ipynb`: Local implementation of the same CNN model

5. **Complex Image Classification**
- `horse or human - local.ipynb`: Training a CNN to distinguish between horses and humans (1283 images, 300x300 resolution)
- `horse or human - vertex ai.ipynb`: Cloud-based implementation of the horse/human classifier

## 🧮 Key Topics Covered

- Neural Network Fundamentals
- Computer Vision & Image Classification
- Convolutional Neural Networks (CNNs)
- Model Training and Evaluation
- Cloud vs Local Development
- Callbacks and Model Optimization
- Data Preprocessing and Normalization
- Model Architecture Design
- Complex Image Classification

## 🛠 Requirements

To run the notebooks locally, you need:

- Python 3.10 or less because of TensorFlow compatibility
- Jupyter Notebook or JupyterLab
- Key libraries:
  ```bash
  pip install tensorflow tensorflow-datasets numpy matplotlib
  pip install google-cloud-aiplatform  # For Vertex AI notebooks
  ```

## 🏗 Project Structure

- Each section is organized in numbered folders
- Includes both local and cloud (Vertex AI) implementations
- Supporting files (images, models) are included where needed
- Clear progression from basic concepts to complex applications
