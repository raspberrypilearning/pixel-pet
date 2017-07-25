## Animate your pet using a loop

So far, your pixel pet only changes once. To animate it fully, you will need to switch repeatedly between the pictures with a time delay. 

You could write the commands out over and over again but it makes more sense to put them into a loop. 

- Move to the end of your program and locate the `sense.set_pixels(pet1)` part. Amend it to look like this:

	```python
    for i in range(10):
        sense.set_pixels(pet1)
        sleep(0.5)
        sense.set_pixels(pet2)
        sleep(0.5)
	```
	
	Don't forget to add the extra `sleep(0.5)` on the last line and remember to indent the lines after `for i in range(10):`. Indenting those lines means that they are inside the `for` loop. This `for` loop with the `range` function will repeat the indented code ten times and then stop.

- Save and run your code to watch the animation.


    <iframe src="https://trinket.io/embed/python/3b41d00de6" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>


- You will notice that after the animation has completed, you are left with the same image still displayed on the LED matrix. There is a great function that you can use that will clear the LEDs. Add this line above your new loop to clear the LEDs when you first run your program:

	```python
	sense.clear()
	```

