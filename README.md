# NoSQL Database Query Project

This project involves implementing functions within a Jupyter Notebook to perform specific operations on a NoSQL database, utilizing Python for querying and data manipulation based on geo-spatial data and business location criteria. 

## Introduction

The project focuses on two primary functions:

1. **FindBusinessBasedOnCity**: Searches the provided `collection` for all businesses in the specified `cityToSearch` and saves the results to `saveLocation1`. The output format for each business is Name$FullAddress$City$State, where `$` is a separator.

2. **FindBusinessBasedOnLocation**: Finds all businesses within `maxDistance` from `myLocation` based on categories specified in `categoriesToSearch` and saves the names of these businesses to `saveLocation2`.

## Distance Calculation

A specific distance algorithm is utilized to calculate the distance between two pairs of latitude and longitude, allowing for the filtering of businesses based on proximity. The calculation is based on the Haversine formula, facilitating the identification of businesses within a given distance from a specific location.

## Requirements

- Python
- Jupyter Notebook
- Access to a NoSQL database

## Setup and Execution

1. Ensure Python and Jupyter Notebook are installed on your system.
2. Clone this repository and navigate to the project directory.
3. Open the Jupyter Notebook (`NoSQL_Query_Project.ipynb`) and run the cells sequentially to perform the operations described above.

## References

- Distance calculation adapted from [Movable Type Scripts](http://www.movable-type.co.uk/scripts/latlong.html) for latitude and longitude distance computation.

---
