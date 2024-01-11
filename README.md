# 📍 Location Finder App (Python + Jupyter Widgets)

This is an interactive **location-based search tool** built using Python. It lets users find nearby places (like hospitals, food joints, ATMs, etc.) within a specified radius using a dataset of geolocations and visualize them on a map.

---

## 🚀 Features

- 📌 Find nearby locations by category (e.g., hospital, petrol pump, food place)
- 📍 Uses current or default user coordinates (like RCOEM)
- 🗺️ Visualize results on an interactive map using `ipyleaflet`
- 🧭 Calculates real-world distances using `geopy`
- 🧩 Interactive UI using `ipywidgets` in Jupyter Notebook

---

## 🛠️ Tech Stack

- Python 3.x
- `pandas`
- `geopy`
- `ipyleaflet`
- `ipywidgets`
- `Jupyter Notebook`

---

## 📂 Folder Structure

location-finder/
├── location_dataset.csv
├── location_finder.ipynb
└── README.md

yaml
Copy
Edit

---

## 🗺️ Sample Dataset Format (`location_dataset.csv`)

| name        | category     | latitude | longitude |
|-------------|--------------|----------|-----------|
| AIIMS       | hospital     | 21.1458  | 79.0882   |
| HP Petrol   | petrol_pump  | 21.1578  | 79.0799   |
| Domino's    | food_place   | 21.1700  | 79.0801   |
| HDFC ATM    | Bank_Atm     | 21.1603  | 79.0893   |

---

## 📌 How to Run

1. Install required libraries:

```bash
pip install pandas geopy ipyleaflet ipywidgets
Run the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook
Choose a category and click "Show Map" to see nearby places around your current/default location.

📍 Default Location
The app sets an initial default location to RCOEM (Latitude: 21.1766, Longitude: 79.0616), but it can be changed to user input in other versions.

📊 Customization
Add more location categories to the dropdown

Change default coordinates

Connect real-time geolocation APIs for live input