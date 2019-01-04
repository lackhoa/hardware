# hardware

This is project on the Raspberry Pi for the visually impaired, which does the following:
1. Converts colors to sound frequency
2. Converts distance to sound volume
3. Recognize image (using Google Vision) and announce via Text2Speech

The image is captured via the Pi Camera, and the distance is gauged using the Ultrasonic sensor.

The main file is vision/main.ipynb. To run it, you need a Google Vision API key,
put it in the file "api-key.json" in the vision folder.

Separate parts are included in the root folder. Use them to test the hardware.
