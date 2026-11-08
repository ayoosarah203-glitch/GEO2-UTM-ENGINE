

 GEO2-UTM-ENGINE: Spatial Dashboard

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://geo2-utm-engine.streamlit.app/)

> Group Project Submission — Group Three  
> Live Application: https://geo2-utm-engine.streamlit.app  
> Source Notebook: GROUP_THREE_WORK.ipynb
>
> Group Three Members

- ITHUNGU ZERISI
- AYOO SARAH
- LUKWAGO HENRY
- ERAR DANIELLA



 Overview

GEO2-UTM-ENGINE is an automated web-based geospatial transformation platform developed by Group Three. The application bridges theoretical geodesy and practical coordinate conversion by processing transformations between WGS 84 (EPSG:4326) geographic coordinates and Universal Transverse Mercator (UTM) projected systems.

The core computational logic was prototyped and verified in GROUP_THREE_WORK.ipynb before being deployed as an interactive Streamlit engine.



 Key Features

- Bidirectional Transformation: Seamlessly converts Geographic (Latitude/Longitude) to UTM (Easting/Northing) and vice-versa.
- Automated Zone Calculation: Determines the correct UTM zone and hemisphere based on longitude and latitude inputs.
- Residual Accuracy Analysis: Performs verification calculations to measure projection distortion and residual errors.
- Batch Processing & Export: Upload custom CSV files of coordinate sets, process transformations, and download results.
- Interactive Data Visualization: Dynamic spatial plots generated using Matplotlib.



 Technology Stack

- Language: Python 3
- Geospatial Engine: pyproj (PROJ coordinate transformation library)
- Data Handling: pandas
- Visualization: matplotlib
- Web Framework: streamlit
- Environment & Deployment: Google Colab (GROUP_THREE_WORK.ipynb), GitHub, Streamlit Community Cloud



 Running Locally

1. Clone the repository:
   git clone https://github.com/ayoosarah203-glitch/GEO2-UTM-ENGINE.git
   cd GEO2-UTM-ENGINE

2. Install dependencies:
   pip install -r requirements.txt

3. Launch the application:
   streamlit run app.py
