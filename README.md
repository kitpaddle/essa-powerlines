# SAPIAT
### Stockholm Arlanda Powerline Inspection Application Tool

This is the official Application tool used by Arlanda (ESSA) ATC for air traffic that wishes to enter the ESSA CTR (Controlzone) to perform Powerline Inspections.

The site was developed by Joachim Koitsalu. The code is open-source and makes use of Leaflet and OSM-map data.

#### How to use the website

* Use the map and drawing features (available on the left on the map) to draw the powerlines you intend to inspect. 
* These can be removed or edited if you made a mistake with the adjacent tools.
* Fill in all the requested information in the form on the right side.
* Mouse-over on the "information"-button in the top right corner to see more details on the required form inputs.
* Once everything is filled in, press the "SAVE & CREATE APPLICATION" button
* This creates two things: a document which you should save as a PDF and email to the ESSA ATC Tower, and a a small .JSON file that you should also email to the ESSA ATC Tower. This small file contains the data you've entered. You can use the LOAD button to reload that data and continue editing your application at a later date if you so wish.
* You may then expect a reply within 2-10 workday. The email the application must be sent is available at LFV.se 

> Why do we ask bout the 335ft QNH altitude. If you cannot maintain at least 335ft QNH while doing the inspection, we cannot, according to the procedures set by state separate your aircraft from commercial aircarfts departing/landing at ESSA. Which means we either have to delay you or them while you do the inspection. And as you may understand commercial traffic flying in and out of Arlanda will have priority.

A JSON file is also created each time an application is created. This JSON file is plain/text and contains all the drawn powerlines as GeoJson data.
This can easily be viewed on the webpage by using the LOAD button to upload your file back to the website. This way you can save your progress and continue at a later date if so required.
