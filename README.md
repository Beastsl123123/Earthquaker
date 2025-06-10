from pathlib import Path

# Create the README content
readme_content = """
# Earthquake Data Viewer 🌍

A sleek and user-friendly Streamlit app to fetch, analyze, and visualize recent earthquake data from the USGS API. Select any date range to explore earthquake magnitudes, locations, and times, and download the data as CSV or styled Excel files.

---

## Features

- Fetch earthquake data from USGS within a custom date range  
- Display key statistics: total earthquakes, maximum magnitude, average magnitude  
- Interactive, styled data table highlighting magnitudes with colors  
- Downloadable CSV and formatted Excel spreadsheets  
- Responsive UI with minimalistic, macOS-like styling  
- Centered layout optimized for readability and user experience

---

## How to Run Locally

### Prerequisites

- Python 3.7 or higher  
- Recommended: Virtual environment to manage dependencies  

### Installation

1. Clone or download this repository.

2. Navigate into the project folder:

```bash
cd earthquake-data-viewer
