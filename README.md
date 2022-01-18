# Human Pose Estimation 

Human pose estimation is a rapidly evolving subject in the field of computer vision. Many companies, including tech giants like Microsoft, Google, Apple etc, have been working on building robust ML solutions for human pose estimation. The applications are limitless. For example, it can form the basis for sign language recognition, posture correction, exercise and finess, gesture control, and sports training. It can also enable the overlay of digital content on top of the physical world in augmented reality applications. 

In this notebook, we will demonstrate the use of Google's [**MediaPipe Pose**](https://google.github.io/mediapipe/solutions/pose.html) model to:

1. Detect and draw pose landmarks
2. Draw landmark connections
3. Acquire the pixel coordinates of landmarks

<br>
<center>
<img src="https://opencv.org/wp-content/uploads/2021/10/c0-m17-01-Feature-Image.png" alt="Human Pose Estimation">
</center>
<br>

The connected keypoint skeleton shown below is a way to visualize the human pose. Based on the position of the keypoints in 2D or 3D coordinate system, decisions can be taken. Apart from the skeleton-based model, other models that are used in human pose visualization are, contour-based and volume-based models. All of them have their advantages and disadvantages. MediaPipe uses a skeleton-based 3D model called Pose Landmark Model (BlazePose GHUM 3D). The landmark model predicts the location of 33 pose landmarks or keypoints as shown below.

<br>
<center>
<img src="https://opencv.org/wp-content/uploads/2021/10/c0-m17-mediapipe-pose-landmarks.png" alt="Pose landmarks">
</center>
<br>

## Output Sample

<img width="599" alt="Screen Shot 2022-01-18 at 7 57 12 AM" src="https://user-images.githubusercontent.com/42128166/149973626-79353ddb-4f75-4731-825b-4261eba35846.png">

(Video Source: https://www.pexels.com/video/man-practicing-kick-boxing-in-a-ring-5752183/)

