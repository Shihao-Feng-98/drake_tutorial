# Drake Tutorial

## Installation 
All installation method see [Installation and Quickstart](https://drake.mit.edu/installation.html).

### Using Drake via Python
Installation via pip see [Installation via Pip](https://drake.mit.edu/pip.html#stable-releases). 

```
pip3.8 install drake
sudo apt-get install --no-install-recommends libpython3.8 libx11-6 libsm6 libxt6 libglib2.0-0
```

### Using Drake via C++
Install Drake to ```/opt/drake```

```
curl -O https://drake-packages.csail.mit.edu/drake/nightly/drake-latest-focal.tar.gz
sudo tar -xvzf drake-latest-focal.tar.gz -C /opt
```

## Check 
### Python API
```
python3 example.py
```

### C++ API
See [CMake Project with an Installed Drake](https://github.com/RobotLocomotion/drake-external-examples/tree/main/drake_cmake_installed).
```
cd simple_continuous_time_system/build
cmake ..
make
./simple_continuous_time_system
```

## Tutorial
See [Drake Tutorial](https://drake.guzhaoyuan.com/). This tutorial is compiled with the bazel build tool. It has similar functions as CMake.


