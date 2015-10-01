# Interactive Space Pet

Short description of the resource

## Draw your Space Pet

1. Open a Terminal by clicking on **Menu**, **Accessories** and **Terminal**
1. Type `cd RPi_8x8GridDraw` and press **Enter** on the keyboard.
1. Next type `8x8grid-sense.py` This will run an application which you can use to draw your space pet avatar. 

	![8x8gridraw application](images/GUI.png)
	
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
    	