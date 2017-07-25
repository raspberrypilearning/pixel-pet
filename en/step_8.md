## Create a walking function

A `function` is a piece of code that you can use over and over. As the goal is to trigger the walking animation later on, it makes sense for us to put the animation code into a function that can be called when an action has been sensed by the hardware. 

- To put your code into a function, you simply need to add this line above your `for` loop and indent the lines beneath like this:

	```python
	def walking():	
		for i in range(10):
        	sense.set_pixels(pet1)
        	sleep(0.5)
        	sense.set_pixels(pet2)
        	sleep(0.5)
    ```

	The use of `def` here means that you are ***defining*** a function which you have called ***walking***.

- Now you need to call the function so at the bottom of your code type:

	```python
	walking()
	```			         	

