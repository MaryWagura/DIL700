# DIL700 - Deep Learning Coursework

This repository contains the laboratory exercises, coding assignments, and the final semester project for the **DIL700: Deep Learning** course.

The goal of this repository is to document the journey from fundamental tensor manipulations to building and deploying complex neural network architectures.

## 📂 Repository Structure

The project is organized into the following directories:

- `Lab_Works/`: Weekly laboratory assignments and coding tasks.
- `Final_Project/`: The capstone project for the semester.
- `Resources/`: Supplementary datasets or notes (if applicable).

## 🚀 Getting Started

To run the notebooks in this repository, you will need a Python environment configured with **TensorFlow** and **NumPy**.

### Prerequisites

* Python 3.8+
* Anaconda or Miniconda (Recommended)

### Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/marywagura/DIL700.git](https://github.com/marywagura/DIL700.git)
    cd DIL700
    ```

2.  **Create a Virtual Environment**
    It is recommended to use a fresh environment to avoid conflicts.
    ```bash
    conda create -n dil700 python=3.9
    conda activate dil700
    ```

3.  **Install Dependencies**
    Note: It is often safer to install TensorFlow via pip inside a Conda environment.
    ```bash
    pip install tensorflow numpy matplotlib pandas jupyterlab
    ```

4.  **Launch Jupyter**
    ```bash
    jupyter lab
    ```

## 🧪 Lab Assignments

### Task 1: Tensor Manipulations
**Focus:** NumPy Fundamentals
- Understanding Scalars, Vectors, and Matrices.
- Tensor operations: Reshaping, Slicing, Broadcasting.
- Mathematical aggregations (Sum, Mean, Dot Product).

### Task 2: Neural Network Foundations
**Focus:** Keras & TensorFlow Basics
- Building a Multi-Layer Perceptron (MLP) using the Keras Sequential API.
- Understanding Layers: `Dense`, `Flatten`.
- Compiling models with Optimizers (`Adam`) and Loss Functions.

### Task 3: Classification Tasks
**Focus:** End-to-End Model Training
- **Part A (Computer Vision):** Handwritten Digit Classification using the **MNIST** dataset.
- **Part B (NLP):** Sentiment Analysis using the **IMDb** movie reviews dataset.
- Visualizing training performance (Loss/Accuracy curves) to detect overfitting.

## 🏆 Final Project
*(To be updated)*
The final project involves applying deep learning techniques to solve a specific real-world problem.
* **Topic:** [TBD]
* **Status:** In Progress / Not Started

## 🛠 Technologies Used
* **Languages:** Python
* **Libraries:** TensorFlow 2.x, Keras, NumPy, Matplotlib, Pandas
* **Tools:** Jupyter Notebooks, Anaconda

---
*Author: [Your Name]*
*Course: DIL700*
