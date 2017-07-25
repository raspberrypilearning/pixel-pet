## Code your pet in Python 3

Now that you have your designs represented as letters in a grid or array, you can start to code them in Python.

- Click on **Menu** then **Programming**, followed by **Python 3 (IDLE)**. This will open the Python 3 shell window.
- Next, click on **File** and **New File** to open an empty text editor window. 
- Save this empty file as `space-pet.py`.
- First you will need to import all the modules and libraries you will need for this project in your code by typing:

	```python
	from sense_hat import SenseHat
	import time
	```
	
- Underneath type:

	```python
	sense = SenseHat()
	```	
	
	Note that capital letters, full stops and commas are very important in Python. Your code might not work if you do not include these.

- Next, create a `Variable` for each colour label in your pet design like this:

	```python
	p = (204, 0, 204) # Pink
	g = (0, 102, 102) #	 Dark Green
	w = (200, 200, 200) # White
	y = (204, 204, 0) # Yellow
	e = (0, 0, 0) # Empty
	```
	
	The numbers used here inside the brackets are `RGB` values, or `Red, Green and Blue` values. A mixture of these colours make different colours. The higher the number, the more of that colour it will contain. For example, `(255, 0, 0)` would make a solid red colour, whereas `(0, 255, 0)` would create a vivid green colour. 
	
	You can change these numbers in your code to get the colours that you want. 
	
- Next, use a `list` to store your pixel pet design like this:

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
	
	Here you have created a variable called `pet1` and stored a list of labels for each colour by using `[` at the start of each letter and `]` at the end. 
	
- Repeat for the second pixel pet design, using a different variable name like `pet2`.

- If you ran your code now nothing would happen, because so far you have only told the program to store information. To make something happen, you will need to write a command to call on that data and display your colours in the right order on the Sense HAT LED matrix. Type this command underneath your lists:

	```python
	sense.set_pixels(pet1)
	```
	
- Save your code by pressing `Ctrl` + `S` on the keyboard followed by `F5`. 


    <iframe src="https://trinket.io/embed/python/46300eab23" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>


	Note what happens. Why did only one of your pet designs display? It's because you have only called `pet1` in your command.
	
- Add a delay using the `sleep` function, and then call the second picture using the same command as before like this:

	```python
	sleep(0.5)
	sense.set_pixels(pet2)
	```					    	
	
	Save and run your code to see your pet.
	
	<iframe src="https://trinket.io/embed/python/ab748e4522" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

