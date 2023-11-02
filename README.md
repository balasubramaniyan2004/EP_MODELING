

# Earthquake Prediction with Machine Learning

## Table of Contents
- [Introduction](#introduction)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Dataset](#dataset)
- [Code Structure](#code-structure)
- [License](#license)

## Introduction

This project uses Python machine learning models to predict the probability of earthquakes in a specific geographic region. The code provided in this repository demonstrates how to preprocess seismic and environmental data, train a prediction model, and make earthquake probability estimates.

## Dependencies

To run this code, you will need the following dependencies:

- Python (>= 3.6)
- NumPy
- pandas
- Scikit-learn
- Matplotlib (for data visualization)
- Jupyter Notebook (optional, for running the provided notebooks)

You can install the Python libraries using pip:

```bash
pip install -r requirements.txt
```

The `requirements.txt` file lists the necessary libraries and their versions.

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/hanifa2074/EP_MODEL.git
```

2. Change your current working directory to the project's root folder:

```bash
cd EP_MODEL.git
```

3. Install the required dependencies (as mentioned in the "Dependencies" section).

## Getting Started

1. Obtain the earthquake prediction dataset. This dataset should include seismic, geological, and environmental data related to earthquake occurrences.

2. Place the dataset files in the project directory.

## Usage

1. Open a terminal or command prompt.

2. Navigate to the project's root directory:

```bash
cd path/to/EP_MODEL.git
```

3. Run the provided Jupyter Notebook or Python script to perform earthquake prediction tasks. Use the code as a reference to customize the prediction model based on your dataset and requirements.

To run a Jupyter Notebook:

```bash
jupyter notebook earthquake_prediction.ipynb
```

To run a Python script:

```bash
python earthquake_prediction.py
```

4. Follow the instructions and code within the notebook or script to preprocess the data, train a machine learning model, and make earthquake probability predictions.

## Dataset

The dataset used in this project should include the following types of data:

- Seismic data: Earthquake occurrence records, location, magnitude, depth, and time.
- Geological data: Information about geological features, fault lines, and tectonic plate boundaries.
- Environmental data: Data on factors like temperature, pressure, and rainfall that may influence seismic activity.

Please ensure your dataset is in a suitable format and placed in the project directory.

The DATASET USED IN THE PROJECT : https://www.kaggle.com/datasets/usgs/earthquake-database


The National Earthquake Information Center (NEIC) determines the location and size of all significant earthquakes that occur worldwide and disseminates this information immediately to national and international agencies, scientists, critical facilities, and the general public. The NEIC compiles and provides to scientists and to the public an extensive seismic database that serves as a foundation for scientific research through the operation of modern digital national and global seismograph networks and cooperative international agreements. The NEIC is the national data center and archive for earthquake information.

## Code Structure

- `earthquake_prediction.ipynb`: A Jupyter Notebook containing code for data preprocessing, model training, and prediction.
- `earthquake_prediction.py`: A Python script equivalent to the Jupyter Notebook for non-notebook environments.
- `data/`: A directory where you can place your earthquake dataset files.
- `requirements.txt`: A file listing Python library dependencies.

## License

This project is licensed under the MIT License. For details, see the [LICENSE](LICENSE) file.

Feel free to adapt and modify this README template to suit your specific project's requirements. A well-structured README file helps users understand how to run your earthquake prediction code and its dependencies.
