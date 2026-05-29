## Shake to activate

It's time to use the Sense HAT's movement sensors, in particular its accelerometer, to trigger the `walking` function you've created. This will make the project more interactive.

You'll need an infinite loop to begin with. Within the loop, you need to fetch the **raw** accelerometer readings. If the `x`, `y`, or `z` component of the accelerometer reading is above `2`, then your `walking()` function should be called.

If everything works correctly, shaking the Sense HAT will then animate your pixel pet!

Take a look at the hints below for help with writing the script.

--- hints ---
--- hint ---
Here's a video showing you how the script can be written:
<iframe width="560" height="315" src="https://www.youtube.com/embed/6l7HDCmYKCQ" frameborder="0" allowfullscreen></iframe>
--- /hint ---
--- /hints ---

