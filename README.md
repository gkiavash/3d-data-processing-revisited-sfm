# Structure From Motion
Unipd, 3D data processing course, homework

In this repository, some parts of the original code is completed by the student.

## Prerequisites (in debian-based distro):

```sudo apt install build-essential cmake libboost-filesystem-dev libopencv-dev libomp-dev libceres-dev libyaml-cpp-dev libgtest-dev libeigen3-dev```

Build and run the executable:
```
mkdir build
cd build
cmake ..
make
```

```./basic_sfm <input data file> <output ply file>```

```./matcher <calibration parameters filename> <images folder filename><output data file> [focal length scale]```

## Datasets

In the /datasets folder there are two simple datasets and the corresponding calibration parameter file
