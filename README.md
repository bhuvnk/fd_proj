# fd_proj
HyperFace inspired architecture, leveraging multitask learning using VGG like backbone.

Example output:
[![Watch the video](https://img.youtube.com/vi/PfGYhnt4HaI/hqdefault.jpg)](https://www.youtube.com/watch?v=PfGYhnt4HaI)

What can it do:
1. Detect people coming and going in front of a static camera system. 
   - Moving toward the camera: Pink Box
   - Moving away: Blue Box
2. Unique ID for each person detected and tracking via Kalman Fiters.
3. Detect Faces of people coming toward the camera.
  - No Box
4. If face quality is adequate and person is looking at camera, further analysis is done.
  - Green Box
5. Age and gender are predicted for the person looking at the camera.
  - overlay on the Green Box

TODO:
1. Update cleaner source code.
2. Next step: Apply Mobilenet SSD kind of implematation with Kalman filter for tracking.
