# NASA-Exoplanet-Data-Web-Scraping
This repository contains a Python script for scraping exoplanet data from NASA's catalog using Selenium. It collects exoplanet names, distances, masses, discovery dates, and stellar magnitudes, and saves the data in a CSV file.
NASA Exoplanet Data Scraper

This project comprises a Python script that automates the extraction of exoplanet data from NASA's Exoplanet Exploration Program's catalog.

## Project Description

The script uses Selenium, a powerful tool for controlling web browsers through programs and automating browser tasks. The data points collected for each exoplanet include the exoplanet's name, its distance from Earth, its mass, the date it was discovered, and its stellar magnitude.

The data is organized into a pandas DataFrame, a two-dimensional, size-mutable, and heterogeneous tabular data structure that is great for representing real-world data. The DataFrame is then exported to a CSV file for easy accessibility and future analysis.

This script showcases the application of Python for web scraping in the field of astronomy and data science, providing a practical method for collecting exoplanet data.

## How to Use

To use this script, clone this repository and run the Python script. Make sure you have the necessary Python libraries installed, including Selenium and pandas. The script will automatically navigate the NASA catalog, collect the data, and save it in a CSV file in your local directory.

## About the Data

The output CSV file contains the following columns:

**Name :** The name of the exoplanet.

**Distance :** The distance of the exoplanet from Earth.

**Mass :** The mass of the exoplanet.

**Discovery Date :** The date the exoplanet was discovered.

**Stellar Magnitude :** The stellar magnitude of the exoplanet.

Remember to check the CSV file for any null values, as these may indicate missing data or errors during the extraction process.
