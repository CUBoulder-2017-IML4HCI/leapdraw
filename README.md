# leapdraw

by Byron Becker, Urban Martin, and Maggie Patton

### Inspiration and Idea

The main idea behind the leapdraw project was to create a creative and easy to use drawing interface with the Leap Motion using Machine Learning. While we currently have the project model set up to recognize the left hand as a classifier and the right hand as the drawing hand, in the future we want to add additional features that will help people easily switch between their right and left hands.

### Usage

To open up the LeapDraw Project and use as is, Wekinator, Processing, and LeapOSC inputs must be installed. The project 2_Week_Demo.wekproj can then be opened in the Wekinator and is functioning (with limited training data of Maggie's hands).

### Gesture Classifiers
1. No left hand - draws with a white color
2. Fist - erases
3. Flat five fingers (w/spaced fingers) - draws a "peach" color
4. Peace sign - draws a teal color
5. "Surfer" Thumb and pinky out - draws with a different random color every time and osc message is received giving a "Rainbow" effect


