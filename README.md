# 🥊 MMA Data Visualization Dashboard

This project is a web-based dashboard designed to visualize and explore global MMA-related data, such as fighter locations, statistics, and performance metrics. Built using HTML, CSS, JavaScript, and open datasets, the dashboard allows users to interact with maps and visual data insights in a clean, responsive interface.

## 🔧 Technologies Used (HTML & JS)

This dashboard was built using only **HTML**, **CSS**, and **JavaScript** with no backend. Core libraries and frameworks used:

- **D3.js v3**: Main library for all data visualization (line chart, bar chart, scatter plot, map).
- **noUiSlider**: For any potential time-based UI filters (currently included, not in active use).
- **GeoJSON**: Used with D3 for plotting country shapes.
- **Custom JavaScript**: Handles parsing CSVs, rendering charts, adding interactivity, tooltips, and chart animations.
- **Basic CSS**: For tooltip styling, axis formatting, and layout management.

## 🌍 Features

- Interactive dashboard with charts and maps  
- Visualizes geocoded MMA fighter data  
- Country-based filtering and performance stats  
- Uses external CSV and GeoJSON files for data input

## ⚙️ How to Run (Requires XAMPP)

Due to browser security restrictions on loading local files (like `.csv` and `.json`), you’ll need to serve this project using a local server. The easiest way is with **XAMPP**.

### Steps:

1. Download and install [XAMPP](https://www.apachefriends.org/index.html).
2. Place the entire project folder inside the `htdocs` directory -> C:\xampp\htdocs
3. Start **Apache** via the XAMPP Control Panel.
4. Open your browser and go to -> http://localhost/MMA-Data-Visulisation-Project/
5. Click on -> MMA Dashboard.html

## 📁 Project Structure

- MMA Dashboard.html # Main interactive dashboard
- geocoded_data.csv # Dataset with location-enhanced fighter data
- mmaData.csv # Original MMA stats dataset
- world_countries.json # GeoJSON map boundaries
- MMAProject.pdf # PowerBI Representation of the Data

## 👤 Author

**Elvis Haziri**  
📧 elvisihaziri@gmail.com  
[LinkedIn](https://www.linkedin.com/in/elvis-haziri-095b34251)
