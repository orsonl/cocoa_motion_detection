# cocoa_motion_detection
This project contains motion detection algorithm from the paper entitled as "COCOA: Tracking in Aerial Imagery". 

One of the main challenge of tracking and visual odometry using aerial imagery is to distinguish moving object from background as the camera is also moving. 

The developed algorithm copes with the abovementioned challenge by integrating:

1. Grid-based foreground extraction 
2. Kanade–Lucas–Tomasi tracker
3. Object recognition 
4. Extended Kalman filter (EKF)

By seperating pixels belong to the background from those from the foreground, the 3D motion of the camera carried by an aerial vehicle can be estimated. 
