"Hi Greta, great job. You were very close with the fill color. You just needed to specify the fillStyle before you fillRect. Try it.

Also, don't spawn a new sound everytime the ball hits the walls (memory leak) . You want to save the audio once during init, and just use the variable to play it when the hit happens."


1. Can't get the colors to work right
2. Can I Use the existing functions created for check if hitting wall?

//GET THE CONTEXT OF THE CANVAS

// INITIALIZE GAME VARIABLES

// WRITE THE PLAYER OBJECTS -> BLUEPRINT

// CREATE THE PLAYER OBJECTS

// INITIALIZE GAME STATE (Initialize Players, reset Score, clear canvas)

// ENTER GAME LOOP - 60 FPS
{
	
	UPDATE GAME OBJECTS (GETS YOU THE NEW POSITION & ALSO OTHER MATERIAL STATES)
	{
		1. CALL AI FUNCTIONS
		2. CHECK USER INPUT 
		3. DO COLIISIONS
		
	}

	RENDER GAME OBJECTS


}

- Break point on render 
- jump into function
//
So just to recap your homework - 

Do the collision check with the ball 
Update Score 
Program the Game Over condition 

That should be it for this game ! 