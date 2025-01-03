pip install phonenumbers

pip install opencage

pip install folium
📱 Phone Number Tracker

This Python project allows you to track the location and service provider of any phone number using the Tkinter library for the GUI, the `phonenumbers` module for parsing the number, and `folium` to map the location.

 💡 Features

- **Location Tracking:** Get the country or region where the phone number is registered.
- **SIM Provider Identification:** Identify the service provider of the phone number.
- **Map Visualization:** Display the phone number’s location on a map using `folium`.
- **Interactive GUI:** User-friendly interface built with Tkinter.

🛠️ Technologies Used

- **Python:** Core language
- **Tkinter:** For creating the GUI
- **phonenumbers:** To parse and get location and carrier information
- **OpenCageGeocode API:** For converting location names to coordinates
- folium: For rendering maps
- webbrowser: To open the generated HTML map

 📋 Requirements

1. Python 3.x
2. Install the required libraries:

```bash
pip install phonenumbers
pip install opencage
pip install folium
```

## 🔑 API Key Setup

You need to get an API key from [OpenCage Data](https://opencagedata.com/) to make this application work. Replace the placeholder in the script with your key:

```python
key = "YOUR_API_KEY_HERE"
```

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/yourusername/phone-number-tracker.git
cd phone-number-tracker
```

2. Place the necessary images (e.g., `logo.png`, `search.png`, and `search_icon.png`) in the project directory.

3. Run the script:

```bash
python phone_number_tracker.py
```

4. Enter the phone number (including the country code) in the input field and click the search button to track the number.

5. Click on the **Location** button to view the location on a map.


⚠️ Disclaimer

This tool is meant for educational purposes only. Please use it responsibly and avoid violating privacy laws.

 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests.
