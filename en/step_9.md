## Shake to trigger action

It's time to use the Sense HAT's movement sensors, in particular its `accelerometer` to trigger the walking function to make the project more interactive.

- Underneath your walking function, but above the function call line of `walking()`, type:

	```python
	x, y, z = sense.get_accelerometer_raw().values()

	while x<2 and y<2 and z<2:    	
		x, y, z = sense.get_accelerometer_raw().values()
	
	walking()
	```
	
	The first line will get current movement readings from the Sense HAT on its x, y, and z coordinates. As your Raspberry Pi is presumably sitting still on a desk, those readings will have a very low value.
	
	Then a `while` loop is introduced to continually check the accelerometer values, to see if they have changed to above or equal to the value `2`. You can help the Sense HAT have an accelerometer reading of above `2` by shaking it!


    <iframe src="https://trinket.io/embed/python/4ff36df371" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
	
- Check your code, especially the indentation [against this version here](resources/space-pet.py).	
	
- Save your code and run it. Nothing should happen until you shake your Raspberry Pi. 	


