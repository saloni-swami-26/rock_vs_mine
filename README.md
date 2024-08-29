
# Rock vs Mine Classification Project

This project aims to classify objects as either a rock or a mine based on sonar data using machine learning techniques. The project uses a dataset where each instance represents a different object and the features represent various sonar frequencies. The goal is to build a classification model that can accurately differentiate between the two classes.

## Technologies Used

- **Python**: Programming language
- **Jupyter Notebook**: For interactive development and analysis
- **NumPy**: For numerical computations
- **Pandas**: For data manipulation and analysis
- **scikit-learn**: For machine learning model implementation

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/saloni-swami-26/rock_vs_mine
    cd rock_vs_mine
    ```

2. **Create a virtual environment (optional but recommended)**:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Jupyter Notebook**:

    ```bash
    jupyter notebook rock_vs_mine.ipynb
    ```

## Usage

- **Data Loading and Exploration**:
    - The dataset (`sonar_data.csv`) is loaded into a Pandas DataFrame.
    - The first few rows of the dataset are displayed to understand its structure.
    - Basic statistics of the dataset are generated.
    - The distribution of the target classes (Rock or Mine) is analyzed.

- **Data Preprocessing**:
    - Features and target variables are separated.
    - The dataset is split into training and test sets.

- **Model Training and Evaluation**:
    - A Logistic Regression model is trained on the training data.
    - The model's accuracy is evaluated on the test data.
    - The accuracy score is printed to assess the performance of the model.

## Project Structure

- `rock_vs_mine.ipynb`: Jupyter notebook containing the full project implementation.
- `rock_vs_mine.py`: Python script containing the core code extracted from the notebook.
- `requirements.txt`: List of dependencies required to run the project.

## Dataset

The dataset used in this project contains sonar readings that are used to classify objects as rocks or mines. It is structured as follows:

- **Features**: Various sonar frequencies.
- **Target**: Binary classification indicating whether the object is a rock (R) or a mine (M).

## License

This project is licensed under the MIT License - see the LICENSE file for details.
