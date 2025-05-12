# 🌍 Earthquakes App: Interactive Seismic Activity Dashboard

Welcome to the **Earthquakes App**, an advanced and interactive dashboard for the exploration and analysis of global seismic activity. Built with [Streamlit](https://streamlit.io/) and [Plotly](https://plotly.com/python/), this application empowers users to visualize, filter, and analyze earthquake data with ease and depth.

![Earthquakes App img](img/image.jpg)

---

## 🚀 Features

- **Dynamic Filtering:**  
  Filter seismic events by date, magnitude, depth, event type, and region using an intuitive sidebar.

- **Comprehensive Visualizations:**  
  - **General Summary:** Key metrics, magnitude and depth distributions, and top regions.
  - **Geographic Analysis:** Interactive maps (scatter, heatmap, and cluster analysis) to explore spatial patterns.
  - **Temporal Analysis:** Daily, weekly, and hourly trends with advanced heatmaps and trend detection.
  - **Advanced Analysis:** Correlation matrices, regional magnitude analysis, and custom variable comparisons.

- **Cluster Detection:**  
  Identify and visualize spatial clusters of seismic events using the DBSCAN algorithm.

- **Data Export:**  
  Download filtered datasets for further offline analysis.

- **User-Friendly Interface:**  
  Responsive layout, expandable data tables, and contextual tooltips for enhanced usability.

---

## 🛠️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/earthquakes_app.git
   cd earthquakes_app
   ```

2. **Install dependencies:**
   ```bash
   pip install streamlit pandas numpy plotly matplotlib scikit-learn
   ```

3. **Prepare the data:**
   - Place your earthquake data file as `data/all_month.csv` (USGS format recommended).

---

## 💡 Usage

1. **Run the app:**
   ```bash
   streamlit run app.py
   ```

2. **Open your browser:**  
   Visit the local URL provided by Streamlit (usually [http://localhost:8501](http://localhost:8501)).

3. **Explore:**  
   - Use the sidebar to filter and customize your analysis.
   - Navigate through the tabs for different analytical perspectives.
   - Download filtered data as CSV for further research.

---

## 📊 Dashboard Overview

### Sidebar Filters
- **Date Range:** Select the period of interest.
- **Magnitude & Depth:** Focus on specific event intensities and depths.
- **Event Type & Region:** Drill down by event classification and location.

### Main Tabs
- **General Summary:**  
  Key statistics, distributions, and top regions.

- **Geographic Analysis:**  
  - **Event Map:** Interactive global scatter plot.
  - **Heat Map:** Density visualization of seismic activity.
  - **Cluster Analysis:** Identify and analyze spatial clusters.

- **Temporal Analysis:**  
  - **Daily, Weekly, Hourly Patterns:** Trends and heatmaps for temporal insights.

- **Advanced Analysis:**  
  - **Correlations:** Explore relationships between variables.
  - **Magnitude by Region:** Regional breakdowns.
  - **Comparisons:** Custom scatter plots and category statistics.

---

## 📁 Data Requirements

- **Input File:**  
  `data/all_month.csv`  
  The CSV should include columns such as `time`, `latitude`, `longitude`, `mag`, `depth`, `place`, `type`, etc.  
  [USGS Earthquake Catalog](https://earthquake.usgs.gov/earthquakes/search/) is a recommended data source.

---

## 🧩 Technologies Used

- [Streamlit](https://streamlit.io/) - Interactive web app framework
- [Plotly Express & Graph Objects](https://plotly.com/python/) - Advanced data visualization
- [Pandas](https://pandas.pydata.org/) & [NumPy](https://numpy.org/) - Data manipulation
- [scikit-learn](https://scikit-learn.org/) - Clustering (DBSCAN)
- [Matplotlib](https://matplotlib.org/) - Additional plotting

---

## 📝 Customization

- **Data Source:**  
  Replace `data/all_month.csv` with your own dataset for custom analysis.

- **Visualization:**  
  Modify or extend the tabs and charts in `app.py` to fit your research needs.

---

## 🧑‍💻 Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements, bug fixes, or new features.

---

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 🙌 Acknowledgements

- USGS for open earthquake data.
- Streamlit and Plotly communities for their excellent tools and documentation.

---

**Developed with passion for data and the planet.**

---