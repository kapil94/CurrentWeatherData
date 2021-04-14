# CurrentWeatherData
to check current weather forecast

Algorithm:

1. Generate an API key from openweathermap.org
2. GET request a url which contains name of city (for which you need to find weather details) passed as command line argument and API key generated from step 1.
3. Response data from step 2 is in form of JSON, convert that json data into python dictionary by using json.loads(response data).
4. Find the value of key from dictionary with current weather and convert it into Celsius(It is in Kelvin as default).
5. Print the name of the city and it's current weather. 
