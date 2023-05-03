# Control_Lights_with_Eyes
CC341 Digital Electronics course project.

# Overview
Lights get turned on or off by detecting eye blink using opencv-python computer vision library and dlib machine learning library. 





https://user-images.githubusercontent.com/73821958/235842363-0d526072-dfcc-48b4-87fb-ecf503d0d61b.mp4

# Used software
- python 3.7  <br />
- opencv-python <br />
- numpy  <br />
- dlib  <br />
- imutils  <br />
- scipy  <br />
- serial  <br />
- Arduino ide  

# Electronic components
- Arduino board <br />
- 2 LEDs <br />
- webcam


https://user-images.githubusercontent.com/73821958/235843007-15ffd5f8-ba1c-41d9-9659-f621d75bc168.mp4

# Commands used 
- For detections using webcam video: <br />
' python detect_blinks.py --shape-predictor shape_predictor_68_face_landmarks.dat

- For detections using saved video: <br />
python detect_blinks.py --shape-predictor shape_predictor_68_face_landmarks.dat --video video_name.mp4 

# Resources
https://www.pyimagesearch.com/2017/04/24/eye-blink-detection-opencv-python-dlib/

