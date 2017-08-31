## Setting your colours

Now that you have your designs represented as letters in a grid or array, you can start to code them in Python.

- Click on **Menu**, then **Programming**, followed by **Python 3 (IDLE)**. This will open the Python 3 shell window.
- Next, click on **File** and then **New File** to open an empty text editor window. 
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

- You now need to create a set of tuples to represent the colours you have used in your design. Have a look at the two sections below if you are unsure how to do this.

[[[generic-theory-colours]]]

[[[generic-python-tuples]]]

- Have a look at the hints below if you need more help.

--- hints --- --- hint ---
Use the letters you chose earlier in your design as the names of your tuples. Then add in the three numbers that represent the colour, separated by commas and surrounded by parentheses.
--- /hint --- --- hint ---
If you wanted to code the colour red, then this would be a simple example of how to do that:
```python
r = (255, 0, 0)
```
--- /hint --- --- hint ---
Here's a video showing you how to set your colours:
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5J85lA0JJs" frameborder="0" allowfullscreen></iframe>
--- /hint --- --- /hints ---
