# A simple game

This is a simple game that has the goal of trying to get the ball into the bucket.
You can draw on the plane for the ball to bounce/roll on. Scores are calculated 
based on the time used and the length of lines drawn on the plane.

If you try to draw on the ball the game resets, this is also the only current way of restarting.



# Run

````bash
javac MyGame.java GameWorld.java CollisionDetection.java
java -cp . MyGame
````

made with java version "1.6.0_24" (OpenJDK)
