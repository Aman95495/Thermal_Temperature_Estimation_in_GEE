# Thermal Temperature Estimation using Landsat 8 in Google Earth Engine

## Overview

This project utilizes Google Earth Engine to estimate thermal temperature from Landsat 8 satellite imagery over a specific region of interest. The temperature is calculated from the thermal bands (Bands 10 and 11) of Landsat 8 data.

## Prerequisites

1. **Google Earth Engine Account**: Make sure you have access to [Google Earth Engine](https://earthengine.google.com/) and have signed up for an account.

2. **Python and Libraries**: The project code is written in Python. Ensure you have Python installed on your machine along with the required libraries such as `geemap` and `ee`.

## Project Structure

- **1_Data_Collection.ipynb**: Accesses Landsat 8 data for a defined Area of Interest (AOI) and date range using Google Earth Engine.

- **2_Calculate_Temperature.ipynb**: Defines thermal bands, calculates temperature, and creates an image collection of temperature values.

- **3_Visualize_Temperature_Map.ipynb**: Visualizes the calculated temperatures on an interactive map using `geemap`.

## Usage

1. Open and run each Jupyter Notebook (`1_Data_Collection.ipynb`, `2_Calculate_Temperature.ipynb`, `3_Visualize_Temperature_Map.ipynb`) in sequence.

2. Make sure to replace the AOI coordinates, date range, and any other parameters as per your project requirements.

3. The final notebook (`3_Visualize_Temperature_Map.ipynb`) will visualize the mean temperature on an interactive map.

## Configuration

- **Google Earth Engine Authentication**: You need to authenticate your Google Earth Engine account. Refer to the [authentication documentation](https://developers.google.com/earth-engine/guides/python_install#authenticate-with-earth-engine).

- **Python Environment**: It's recommended to use a virtual environment to manage Python dependencies. You can create one using tools like `virtualenv` or `conda`.

## Results
## Heat Distribution image

This is the image of heat distribution in madrid spain

![Screenshot 2024-01-15 161419](https://github.com/Aman95495/Thermal_Temperature_Estimation_in_GEE/assets/90555918/5f1032af-128a-4ae6-9e7b-0cfd84235481)
## Issues and Troubleshooting

If you encounter any issues or errors, please check the [issues section](#) of this repository for possible solutions. If your issue is not addressed, feel free to open a new issue.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- The project is inspired by similar work in the remote sensing and Earth Engine community.
- Acknowledge the Google Earth Engine team for providing powerful tools for geospatial analysis.

