# Install OpenCV & Mediapipe on Raspberry Pi4B

### Run on Raspberry Pi4B 4GB and based on Debian Buster (Raspberry Pi OS (Legacy))
![cap](https://user-images.githubusercontent.com/61585411/168199774-9175d642-9768-4f37-adfd-bc575da97876.png)
### Python version == 3.7.3

[Install OpenCV & Mediapipe on Raspberry Pi 4B](https://www.youtube.com/watch?v=j11CKdGFOWg) -YouTube demo


## Update and upgrade the Raspberry Pi OS
```sudo apt-get update```

```sudo apt-get upgrade```

## Install OpenCV related packages

HDF5 is a file format and library for storing scientific data. HDF5 was designed and implemented to address the deficiencies of HDF4.x. It has a more powerful and flexible data model, supports files larger than 2 GB, and supports parallel I/O.

```sudo apt-get install -y libhdf5-dev```

ATLAS is an approach for the automatic generation and optimization of numerical software. Currently ATLAS supplies optimized versions for the complete set of linear algebra kernels known as the Basic Linear Algebra Subroutines (BLAS), and a subset of the linear algebra routines in the LAPACK library.

```sudo apt-get install -y libatlas-base-dev```

Install JPEG-2000 library

```sudo apt-get install -y libjasper-dev```

Install QT GUI related packages

```sudo apt-get install -y libqtgui4```

```sudo apt-get install -y libqt4-test```

```sudo apt-get install -y python3-pyqt5```

## Install Python related packages

### Update pip package

```python3 -m pip install --upgrade pip```

### Update Numpy package

```python3 -m pip install --upgrade numpy==1.21.2```

### Install Matplotlib package

```python3 -m pip install matplotlib```

### Install imutils package

```python3 -m pip install imutils```

## Install OpenCV package

Install OpenCV with version 4.5.3.56 (has been tested and compatible with numpy 1.21.2)

```python3 -m pip install opencv-python==4.5.3.56```

## Install Mediapipe package

Install Mediapipe for Raspberry Pi 4

```python3 -m pip install mediapipe-rpi4==0.8.4.0```
