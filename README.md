# realsense-v1-pcl
An example to use Intel ZR300 Camera with PointCloud library.


## What Is This Example For?

As noted in the realsense-v2 (https://github.com/IntelRealSense/librealsense) readme file, a PCL wrapper is provided. But at the same time, it is noted that for usage of camaras such as ZR300, we should use realsense-v1(https://github.com/IntelRealSense/librealsense/tree/v1.12.1) but this time, PCL wrapper is not provided.

There is an example of using PCL in Intel's articles using R200 camera (https://software.intel.com/en-us/articles/using-librealsense-and-pcl-to-create-point-cloud-data). I've tested the example with ZR300 camera. It is OK but there is a minor bug causing segmentation fault. I've solved it and put the correct example in the repository.

## Code Explanation

There is enough explanation in the Intel's website: https://software.intel.com/en-us/articles/using-librealsense-and-pcl-to-create-point-cloud-data
