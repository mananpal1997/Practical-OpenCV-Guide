# pydata-talk
Jupyter Notebooks for PyData talks

- For SudokuSolver, dowload the pre-trained model and labels into the resources folder. Download the content from [here](https://drive.google.com/drive/folders/0BzEeBAqEX505bU1kTW1WOENKZ3c?usp=sharing).

## Installation Instructions For OpenCV (Linux)

Run the following commands

1. Installing required packages (last command is optional, run only if you want to test python version)
  
  ```
  sudo apt-get install build-essential
  sudo apt-get install cmake git libgtk2.0-dev pkg-config libavcodec-dev libavformat-dev libswscale-dev
  sudo apt-get install python-dev python-numpy libtbb2 libtbb-dev libjpeg-dev libpng-dev libtiff-dev libjasper-dev libdc1394-22-dev
  ```
2. Downloading cmake
  
  ```
  sudo add-apt-repository ppa:george-edison55/cmake-3.x
  sudo apt-get update
  sudo apt-get install cmake
  ```
3. cd ~
4. Downloading opencv - wget https://github.com/Itseez/opencv/archive/2.4.13.zip
5. Building OpenCV
  
  ```
  unzip 2.4.13.zip
  cd opencv-2.4.13
  mkdir release
  cd release
  cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local ..
  make
  sudo make install
  ```


For Tensorflow, follow instructions [here](https://www.tensorflow.org/install/install_linux)
