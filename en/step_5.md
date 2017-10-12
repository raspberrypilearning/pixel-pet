## Representing your pet

The pet you designed earlier can now be represented by a Python list.

- Create a list like the one below called `pet1`, and type in the colour of each pixel, using the colour variable names you just created. Note that the list needs to be surrounded by `[` and `]` and each colour pixel must be followed by a comma.

	```python
	pet1 = [
		e, e, e, e, e, e, e, e,
		p, e, e, e, e, e, e, e,
		e, p, e, e, p, e, p, e,
		e, p, g, g, p, y, y, e,
		e, g, g, g, y, w, y, g,
		e, g, g, g, g, y, y, e,
		e, g, e, g, e, g, e, e,
		e, e, e, e, e, e, e, e
		]
	```

- Repeat this for the second pixel pet design, but use a different name, such as `pet2`.

- If you ran your code now, nothing would happen, because so far you have only told the program to store information. To make something happen, you will need to write a command to call on that data and display your colours in the right order on the Sense HAT LED matrix. Add this command below your lists:

	```python
	sense.set_pixels(pet1)
	```
- When you've run the program once, you can type directly into the shell to switch back and forth between your two pets.

	```python
	>>> sense.set_pixels(pet2)
	```

- If you want to clear the LED matrix after setting the images, you can use the following command:

	```python
	>>> sense.clear()
	```

--- collapse ---
---
title: Video help
---
Here's a video to help you out if you get stuck:
<iframe width="560" height="315" src="https://www.youtube.com/embed/gBbYjKGAQsM&rel=0" frameborder="0" allowfullscreen></iframe>
--- /collapse ---
