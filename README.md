# Metro Passenger Data Analysis and Prediction

This project analyzes metro passenger data obtained from the **IBB Open Data Portal** (Istanbul Metropolitan Municipality). The project includes cleaning and processing the dataset, exploratory data analysis, visualization of trends, and applying a prediction model to forecast passenger counts.

---

## Dataset

The dataset contains information about metro passenger counts in Istanbul. Key features include:

- **passage_cnt**: Number of passages recorded.
- **passanger_cnt**: Number of passengers.
- **transaction_month**: Month of the transaction.
- **line**: Name of the metro line.
- **age**: Passenger age group.
- **age_numeric**: Numeric representation of age group.
- **line_numeric**: Numeric representation of metro lines.

The dataset was sourced from the **IBB Open Data Portal**.

---

## Features of the Project

1. **Data Cleaning**:
   - Removed irrelevant columns and handled missing data.

2. **Exploratory Data Analysis**:
   - Visualized passenger counts per metro line.
   - Analyzed passenger distribution by age group.
   - Identified monthly trends in passenger counts.

3. **Prediction Model**:
   - Built a linear regression model to predict passenger counts based on key features such as passage count, transaction month, and numeric representations of age and metro lines.
   - Achieved a strong performance with:
     - **Mean Squared Error (MSE)**: 20,664.68
     - **R² Score**: 0.997

4. **Visualizations**:
   - Trends and distributions were visualized using bar charts and line plots.
   - Predictions were compared to actual values using a scatter plot.

---

## How to Use

### Clone the Repository:

```bash
git clone https://github.com/your-username/metro-passenger-analysis.git
cd metro-passenger-analysis
```

### Install Dependencies:
Make sure you have Python and the required libraries installed. Install dependencies using:

```bash
pip install -r requirements.txt
```

### Run the Script:

```bash
python analysis_and_prediction.py
```

### Output:

1. **Visualizations**:
   - Bar charts showing passenger counts by metro line and age group.
   - Line plot illustrating monthly trends in passenger counts.
   - Scatter plot comparing predicted vs actual passenger counts.

2. **Prediction Results**:
   - **Mean Squared Error (MSE)**: 20,664.68
   - **R² Score**: 0.997, indicating that the model explains 99.7% of the variance in passenger counts.

---

## Dependencies:

The project requires the following Python libraries:

- `pandas`
- `matplotlib`
- `scikit-learn`

You can install all dependencies with:

```bash
pip install -r requirements.txt
```

---

## Dataset Details:

The dataset used in this project was sourced from the **IBB Open Data Portal**, which provides open access to Istanbul's transportation and other municipal data. The dataset contains the following key features:

- **passage_cnt**: The number of recorded passages through metro turnstiles.
- **passanger_cnt**: The number of passengers recorded.
- **transaction_month**: The month when the transaction was recorded.
- **line**: The name of the metro line.
- **age**: The age group of passengers.
- **age_numeric**: A numeric representation of the age group.
- **line_numeric**: A numeric representation of metro lines for modeling purposes.

This dataset is valuable for analyzing passenger trends, forecasting demands, and gaining insights into metro usage patterns in Istanbul. You can explore more datasets on the [IBB Open Data Portal](https://data.ibb.gov.tr/).

---

## License:

This project is licensed under the MIT License. You are free to use, modify, and distribute this project as per the license terms.

---

## Contributing:

Contributions to this project are welcome! You can contribute by:

1. Reporting any issues or bugs you encounter.
2. Suggesting new features or improvements.
3. Submitting pull requests with fixes or enhancements.

To contribute:

- Fork the repository.
- Make your changes in a separate branch.
- Submit a pull request explaining your changes.

---

## Contact:

If you have questions, feedback, or suggestions, feel free to open an issue on this repository. We appreciate your input and collaboration!


