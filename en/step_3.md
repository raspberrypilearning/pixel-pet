## Setting your colours

Now that you have your designs represented as letters in a grid or array, you can start to code them in Python.

- Open mu.



- Save this empty file as `space-pet.py`.
- First you need to import all the modules and libraries you will use for this project by typing:

	```python
	from sense_hat import SenseHat
	from time import sleep
	```

- Next you need to create a `SenseHat()` object to interact with the Sense HAT:

	```python
	sense = SenseHat()
	```

	Note that capital letters, full stops, and commas are very important in Python. Your code might not work if you do not include these.

- Create one variable to represent each of the colours you have used in your design. If you use a single letter instead of the full colour name, you will find it easier later on, but make sure you have no duplicates - you can't use `b` for both blue and black!

```python
b = (0, 0, 255)
```

You can look up the RGB values of the colours using a [colour picker](https://www.w3schools.com/colors/colors_rgb.asp){:target="_blank"}.

These variables are called **tuples**.

[[[generic-python-tuples]]]

--- hints --- --- hint ---
Give your variable a name, then add in the three numbers that represent the colour, separated by commas and surrounded by parentheses.
--- /hint --- --- hint ---
If you wanted to code the colour red, then you would use this code:
```python
r = (255, 0, 0)
```
--- /hint --- --- hint ---
Here's a video showing you how to set your colours:
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5J85lA0JJs" frameborder="0" allowfullscreen></iframe>
--- /hint --- --- /hints ---
