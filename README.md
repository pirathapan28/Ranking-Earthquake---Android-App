# Android App: Ranking Earthquake 
An android app that uses android studio and BlueStack Emulator 
## Purpose
Used Android Studio to create a mobile app that fetches the earthquake API and displays recent updates on earthquakes based on magnitude or chronological order
## User Interface
When we first open the app, we have a drop down menu when clicking the "order by" button that allow us to select if we want to order earthquake by chronological order or the magnitude of the earthquake. 
![alt text](https://github.com/pirathapan28/Ranking-Earthquake---Android-App/blob/master/image/homescreen.PNG)
We also have a clickable calender view, when you click on the "Start date" button, a calender API is loaded. This date is for when we want to start fetching earthquake data. For example, if we click on today's date, it will show if there has been any earthquake recorded today.
![alt text](https://github.com/pirathapan28/Ranking-Earthquake---Android-App/blob/master/image/calendar.PNG)
<br> <br>
Once we have figure out what order we want to list the earthquake data, we can simply click submit, which will start a new intent. The earthquake data is displayed in a listview. Each listview is also clickable.
This is an image of the listview when clicked submit when ordered by chronological order.
![alt text](https://github.com/pirathapan28/Ranking-Earthquake---Android-App/blob/master/image/orderbydate.PNG)
This is an image of the listview when clicked submit when ordered by magnitude size. 
![alt text](https://github.com/pirathapan28/Ranking-Earthquake---Android-App/blob/master/image/orderby.PNG)

<br>
Each listview is a clickable. When clicked, it will show the geography of the earthquake on the map. We use the longitude and latitude that is fetched by the earthquake API and geographically map it for us to see.<br>
This is an image of Ecuador, the marker is placed on Ecuador. If you were to click on the listview that says Ecuador on it, it will displays this on the map. <br>
![alt text](https://github.com/pirathapan28/Ranking-Earthquake---Android-App/blob/master/image/map.PNG)
<br>
