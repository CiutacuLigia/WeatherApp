In this project I made an weatherApp using the OpenWeather API to display weather informations.

First I made the html file to create:

- a form which contains an input to introduce the name of the city and a button for search;
- a div element with the class "card" which will contain the information about the weather;

For styling I used a css file:

- I set the body with some characteristics for all the elements in the body;
- For the background image I had to wrap all the elements in the body into a div and set the name class to "display", then I used the pseudo-class ::before to put the image in the background and make it opac without affecting the other elements.
- I used flex property to display the elements in the body and the card class.

For functionality I used a js file, where I creted:

- three constants to extract the elements: weatherForm, cityInput and card from the html file and another constant to access the apikey from the API.
- an event listener to make functional the button element.
- an asynchronous function to get weather data from the API;
- three frunctions to display weaher info, get weather emoji and display error.
- in the displayWeatherInfo function I created and added inside the card class the elements:
  cityDisplay, tempDisplay, humidityDisplay, descDisplay, weatherEmoji in which I inserted the extracted informations from the API;
