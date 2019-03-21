## More hoops

Now let’s add more hoops. The design uses 6 intersecting hoops. Each hoop is moved away from the centre and rotated a different amount. 

--- task ---
If you look at the design, there's no hoop in the centre. The hoops are all moved out from the centre.

Let's `translate`{:class="blockscadtransforms"} (move) the first hoop into position. 
	
![screenshot](images/pendant-translate.png) 
	
Now the hoop is a little off centre. 

--- /task ---
--- task ---
Now we need multiple copies of this hoop, rotated around the centre.  First let's create 3 equally space hoops using a `count`{:class="blockscadloops"} loop and `rotate`{:class="blockscadtransforms"}. 

	![screenshot](images/pendant-3-hoops.png) 
	
	The count goes from 1 to 3 and sets the `i` variable. Each hoop is rotated by `i` times 120 to space the hoops equally around the 360 degrees of a circle. 
	
	Look at the code and make sure you understand how it works. 

--- /task ---
--- task ---
The finished design has 6 hoops rather than 3. Change your code so that it creates 6 equally spaced hoops.

--- hints ---
--- hint ---
You'll need to change the `count`{:class="blockscadloops"} loop so that it runs 6 times instead of 3. And the 6 hoops will need to be equally spaced around 360. 
--- /hint ---
--- hint ---
need to change the loop to run from 1 to 6 and move in multiples of 60 degrees (360 / 60 = 60):

--- /task ---
--- task ---
Your code should look like this:
![screenshot](images/pendant-6-hoops.png) 
--- /hint ---
--- /hints ---
--- /task ---	
	
