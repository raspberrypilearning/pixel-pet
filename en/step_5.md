### Animate your pet

So far, your pixel pet only changes when you type into the shell. To animate it fully, you will need to switch repeatedly between the pictures with a time delay.

You could write the commands out over and over again but it makes more sense to put them into a loop.

To complete this section you need to create a loop that runs ten times. Within the loop, the pets should be displayed on the Sense HAT, and be switched every half-second.

Have a look at the hints below to learn how to do this.

--- hints --- --- hint ---
1. Create a for loop that iterates over a range of 10
2. Within the for loop, set the first pet, sleep for half a second, and then set the second pet
3. Add a final sleep of half a second before the loop cycles around again
--- /hint --- --- hint ---
Here's some code that has been partially completed:

```python
for i in range(## Add a value here):
	## set your first pet
	sleep(0.5)
	## set your second pet
	sleep(0.5)
```

--- /hint --- --- hint ---
Here's a video showing you how to animate your pet:
<iframe width="560" height="315" src="https://www.youtube.com/embed/hdupFogp8D0" frameborder="0" allowfullscreen></iframe>
--- /hint --- --- /hints ---
