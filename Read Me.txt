# OpenWeatherMap
functional API automation

 Author : Mogale Mapaela
 2021/07/08

Steps on how to run the files on Postman

1. Import both the files named 
 	a. Global Kinetic - Environment.postman_environmet
	b. Global Kinetic.postman_collection
	c. Download 7zip from https://www.7-zip.org/download.html 
	d. Once 7Zip is downloaded and installed , right click on a file named "city.list" and extract. 

2. When Running the collection please attach the file named "city.list" as a Data file. (Note: The collection named "Read from JSON file" require a JSON file in order to execute.
3. Please set the Iteration to "1".
4. Click Run 

NB: The collection will take a few seconds before executing as it reads the JSON Data file

P.S The tests include the following 

	- Dynamic Global variables
	- Parameter
	- Postive and Negative Test Scenarios
 	- Environment file for dynamic URL and API Key
