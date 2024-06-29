# Financial Prediction Projects

This repository contains two distinct machine learning projects focused on financial prediction tasks: predicting company bankruptcy and forecasting company profit. Each project is organized in its own directory with separate datasets, notebooks, and results.

## Features

1. **Bankruptcy Prediction Project**:
    - Uses logistic regression to predict whether a company will go bankrupt based on various financial indicators.
    - Includes data preprocessing steps such as handling missing values and feature scaling.
    - Provides model evaluation metrics like accuracy.

2. **Profit Prediction Project**:
    - Applies linear regression to forecast company profit using R&D spend, administration costs, marketing spend, and state information.
    - Converts categorical variables to numerical form and normalizes data.
    - Provides model evaluation metrics like R² score and visualizations of actual vs. predicted profits.

## Technologies Used

- **Python**: Main programming language for the projects.
- **Pandas**: For data manipulation and preprocessing.
- **scikit-learn**: For building and evaluating machine learning models.
- **Matplotlib & Seaborn**: For data visualization and plotting.

## Getting Started

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/your-username/financial-prediction-projects.git
    cd financial-prediction-projects
    ```

2. **Set Up Environment**:
    Create and activate a virtual environment (optional but recommended):
    ```sh
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. **Install Dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

## Project Structure

- **bankruptcy_prediction/**: Directory containing the bankruptcy prediction project.
  - `data/`: Directory for the dataset.
    - `bank.csv`: Dataset for bankruptcy prediction.
  - `bankruptcy_prediction.ipynb`: Notebook for analysis and model training.
- **profit_prediction/**: Directory containing the profit prediction project.
  - `data/`: Directory for the dataset.
    - `data.csv`: Dataset for profit prediction.
  - `profit_prediction.ipynb`: Notebook for analysis and model training.
- **requirements.txt**: File listing the required Python packages.

## Usage

### Bankruptcy Prediction

1. Navigate to the bankruptcy prediction directory:
    ```sh
    cd bankruptcy_prediction
    ```
2. Place the `bank.csv` dataset in the `data/` directory.
3. Open the Jupyter notebook:
    ```sh
    jupyter notebook bankruptcy_prediction.ipynb
    ```
4. Run the notebook cells to execute the analysis and model training.

### Profit Prediction

1. Navigate to the profit prediction directory:
    ```sh
    cd profit_prediction
    ```
2. Place the `data.csv` dataset in the `data/` directory.
3. Open the Jupyter notebook:
    ```sh
    jupyter notebook profit_prediction.ipynb
    ```
4. Run the notebook cells to execute the analysis and model training.

## Results

- **Bankruptcy Prediction**: Achieves an accuracy of ~X% using logistic regression.
- **Profit Prediction**: Achieves an R² score of ~Y% using linear regression.

## Contributing

We welcome contributions to enhance these projects. Feel free to submit pull requests or open issues with suggestions and improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [scikit-learn](https://scikit-learn.org/)
- [pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)

