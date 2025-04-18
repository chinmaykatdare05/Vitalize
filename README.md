# Vitalize

This project provides a streamlined way to analyze and visualize health data exported from **Apple Health** and **Google Fit**. It parses XML data exported from Apple Health, extracts key health metrics, and generates insightful visualizations using **Streamlit** and **Plotly**.

## Deployment

You can access the deployed Streamlit app using the following link:

[Vitalize](https://vitalize.streamlit.app/)

## Key Features

- **Data Parsing:**
  - Efficiently parses Apple Health XML files to extract health metrics.
  - Cleans and processes the data into a structured Pandas DataFrame.
- **Statistical Analysis:**
  - Aggregates daily, weekly, and monthly trends.
  - Provides correlation analysis between different health parameters.

## Getting the Input Files

### Exporting Data from Apple Health (iOS)

1. Open the **Apple Health** app on your iPhone.
2. Tap on your profile picture in the top right.
3. Select **Export All Health Data**.
4. A ZIP file will be generated and shared via **AirDrop, Mail, or any cloud storage**.
5. Extract the ZIP file and locate the **`export.xml`** file.

### Exporting Data from Google Fit (Android)

1. Visit [Google Takeout](https://takeout.google.com/).
2. Sign in with your Google account.
3. Select **Google Fit** and choose **Daily activity metrics**.
4. Click **Create Export** and download the ZIP file.
5. Extract the ZIP and locate the **CSV files** containing your health data.

## Installation & Setup

### Prerequisites

Ensure you have **Python 3.8+** installed.

#### Install Required Libraries

```bash
pip install -r requirements.txt
```

#### Running the Streamlit App

```bash
streamlit run app.py
```

## Usage Guide

### Uploading and Parsing Data

1. **Launch the Streamlit app.**
2. **Upload the exported XML file** from Apple Health.
3. The tool will automatically parse and process the data.

### Generating Insights

- The app dynamically generates **interactive** visualizations.
- Helps users **track health trends**, identify patterns, and make informed decisions.

## Future Enhancements

- Time-based analysis for deeper trend detection.
- Integration with **real-time APIs** for live tracking.

## Disclaimer

This project is **not affiliated with Apple or Google**. It is designed for **personal analytics and research** purposes only. Use this tool responsibly to track and improve your health.

**Happy Health Tracking!**
