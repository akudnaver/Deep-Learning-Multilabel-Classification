# Movie Genre Prediction Using Multilabel Classification

This repository contains a project for predicting movie genres using a multilabel classification approach. The project employs machine learning techniques to classify movies into multiple genres based on their features.

## Project Overview

The goal of this project is to predict movie genres from a given dataset of movie features. Since movies often belong to multiple genres, a multilabel classification approach is used to handle this problem. The model is built using Scikit-learn and Python.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Multilabel Classification:** Classifies movies into multiple genres.
- **Model Training:** Utilizes machine learning algorithms for model training and evaluation.
- **Evaluation Metrics:** Provides detailed metrics for model performance.

## Technologies Used

- **Python:** Programming language used for development.
- **Scikit-learn:** Machine learning library used for implementing classification algorithms.
- **Pandas:** Data manipulation library for handling the dataset.
- **NumPy:** Library for numerical operations.

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/movie-genre-prediction.git
   cd movie-genre-prediction
   ```

2. **Create and Activate a Virtual Environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Prepare the Data:**
   - Ensure your dataset is in the `data/` directory. The dataset should be in CSV format with features and genre labels.

2. **Train the Model:**

   ```bash
   python train_model.py
   ```

   This script will train the multilabel classification model using the provided dataset.

3. **Make Predictions:**

   ```bash
   python predict_genre.py --input <path_to_input_file>
   ```

   Replace `<path_to_input_file>` with the path to a CSV file containing movie features for which you want to predict genres.

4. **Evaluate the Model:**

   ```bash
   python evaluate_model.py
   ```

   This script will provide evaluation metrics for the trained model.

## Results

The multilabel classification model achieves an F1-score of X% on the test dataset, demonstrating its effectiveness in predicting multiple genres for movies. Detailed evaluation metrics, including precision, recall, and F1-score, are available in the `results/` directory.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

**Note:** Replace placeholders such as `https://github.com/your-username/movie-genre-prediction.git` with your actual repository link and `X%` with your model's actual performance metrics. Adjust the instructions and script names if they differ in your project.
