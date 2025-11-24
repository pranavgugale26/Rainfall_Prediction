# 🌧️Rainfall Prediction

A Google Colab project analyzing Indian city weather data to understand how temperature, humidity, wind speed, and cloud cover impact rainfall. Includes dataset, Colab notebook, visualizations, correlation heatmaps, and insights into rainfall patterns.


## 📂 Repository Structure

```

📁 Rainfall-Prediction/

│

├── rainfall_prediction.ipynb     # Main Google Colab Notebook (analysis, visualizations)

├── rainfall_data.csv             # Dataset used in the notebook

├── README.md                     # This file

├── LICENSE                       # MIT License

└── screenshots/                  # Extracted notebook output images

```

## 🧾 Dataset

- **Path:** `/mnt/data/rainfall_data(1).csv`

- **Columns:** `City`, `Temperature`, `Humidity`, `Wind_Speed`, `Cloud_Cover`, `Rainfall_mm`


## 🧪 Notebook Contents

The notebook (`rainfall_prediction.ipynb`) contains:

- Data loading and cleaning
- Exploratory Data Analysis (EDA)
- Visualizations: histograms, scatter plots, and correlation heatmap
- Basic interpretation and insights


## 🖼️ Screenshots

### Snapshot

![](/mnt/data/screenshots/shot_1.png)

### Snapshot

![](/mnt/data/screenshots/shot_2.png)


## 🚀 How to Run Locally

Follow these steps to run the notebook on your machine or in a cloud environment.


### 1️⃣ Clone the repository

```bash

git clone https://github.com/your-username/your-repo.git

cd your-repo

```

### 2️⃣ Setup environment

Make sure you have Python 3.x installed. Recommended to use a virtual environment.

```bash

python -m venv venv

source venv/bin/activate  # (Linux / macOS)

venv\Scripts\activate     # (Windows)

pip install -r requirements.txt  # or: pip install notebook pandas matplotlib seaborn scikit-learn

```


### 3️⃣ Open the notebook

```bash

jupyter notebook rainfall_prediction.ipynb

```


### 4️⃣ Run the cells

In Jupyter: `Kernel → Restart & Run All`.


## 🧠 What You’ll Learn

- How rainfall varies across cities
- Correlation between humidity / cloud cover and rainfall
- How to create and interpret basic visualizations


## ⭐ Future Improvements

- Add predictive machine learning model (regression/classification)
- Create a Streamlit dashboard for interactive exploration
- Add live weather API integration to fetch up-to-date data


## 🤝 Contributing

Contributions are welcome! Suggestions:

- Add better visualizations or EDA
- Build predictive models and report metrics
- Improve data cleaning and add more cities


## 📝 License

This project is licensed under the MIT License - see the `LICENSE` file for details.


## 📎 Useful paths (local)

- Notebook: `/mnt/data/rainfall_prediction.ipynb`

- Dataset: `/mnt/data/rainfall_data(1).csv`

- Screenshots folder: `/mnt/data/screenshots/`
