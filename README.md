# **India Air Quality Analysis**

## **Overview**
This project analyzes real-time air quality data for India using the OpenWeatherMap API. The dataset includes key pollutants such as PM2.5, NO2, CO, and SO2. The analysis involves time-series trends, correlation analysis, anomaly detection, and rolling averages to identify pollution patterns.

## **Features**
- **Real-time Data Fetching**: Collects air pollution data via API.
- **Data Preprocessing**: Cleans and formats data for analysis.
- **Exploratory Data Analysis (EDA)**: Visualizes pollutant trends.
- **Anomaly Detection**: Identifies pollution spikes.
- **Rolling Averages**: Analyzes long-term trends.

## **Dataset**
The project fetches and stores real-time air quality data in a CSV file (`india_air_quality.csv`).

## **Technologies Used**
- **Python** (Pandas, Matplotlib, Seaborn, Requests)
- **Jupyter Notebook** for analysis
- **OpenWeatherMap API** for data retrieval

## **Installation & Setup**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/india-air-quality.git
   cd india-air-quality
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script to fetch data:
   ```bash
   python fetch_india_air_quality.py
   ```
4. Run the analysis notebook:
   ```bash
   jupyter notebook air_quality_analysis.ipynb
   ```

## **Deployment**
To deploy as a web-based analysis tool:
- **Google Colab**: Upload the notebook and execute in the cloud.
- **Streamlit**: Convert the script into an interactive web app.
- **Flask/Django**: Create an API to serve air quality data.
- **Dash (Plotly)**: Build an interactive dashboard.

## **License**
This project is licensed under the MIT License.

## **Contributing**
Pull requests are welcome! For major changes, please open an issue first to discuss.

## **Contact**
For questions or collaboration, contact **Ritalee Monde** at **pamsmonde@gmail.com**.
