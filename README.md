#Project 1-1 Spec [Due 1/27 at 11:59 pm]:
##How to download Unity
Download Unity at https://store.unity.com/download?ref=personal and install it  
##How to get project through git  
The project repository is at: https://github.com/berkeleyGamedev/Project1-1  
If you or your partner know how to use git use it to clone the repository.  
If you don’t know how to use git, here is a tutorial: http://rogerdudler.github.io/git-guide/  
If you have further questions about acquiring the project, please ask on Piazza.  

You should try to use git for version control on the project. Submission will be through your git repository on Github.

In order to open the project in Unity simply run Unity and click the open button on the splash screen, then select the project folder.

##About the Project
This project is for teams of 1-2 (we would prefer teams of 2). Every team must have at least 1 programmer. The project is split into 3 parts. Every team must do the Editor and Programming parts, and you only have to do the Art part if you have an artist in your group. You can find a partner through the Piazza “Find a teammate” post.

##Grade Breakdown:
Requirements: 55%
Complexity: 25%
Creativity: 20%
These two categories are here for your benefit. We want to allow students to have fun with these projects, do not stress over these categories.

###The requirements are listed below, some are left vague and open-ended. These open-ended requirements are where you can earn your creativity and complexity points.

##Unity Editor (Artists and/or Programmers):
* Oh No! Mario appears to be starting too far left and falling off the level. Figure out how to manipulate Mario’s transform component to get him above the ground
* Now Mario is moving but something still feels fishy, it looks like the Input keys were changed! Find the Input Manager tab and fix this (It is located in one of the drop-down menus)
  * Rebind keys correctly in input manager
  * Optional/Recommended: Look into what some of the other Input settings do such as Gravity and Dead
* Something appears to be wrong with the Gravity! (Note this is actual gravity, not Gravity associated with Inputs). Play around with it so that it feels right. It should be under the Physics tab.

##Art (Artists):
Requirements:
* Replace Mario with a new character! Use any art style you feel comfortable with.
  * Update any other art assets you want (Totally Optional)
* Add art to the new Mario ability that your team creates.
Totally Optional (Extra Credit):
* Write a backstory for your character. If it is a totally different art style try and justify why they are here and why they look so different.


##Programming (Programmers):
All change will be made in the Player Controller Script. You will find the text “YOUR CODE HERE” wherever you need to make changes.
Requirements:
* Pass Little Mario into the Player Controller script using the editor (No coding needed)
  * Note how Little Mario is a public variable in the script
* Make the Mario flip when the direction is changed (Flip() function provided)
  * Changes will be made in FixedUpdate()
* Make Mario jump
  * Changes will be made to the class Jumping
* Add a new ability to Mario
  * If your group is not doing the Art category and you have 2 members you must add two new abilities.
  * Ex: Hover jump, double jump, teleportation, etc
  * Does not have to be an actual Mario ability!

##Submission:
* Place a copy of all your art files into a separate folder. Make sure this folder is included in your git repository.
* Make sure you have added the github user berkeleyGamedev as a contributor to your github repository.
* Add a commit with a “final submission” tag and push it to github.
* Double check that the github repository contains a working version of your project :-)
# GCS17Proj1-1
