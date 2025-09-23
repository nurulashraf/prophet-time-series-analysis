# Time Series Analysis using Prophet

Time-series forecasting using Facebook’s Prophet: loading data, detecting trends & seasonality, fitting a Prophet model, evaluating performance, and visualising predictions and forecast components.

---

## Project Structure

- `notebooks/` – Jupyter Notebooks for data analysis, model training and evaluation  
- `requirements.txt` – Python libraries needed to run the project  
- `LICENSE` – MIT Licence for this project  
- `README.md` – this file with overview and instructions

---

## Features

- Import and preprocess time-series data.  
- Detect trend, seasonality, holiday effects.  
- Fit forecasting model using Facebook’s Prophet.  
- Forecast future values and generate forecast components.  
- Evaluate model performance (error metrics, cross-validation if applicable).  
- Visualise results (forecast vs history, components: trend, weekly/annual seasonality etc.).

---

## Tools & Libraries

- **Python** (>=3.x) - main programming language 
- **pandas** - data loading, manipulation 
- **numpy** - numerical operations 
- **fbprophet** (or **prophet**) - forecasting model library by Facebook 
- **jupyter / jupyter-lab** - interactive notebooks environment 

---

## How to Use

1. **Clone the repository**

   ```bash
   git clone https://github.com/nurulashraf/prophet-time-series-analysis.git
   cd prophet-time-series-analysis
    ````

2. **Set up the environment**

   It’s recommended to use a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate   # on Linux / macOS
   # or on Windows: venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Open notebook**

   Launch Jupyter:

   ```bash
   jupyter notebook
   ```

   or

   ```bash
   jupyter lab
   ```

   Then open the notebook in the `notebooks/` folder.

5. **Adjust data / parameters as needed**

   * If you have your own time-series data, place it in or point to it in the data-loading notebook.
   * Modify forecasting horizon, seasonality parameters, holiday data etc.
   * Compute evaluation metrics relevant to your use case (MAE, RMSE, MAPE etc.).

6. **View results**

   You will get forecasts, plots of trend & seasonality, residuals etc. Use them to assess if the model is performing well or if more tuning is needed.

---

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.



