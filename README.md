# hardware

This is project on the Raspberry Pi for the visually impaired, which does the following:
1. Converts colors to sound frequency
2. Converts distance to sound volume
3. Recognize image (using Google Vision) and announce via Text2Speech

Video of the thing in action: https://drive.google.com/file/d/1y-__aQhvv9eTKyljemb8jt6IZ_0YF0fH/view?usp=sharing

The image is captured via the Pi Camera, and the distance is gauged using the Ultrasonic sensor.

The main file is vision/main.ipynb. To run it, you need a Google Vision API key,
put it in the file "api-key.json" in the vision folder.

Separate parts are included in the root folder. Use them to test the hardware.
