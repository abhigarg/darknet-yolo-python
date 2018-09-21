# darknet-yolo-python

This script is an extension of original python script included in darknet-yolo repo to run model inference on video frames.

## Requirements
OpenCV for python - sudo pip install opencv-contrib-python

Build darknet as per steps given at https://pjreddie.com/darknet/yolo/ and copy the libdarknet.so file generated after successful build to the project folder. The .so file and this script should be in same directory or otherwise path to the .so file must be provided in the script.

The script is tested on Ubuntu 16.04 environment with CUDA-9.0 and Yolo v2/v3 versions are supported.

## Usuage
To run the script the path to cfg, weights, data files must be provided as given in darknet yolo description.

Video source could be a webcam or a video file



