# NorthStarToolbox
 Scripts and tools that help service Project North Star AR glasses

![Leap Positioning Tool](img/positioningTool.PNG)

## Leap Positioning Tool

After optical calibration the Leap Motion sensor data needs to be aligned with the AR optics space.

### Instructions [Youtube timelapse](https://www.youtube.com/watch?v=0LtfHAdqVtQ)

1) Move calibration file to StreamingAssets folder, click "Load JSON"

2) While holding "Spacebar," align Right Index finger with red sphere. Release key when red sphere is on bone tip (about 5mm from fingertip).

3) Capture many samples, varying depth and palm rotation. Click "Refine" or press the "S" key. Repeat process until hands align near and far.This may take several attempts. **The more varied the sampling, the better the result.**

4) Click "Save copy" to create a new version with adjusted values. New file will be saved inside the "Calibrations" folder.