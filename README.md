# Weather and Air Quality Web App

This web app displays weather and air quality data for cities around the world, powered by AirVisual API and built using Streamlit.

![Weather and Air Quality Web App Screenshot](https://user-images.githubusercontent.com/45052719/230487390-269d11a9-ed7e-4aa1-8de1-93c7d61cd182.gif)

<a href="https://air-weather.streamlit.app/" target="_blank">Live demo</a>

## Features

- Search weather and air quality information by city, state, and country.
- Get weather and air quality data for the nearest city using your IP address.
- Search for weather and air quality information by latitude and longitude.
- Displays temperature, humidity, and air quality index.
- Shows the location of the selected city on an interactive map.

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Streamlit
- Streamlit Folium
- Streamlit Pills

### Installation

1. Clone this repository or download the project files.

```bash
git clone https://github.com/jamesjbustos/air-weather-streamlit.git
cd air-weather-streamlit
```

2. Create a virtual environment and activate it.

```bash
python -m venv env
source env/bin/activate # For Linux and macOS
env\Scripts\activate # For Windows
```

3. Install the required packages.

```bash
pip install -r requirements.txt
```

4. Get a free API key from [AirVisual API](https://www.iqair.com/air-pollution-data-api).

5. Create a `secrets.toml` file inside the `.streamlit` folder in the root directory of the project. Add your API key to the file in the following format:

```bash
api_secret="YOUR_API_KEY"
```

4. Run the Streamlit app.

```bash
streamlit run main.py
```

## Technologies Used

- [Streamlit](https://streamlit.io/): An open-source app framework for creating data-driven web apps.
- [AirVisual API](https://www.iqair.com/air-pollution-data-api): API for getting air quality and weather data.
- [Streamlit Folium](https://github.com/randyzwitch/streamlit-folium): A Streamlit component for rendering Folium maps.
- [Streamlit Pills](https://github.com/okld/streamlit-pills): A Streamlit component for creating clickable pills.

## License

This project is licensed under the MIT License.


