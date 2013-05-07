UBTalker_2013
=============

UBTalker developed for Windows Surface RT at University at Buffalo.
This application is being developed to extend the existing UBTalker in the tablet PC domain. 
The application is developed using C# in Visual Studio 2012 on .Net 4.5. 
The application uses SQLite Runtime for Windows RT for the database tool. The Visual Studio 2012 extension is available in the Visual Studio market. 

To run the application on the Windows Surface RT, you can either configure VS2012 to debug in the remote ARM processor mode OR create a package and then download the package on the Windows RT and it'll be up and running merrily.

Configuration parameters : 

Platform - ARM (Windows Surface RT Device)
           x86 (Windows 8 OS)

Pre-requisites : 
-- Windows 8
-- Visual Studio 2012 
-- SQLite Runtime Environment for Windows RT
-- Bing Translator Client ID and Client Password 

The application starts off with the Main Screen which contains tiles referring to categories like School, Shopping, Help and Office etc. 
When you click on a tile, it takes you to the next screen which is pre-populated by a set of tiles which come under thatn coategory. 
Each tile has a Title and Subtitle. 
Click on any tile and the application will speak up the Title of the tile. 
To add a tile, right-click on the screen and you'll have the app-bar pop-up at the top of the screen. 

The app-bar has 3 buttons 
  -- Add --> Takes you to a new page to add a tile to the current page. 
  -- Keyboard --> Takes you to a new page to use the customized keyboard to type sentences.
  -- Delete --> This is dysfuntional at the moment. 

The Add Tile Page gives you options to add a Title, Subtitle and description. 
Right-click on the screen to get the app bar on the top of the screen and you see the Pictures icon. 
Clicking on the icon will take you to the Add Picture page where you can add a background image to the icon by selecting a file from your disk.
Click Submit on any button and you'll be taken back to the page of the category you were working on.

The Everyday and General pages don't have any pre-populated icons on the screen. 

The application saves the audio files streamed from the Microsoft server, the first time a tile is clicked.
After that it just uses the audio file to replay when the tile is clicked. So the response of the application on the first click will be slow. And ev
