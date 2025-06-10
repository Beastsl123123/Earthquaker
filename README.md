
# 🌍 Earthquake Data Viewer

An interactive Streamlit app that fetches and visualizes global earthquake data using the USGS API. Allows users to select a date range and view earthquakes with details like magnitude, location, coordinates, and time. You can also export the data to CSV or styled Excel formats.

---
GOTO: [DENO](http://localhost:8501/)

## 🚀 Features

- 🌐 Fetch real-time earthquake data from [USGS Earthquake API](https://earthquake.usgs.gov/)
- 📅 Select a date range with date pickers
- 📊 View key metrics: total quakes, max magnitude, and average magnitude
- 📋 Interactive table with styled magnitudes
- 📁 Download results as CSV or styled Excel
- 💻 Modern UI styled with custom CSS

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/earthquake-data-viewer.git
cd earthquake-data-viewer
```

### 2. Set Up a Virtual Environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the app locally:

```bash
streamlit run app.py
```

Then open the URL in your browser (usually `http://localhost:8501`).

---

## 📦 File Structure

```
earthquake-data-viewer/
├── app.py                # Main Streamlit app
├── requirements.txt      # Required Python packages
├── README.md             # Project info and instructions
```

---

## 📊 Example Output

- Clean and responsive UI
- Cards showing stats (Total Earthquakes, Max Magnitude, Avg Magnitude)
- Styled table with interactive data
- Download buttons for CSV and Excel

---

## 📎 Dependencies

- `streamlit`
- `requests`
- `pandas`
- `openpyxl`

(See `requirements.txt` for versions.)

---

## 📜 License

MIT License. See `LICENSE` file (if added).

---

## 🙌 Credits

Developed by [Your Name] – feel free to contribute or fork.

Data Source: [USGS Earthquake Catalog API](https://earthquake.usgs.gov/fdsnws/event/1/)
