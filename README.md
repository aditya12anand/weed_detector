# weed_detector

This project is regarding detecting the weeds that are present on the plants with the help of image detection.

In this project, a mechanical rover has been created which is mounted with a camera connected to the Raspberry Pi where the python scripts will be executed that will help us to detect whether the plant is infected with weed or not.


Various python scripts have been written each for their own workings:-

a) weed.py -> It captures the image of the plant leaves and detects whether the plant has been infected by weed or not.

b) sprayer_fn.py -> It sprays the pesticides once weed is detected on the plant leaves

c) motor_fn.py -> It helps us to move the rover ahead once the whole process of spraying pesticide is done

