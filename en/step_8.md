## Shake to activate

It's time to use the Sense HAT's movement sensors, in particular its accelerometer, to trigger the `walking` function you've created. This will make the project more interactive.
You'll need an infinite loop to begin with. Within the loop, you need to fetch the **raw** accelerometer readings. If the `x`, `y`, or `z` component of the accelerometer reading is above `2`, then your `walking()` function should be called.

If everything works correctly, shaking the Sense HAT will then animate your pixel pet!

Take a look at the hints below for help with writing the script.

--- hints --- --- hint ---
- In Python, an infinite loop can be created using a the line `while True:`
- You can use the `get_accelerometer_raw()` method to get a dictionary with the `x`, `y`, and `z` components of the accelerometer reading
- You can use an `if` conditional to see if any of the components are above 2
--- /hint --- --- hint ---
Here's some code to get you started:
```python
while True:
    acc = sense.get_accelerometer_raw()
	if accc['x] > 2 or ## Now check the y and z components
	    ## call your walking function here
```
--- /hint --- --- hint ---
Here's a video showing you how the script can be written:
<iframe width="560" height="315" src="https://www.youtube.com/embed/6l7HDCmYKCQ" frameborder="0" allowfullscreen></iframe>
--- /hint --- --- /hints ---

