# Patient Volume Forecasting for Aravind Eye Care, Madurai

This project was developed during a hackathon organized by **Aravind Eye Care** in Madurai. It aims to forecast patient volume for the next two months using two years of historical data, helping optimize operational planning, staffing, and resource allocation at the hospital.

## 📁 Project Structure

- `main.ipynb`: Jupyter notebook containing preprocessing, feature engineering, and forecasting logic.
- `forecasting_train.csv`: Historical patient volume data from Aravind Eye Care.
- `government holidays.csv`: Public holiday calendar for Tamil Nadu, manually created using official government data.

## 🧰 Libraries Used

- `pandas`: Data manipulation
- `numpy`: Numerical operations
- `matplotlib`: Visualizations
- `datetime`: Handled via pandas

## 🔍 Features

- Parses and formats date columns for time series compatibility.
- Adds meaningful temporal features such as day-of-week.
- Incorporates holiday-based data to improve model performance.
- Forecasts patient counts for two months into the future based on past trends.

## 🏥 Use Case

- **Organization**: Aravind Eye Care, Madurai
- **Context**: Hackathon project
- **Objective**: Predict outpatient footfall
- **Benefit**: Enables better preparation and planning across departments

## 📊 Data Notes

- The `government holidays.csv` file was created using publicly available data from **Tamil Nadu government websites**.
- This data helps the model account for fluctuations in patient volume due to national and state holidays.

## 🚀 How to Run

1. Clone the repository or download the notebook and datasets.
2. Install the required packages:
    ```bash
    pip install pandas numpy matplotlib
    ```
3. Open the notebook:
    ```bash
    jupyter notebook main.ipynb
    ```
4. Execute all cells to process the data and generate the forecast.

## 📌 Notes

- File paths are currently hardcoded for a local Windows environment (e.g., `D:\\auro\\...`). Update them to match your system.
- Further enhancements can include advanced time series models (e.g., Prophet, ARIMA, LSTM) and evaluation metrics.

## 📬 Contact

For questions or collaboration, feel free to open an issue or create a pull request.

---
