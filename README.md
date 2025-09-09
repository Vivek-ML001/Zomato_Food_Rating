# Zomato Food Rating

A machine learning project that predicts food ratings based on various features extracted from Zomato datasets. This repository aims to help restaurants and users understand factors contributing to ratings and offers insights using data-driven modeling.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Project Overview

This project leverages machine learning algorithms to predict restaurant ratings using data extracted from Zomato. It includes data preprocessing, exploratory data analysis (EDA), feature engineering, modeling, and evaluation steps. The goal is to improve understanding of rating factors and assist stakeholders in making informed decisions.

## Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA) visualizations
- Feature selection and engineering
- Multiple ML models (e.g., Linear Regression, Random Forest, XGBoost)
- Model evaluation metrics (accuracy, RMSE, etc.)
- Prediction and visualization of results

## Dataset

The dataset used in this project is sourced from [Zomato](https://www.zomato.com/). It contains information about restaurants, such as name, location, cuisines, average cost, votes, and ratings.

> **Note:** Refer to the [data](data/) directory for raw and processed datasets.

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Vivek-ML001/Zomato_Food_Rating.git
   cd Zomato_Food_Rating
   ```

2. **Create and activate a virtual environment (optional)**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the main script**
   ```bash
   python main.py
   ```

2. **Jupyter Notebook**
   - Open and run the notebooks in the [`notebooks/`](notebooks/) directory for step-by-step analysis.

3. **Model Training and Evaluation**
   - Customize parameters in the config files or scripts as needed.

## Project Structure

```
Zomato_Food_Rating/
│
├── data/                 # Datasets (raw and processed)
├── notebooks/            # Jupyter notebooks for EDA and modeling
├── src/                  # Source code (data processing, modeling)
├── requirements.txt      # Project dependencies
├── main.py               # Main script to run the pipeline
├── README.md             # Project documentation
└── ...
```

## Results

- Achieved high accuracy in rating prediction using ensemble models.
- Visualizations highlight critical factors influencing restaurant ratings.

> For detailed results and analysis, see [`notebooks/results.ipynb`](notebooks/results.ipynb).

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or suggestions, please contact:
- [Vivek-ML001 on GitHub](https://github.com/Vivek-ML001)

---

**Star this repo** if you find it useful!
