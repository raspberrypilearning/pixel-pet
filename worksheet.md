# Interactive Space Pet

Using sensors and output devices are a great way to make your computer programs more interactive. The Raspberry Pi Sense HAT contains a whole set of sensors that can be used to detect movement, which will be used in this activity to take a digital pet for a walk. 

## Draw your Space Pet

First you'll need to design your pet avatar before you program any actions. 

1. Open a Terminal by clicking on **Menu**, **Accessories** and **Terminal**
1. Type `cd RPi_8x8GridDraw` and press **Enter** on the keyboard.
1. Next type `8x8grid-sense.py` This will run an application which you can use to draw your space pet avatar. 

	![8x8gridraw application](images/GUI.png)
	
1. Simply select the colour you wish to use from the grid with your mouse pointer and then select the circle in the grid to change it to that colour. You may wish to draw your picture out on square paper with colour pencils first instead like this:

	![square paper avatar](images/square-paper.png)	
	
## Code your Pet in Python 3



## Create a walking function

```python
def walking():
    for i in range(10):
        sense.set_pixels(pet1)
        time.sleep(0.5)
        sense.set_pixels(pet2)
        time.sleep(0.5)
```        

## Shake to trigger action


```python

x, y, z = sense.get_accelerometer_raw.values()

while x<2 and y<2 and z<2:
    x, y, z = sense.get_accelerometer_raw.values()

walking()
time.sleep(2)
```

## What next?
- Can you create more actions in order to look after your space pet?
    	