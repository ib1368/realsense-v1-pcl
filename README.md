# realsense-v1-pcl
An example to use Intel ZR300 Camera with PointCloud library.


## What Is This Example For?

As noted in the realsense-v2 (https://github.com/IntelRealSense/librealsense) readme file, a PCL wrapper is provided. But at the same time, it is noted that for usage of camaras such as ZR300, we should use realsense-v1(https://github.com/IntelRealSense/librealsense/tree/v1.12.1) but this time, PCL wrapper is not provided.

There is an example of using PCL in Intel's articles using R200 camera (https://software.intel.com/en-us/articles/using-librealsense-and-pcl-to-create-point-cloud-data). I've tested the example with ZR300 camera. It is OK but there is a minor bug causing segmentation fault. I've solved it and put the correct example in the repository.

## Code Explanation

There is enough explanation in the Intel's website: https://software.intel.com/en-us/articles/using-librealsense-and-pcl-to-create-point-cloud-data

## How To Run Example

It is tested in Ubuntu 16.04.2

### Install Dependencies

See https://github.com/IntelRealSense/librealsense/blob/v1.12.1/doc/installation.md for installing ReaLsense v1.12.1.
See http://www.pointclouds.org/documentation/tutorials/compiling_pcl_posix.php for compiling PCL. I've used PCL 1.8.0 (https://github.com/PointCloudLibrary/pcl/tree/pcl-1.8.0).

### Building Example

* `mkdir build`
* `cd build`
* `cmake ..`
* `make -j`

### Run

* `./LRS_PCL`
