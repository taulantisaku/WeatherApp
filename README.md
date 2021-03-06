# WeatherApp
 This is a simple Weather Forecast app made with pure Javascript.
 
 The main purpose of this app was getting the weather information from usage of **Async & Await** functions with promises and manipulation with DOM. 
 Therefore, there are 2 scripts on this file : 
 - app.js (used for DOM manipulation)
 - forecast.js (used to get the weather API) 
  
 
 There are 2 API endpoints requests I used to fetch the data generated from the website AccuWeather : 
 
 - Location (City) using **getCity** function
 - Weather conditions using **getWeather** function

![Weather   City API](https://user-images.githubusercontent.com/44265863/132055189-bfa11c46-e4c4-4f19-8d7b-40fae87dd5d4.jpg)



In the other hand, using DOM manipulation we can set the image of the weather to be day or night,set temperature, weather description based on the properies inside the object **weather** returned by the API :

![isDayTime](https://user-images.githubusercontent.com/44265863/132056634-820c6ae2-2fe3-401a-a761-e7f4e376aa46.jpg)


 Using the **updateCity** async function, we get the city details and weather conditions together combined in one single function.
 
 ![updateCity](https://user-images.githubusercontent.com/44265863/132057320-8db2e01e-52ae-4bf3-869c-b705873f7fa7.jpg)

 In the end we added local storage to the app, in order to get the last city that has been checked from the user :
 
 ![localStorage](https://user-images.githubusercontent.com/44265863/132099390-96184ce5-0e3f-42a1-8507-a72da09e7ad0.jpg)

 
After completion of the project, I tried to implement the **Object Oriented Programming** logic into the code. 
All those separate functions were bundled together into a single **class Forecast**  as asynchronus methods. 
Then a new instance of Forecast class was created with those properties.

![Forecast class](https://user-images.githubusercontent.com/44265863/132309419-9bcdb27b-0a6e-40f7-9a1a-2315fa77fa46.jpg)


