# python-api-challenge

Repository structure:
*Folder: Weatherpy:
      * contains:
          *Folder:output_data
          *VacationPy.ipynb
          *WeatherPy.ipynb
*README.md

### WeatherPy 

Python script to vizualize weather of 500+ cities across the world of varying distance from the equator.
* Utilizes API Calls from OpenWeatherMap API to call and retrieve weather data 
* Contains Exception Handling for any cities not found
* Produces data retrieval status for each city during call 
* DataFrame cleanup and basic statistics 
* Scatter Plot of various Latitude vs Variable to view general trends
* Linear Regressions of separated data to view correlation and trends
* Each plot is saved as a png 
* cleaned up DataFrame is saved as a .csv file 

### VacationPy 

python script to view maps, heatmaps, and marker layered maps.
* Utilizes google API/gmaps to produce heatmaps for humidity 
* DataFrame clean up/ filtering to view the best weather locations within the data 
* Utilizes data retrieval from google API to locate hotels nearby within 5000m of the best weather location cities 
* Creates layered maps based on output
