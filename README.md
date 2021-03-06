# Weather Dashboard

![Screen Shot 2020-08-02 at 1 00 56 PM](https://user-images.githubusercontent.com/64692833/89130207-3cf94580-d4c0-11ea-8a0f-6c66b1136665.png)

# User Story

As a user who checks the weather everyday, I want to open up an application search for a specific city by name or by city, state and get today's current weather as well as a 5 day forecast. In addition to showing the current weather, the application will display temperature, humidity, UV index, and a picture representing whether it is clear, cloudy, raining, etc. 

# Intention

Build my first application using an API and retrieve data from a third-party weather applicaiton (OpenWeather API) using their API to pull in information of a city current and 5 day forecast.  In order to retrieve all the information needed, a good deal of mainpulation of the response from the GET request was needed, including taking information from one response to generate a new request. 

In order to display dates on the current conditions and forecasts, I used moment.js to easily do the date conversions for  the timestamp shown on the page. This was much easier  to achieve than use conversion methods such as a "getdate", "getMonth", and "getFullYear" methods to generate the date strings displayed on the page.

# Opportunities for Improvement

An opportunity for improvement would be to add an option to clear the search results that append to the previous search on the left-hand side of the screen. Secondly, I would had liked to displayed some sort of prompt to the user whenever a city entered is mistyped by mistake. As of right now, the only way to identify if a city was mispelled is to view the console log. 

# Links

* Deployed Link: https://alsricha.github.io/Weather-Dashboard/

