# Train Wheel and Track Fault Detector

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A project dedicated to automating railway safety inspections using deep learning. The system uses computer vision to identify potential hazards on both tracks and wheels, which are typically checked manually.

---

## Features

* **Track Fault Classifier:** A CNN model trained to classify images of railway tracks as either **defective** or **non-defective**.
* **Wheel Defect Detector:** A YOLOv8 object detection model trained to identify and locate specific defects on train wheels.

---

## Tech Stack

* Python
* TensorFlow & Keras
* Ultralytics (YOLOv8)
* OpenCV
* Jupyter Notebook

---

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* Python 3.8+
* Git

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/](https://github.com/PI-Prasaad-Krishna/train-inspector.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd train-inspector
    ```
3.  **Create and activate a virtual environment:**
    ```bash
    # Create the environment
    python -m venv venv

    # Activate on Windows
    .\venv\Scripts\activate

    # Activate on macOS/Linux
    source venv/bin/activate
    ```
4.  **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

---

## Usage

*(Detailed instructions on how to run the training scripts and use the models for inference will be added here later.)*

---

## Datasets

This project utilizes the following datasets from Kaggle:

1.  **Railway Track Fault Detection:** [Link to Dataset](https://www.kaggle.com/datasets/salmaneunus/railway-track-fault-detection)
2.  **Wheel Fault Detection:** [Link to Dataset](https://zenodo.org/records/13162335)

Please download the data and place it into the `datasets/processed/` directory according to the structure specified in the project.

---

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.