# CSV-to-Google-Earth
A lightweight automation tool that converts CSV files containing geolocation data into KML format and uploads them to an FTP server for visualization in Google Earth.

---

## Features

- 📥 **Automatic CSV Download**: Periodically fetches updated CSV data from a specified URL.
- 🗺️ **CSV to KML Conversion**: Translates latitude, longitude, status, and name fields into Google Earth–readable KML format.
- 🎯 **Status-Based Icon Styling**: Custom KML icons and colors based on station status (`Nominal`, `Deactivated`, `Warning`, etc.).
- ☁️ **FTP Upload**: Automatically uploads the generated KML file to a predefined server path for shared access.
- 🔁 **Periodic Refresh**: Checks and updates data at user-defined intervals.

---

## Technologies Used

- **Python 3**
- `pandas` – for data processing  
- `simplekml` – to create KML files  
- `requests` – for HTTP requests  
- `ftplib` – for FTP file transfer

---

## Use Cases

- Visualizing remote station status on Google Earth  
- Geo-monitoring systems  
- Any scenario where location data from a CSV or database tables must be auto-synced to a KML format for spatial visualization

---

## Getting Started

1. Clone this repo.
2. Install dependencies:
3. Edit the script with your CSV URL, local file path, and FTP credentials.
4. Run the script:

---

## License and Commercial Use:

This project is licensed under the [MIT License](LICENSE). feel free to use, modify, and share it for personal and educational purposes.
For any commercial use or distribution, please contact the author for permission.

---

## Author

Alireza peimanara



## Note:
Any other data such as SQL tables could be replaced instead of CSV  

