### Invisible Cloak

this will make anything invisible that is set inside the full_mask

how it works:

## Setup and Initialization:

The program uses OpenCV (cv2) for video capture and image processing
It uses NumPy (np) for array operations

## Background Capture:

The program initializes the webcam using cv2.VideoCapture(0)
It waits 3 seconds to let the camera stabilize
Then it captures 30 frames to create a stable background image

## Color Detection:

The program is set up to detect the color you defined in the full_mask (this is the "cloak" color)

## Invisibility Effect:

When the color is detected in the frame, it creates a mask
The mask is cleaned up using morphological operations to remove noise
