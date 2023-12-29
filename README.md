# METAR_by_coordinates
J.Notebook environment for retrieving METARS from database based on date and coordinates

There are three essential functions that were kept easy to be modified easily.

## Fetch METAR data in CSV
If you know the ICAO indicators, you can get data from any available time-span
![Example usage of fetch_and_process_csv function_](https://github.com/Sladekd/METAR_by_coordinates/blob/main/Fetch_data.PNG)


## Find ariports in your county
If you do not know the ICAO indicators, you can first finnd available airports
![Example usage of generating of the airport information woithin ASOS network](https://github.com/Sladekd/METAR_by_coordinates/blob/main/Generate_asos_stations.PNG)

## Find nearest airports to the coordinates
If you do not know which ariport you would find suitable, try to find the closest airports to your coordinates and then fetch data from them!
![Example usage of finding the closest airports_](https://github.com/Sladekd/METAR_by_coordinates/blob/main/Find_closest.PNG)
