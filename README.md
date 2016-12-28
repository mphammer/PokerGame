--------------
Big Java Poker
--------------
This program is a graphics oriented Texas Hold'em Poker varient.  The game
utilizes simple Poker AI that use simply actuary skills to determine the best
time to perform specific betting options.  The graphical layout of the game is
geared toward a multipanled screen with a "flat" 3D perspecitve in the main
panel.

<br>
![mainpages](https://66.media.tumblr.com/3f40681dbce2201dc1dc596c9a6fac11/tumblr_of2oncVDfQ1r438poo1_1280.png)
<br>

-------
Authors
-------
* Devon Wasson
* Morgan Eckenroth
* Michael Hammer
* Yash Bhutwala

---------
Libraries
---------
* Slick2D - primary graphical library
* LWJGL - Used to create openGL contexts to allow for screen rendering

-----------
Compilation
-----------
* First build the project like usual in your IDE
* Now, go to the main project folder and find the jarsplice program
* Run this using the command "java -jar "jarsplice-0.40"
* Click on "Add Jars" on the side and again at the bottom.
* Navigate to the output folder from the IDE's build and add the main jar file for the program, and also all of the contents of the "lib" folder.
* Click on "Add Natives" on the side and again at the bottom.
* Navigate to "Externals/lwjgl 2.9.3/natives/linux" and add all six of the files
* Now click on "Main Class" and enter "view/Game" in the field
* Finally click "Create Fat Jar" and place the file wherever.
* Run the output jar as normal.

-------
Running
-------
To run the newly compiled Fat Jar, navigate to the containing directory and
enter the command "java -jar "nameOfJar.jar"" without the outer quotes and the
game should start running.
