# optical-distance-measurement
 

# todo

- things to figrue out:
    - is focal length measured from object to camera lens or to camera sensor?
    - what effect does properties of the lens have on the calculations?

- known variables:
    - object distance The object distance is the distance of the object to the centre line of the lens. 
    - object diameter (measurement of a FIXED axis of the object, e.g. width, height, any line drawn within the object)
    - image distance: The image distance (sometimes confused with the focal length) is the distance of the image to the centre line of the lens. refer to uploaded charts.
    - image size (size of digital sensor typically in mm, if film, size of film in mm ie 35mm film)
    - focal length (focal length of the camera in mm)
    - angle of view (angle of view of the camera in degrees)
    - magnification (magnification of the lens)

- formulas: (pls verify formulas, the source is very sketch)
    - refer to formulas.png
    - update: the math checks out! see math checking.jpg

- calibration stage: initial assessment of the camera properties, using multiple test images to calibrate the focal length of the camera.
- measurment stage: then, you have 2 fixed properties of the camera: the focal length and the sensor size.
    - use the camera to measure the distance between the two objects.
    - use the camera to measure the angle between the two objects.


- GUI stage:
    - flutter AIO app?


# information

- The focal length of a lens, expressed in millimeters, is the distance from the lens’s optical center (or nodal point) to the image plane in the camera (often illustrated by a "Φ" on the top plate of a camera body) when the lens is focused at infinity. 
    - what about when the lens is not focused at infinity?
    - what about when the lens is not centered on the optical axis?

-  If you are an optical engineer, this is important stuff. For the photographer, however, we do not need to know about nodal points or why the 200mm lens in our closet is only 193mm long, to make great photos.
    - find out what this means


# calibration tips
- the more precise the calibration the better
    - the greater the distance between object and camera, the more precise the calibration
    - caveat when using tapemeasure: watch for droop in the measurement. if droop exists, it would not be even as accurate as calibrating with a ruler.


