03 

CROWDLEY  

An Android  application for Bilkent members to be able to see the level of density of particular areas through a Bilkent map, 
and the ability to see several different cafés and some certain places (like sports center or Mayfest lawn) in these areas. 
In addition to this, user will be able to see some specialties about these places like working hours or menus etc.

	
Current status: Working but have some missing places( buildings and so)
	

Sýla Ýnci & Melike Arslan: Worked on MapsActivity class and Google Maps API and did the xml of places' pages.
Yavuzselim Taþçý: Worked on Firebase to add users to certain buildings in check-in part
Nursena Kurubaþ: Worked on check-in part, wrote the code of OpeningActivity and CheckinActivity and did the xml of them.
Selim Özcan & Mehmet Sanisoðlu: Also worked on markers of map and wrote the pages of places.

We all worked together and helped each other's parts. 


Organisation and Working of Code

First the OpeningActivity class works and show the opening page for a while
Then the app moves on to Check-in Page and CheckinActivity class starts to run.
When user clicks done button the information will be added to database and map will be shown
The MapActivity class will run and show the Bilkent map with colored markers.
If user clicks the menu button a menu will be shown and any button that user click will lead user to another class
such as Buildings lead BuildingList class that has a button list of Buildings.
And when user clicks one of those buttons a specific page of that place will show up which is page class.


The tools we used:

Android Studio v2.3.2
Google Maps API
Firebase


How to work the program:

You should download Android Studio from https://developer.android.com/studio/index.html
and install by the instructions from https://developer.android.com/studio/install.html
    1- Launch the .exe file you downloaded.
    2- Follow the setup wizard to install Android Studio and any necessary SDK tools.

When you open Android studio you should choose Open an existing project and choose the project file
we sent. The project recompiles itself. To be able to run the program you should press the 'run' button and create a new virtual
device (preferably Nexus 5X API 24).
