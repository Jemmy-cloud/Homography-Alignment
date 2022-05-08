# Homography Alignment

Automatic Panoramic to stitching Two images capturing the same scene in OpenCV using feature detection, homography linear blending and RANSAC algorithm for best-fit homograpy. Image stitching is one of the most successful applications in Computer Vision.

When I input two images with overlapped fields, I expect to obtain a wide panorama. Finally applying a weighted matrix as a mask for image blending.


## Sample 

### Input Images
<img src="https://github.com/Jemmy-cloud/Homography-Alignment/blob/master/unstitchedImages/left_image.png" width=400 height=400 >   <img src="https://github.com/Jemmy-cloud/Homography-Alignment/blob/master/unstitchedImages/right%20image.png" width=400 height=400 >

### Matching
![matching](https://user-images.githubusercontent.com/85626938/166119292-bc2436c7-ca00-4c1d-9aaf-67bbbfc3798e.png)

### Output image
![stitchedOutputProcessed](https://user-images.githubusercontent.com/85626938/166118022-dc4962b4-e04c-4db7-b763-29247e699115.png)




## ✨Dependency
- Python 3.10.4
- OpenCV 4.5.5


