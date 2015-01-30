# Basic Interview Problem  

Greetings and salutations.  The following is a basic exercise that the Mobile Apps Team uses to help us interview bright and talented developers like you!  This project includes the framework for a simple map-based android application.  Once we have a functioning shell of an application up and running, we will ask you to perform a few changes to add some basic behavior of the application.  Once you're done, we'd love to see your code!  

Lets get started!  

Step 1: Install Android Studio.  I used version: 1.0.  

Step 2: Download the code onto your machine using git. Something like:
````
git clone https://github.com/travisbaumgart/BasicInterviewProblem.git
````

Step 3: Import the git project into Android Studio.  A few users have had to upgrade Gradle in order to get the project building.  Android Studio SHOULD help you with this.  Take a look at the application structure.  Like most IDEs, Android Studio hides a lot of the dirty details from us so that we can just concentrate on the task at hand.

Step 4:  Let's get the app building and deployed to a phone.  If you don't have a phone, feel free to use the Emulator that comes with Android Studio.  The phone is faster/easier.  You've been warned!  First make sure your phone is in Development Mode.  This will allow Android Studio to deploy your app.  Not sure how to put your phone into Development Mode?  I could google that for you...but I WON'T!  Once you're ready...use Android Studio to publish the app.  

Step 5:  Houston...we have a problem.  Your map is probably not showing up.  Our goal was something like:  

![screen1](https://raw.githubusercontent.com/travisbaumgart/BasicInterviewProblem/master/images/interview1SS.png)
````
Here is your first challenge.  Let's fix the app so that we can see the map.  
Open up the file called google_maps_api.xml.  You need a Google Maps API key.  
Follow the instructions in the comments at the top of this file.  
See if you can't get the map to show up.
````
Step 6:  Something you should know about the Mobile Apps Team.  We love Medieval Times dinner theatre.
![s](https://raw.githubusercontent.com/travisbaumgart/BasicInterviewProblem/master/images/image002.jpg)
![s](https://raw.githubusercontent.com/travisbaumgart/BasicInterviewProblem/master/images/image003.jpg)
````
For your next challenge, find the Medieval Times in Baltimore.  
Put a Marker on the map at that location.  For extra credit, have the 
application zoom in to that location when you open it.
````
Step 7:  By now, you've probably noticed the three buttons at the bottom of the screen labled 'Normal', 'Satellite' and 'Hybrid'.  If you press them, notice that ABSOLUTELY NOTHING HAPPENS!
````
Wire up those buttons to actually do something.  Changing the map type isn't 
that hard.  As a stretch goal, add some logic to activate/deactivate the 
buttons at appropriate times.  Probably shouldn't be able to press Hybrid 
if a Hybrid map is being displayed.
````
If you've made it this far, you're doing great.  The Mobile Apps Team doesn't want you to burn an entire weekend on this exercise.  If you've got some more gas in your tank, consider the extra credit.  This problem is a little harder.
````
Add another button to the bottem of the screen.  You may have to play with 
the layout a little bit to get it pretty.  We're going to turn this button 
into a Tile Overlay for our map.  Take a look at the following page:
  
  https://developers.google.com/maps/documentation/android/tileoverlay
  


````
