# optical-distance-measurement
 

# todo

- things to figrue out:
    - is focal length measured from object to camera lens or to camera sensor?
    - what effect does properties of the lens have on the calculations?

- known variables:
    - object distance (measurement of distance between object and sensor of camera)
    - object diameter (measurement of a FIXED axis of the object, e.g. width, height, any line drawn within the object)
    - image size (size of digital sensor typically in mm, if film, size of film in mm ie 35mm film)
    - focal length (focal length of the camera in mm)
    - angle of view (angle of view of the camera in degrees)
    - magnification (magnification of the lens)

- formulas: (pls verify formulas, the source is very sketch)
    - object distance = image size / (2 * tan(angle of view / 2))
    - object diameter = object distance * magnification
    - focal length = image size / (2 * tan(angle of view / 2))
    - images size = object distance * magnification OR image size = object diameter / magnification
    - angle of view = 2 * atan(image size / (2 * focal length))
    - magnification = image size / (2 * focal length) OR magnification = focal length / image size

- calibration stage: initial assessment of the camera properties, using multiple test images to calibrate the focal length of the camera.
- measurment stage: then, you have 2 fixed properties of the camera: the focal length and the sensor size.
    - use the camera to measure the distance between the two objects.
    - use the camera to measure the angle between the two objects.


- GUI stage: