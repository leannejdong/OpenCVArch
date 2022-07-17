# Install OpenCV C++ on Arch Linux 

The instruction is very similar to Debian-based distro
https://docs.opencv.org/3.4/d7/d9f/tutorial_linux_install.html

## Dependency

`cmake, make, git, gtk2, pkgconf`

`cd ~/<my_working_directory>
git clone https://github.com/opencv/opencv.git`

`mkdir -p build && cd build`

`cmake ../opencv`

`make -j8`

If you did not encounter any error then OpenCV is installed successfully on your Linux system. The header files are at the location.

`/usr/local/include/opencv4`

# Verify installation 

`mkdir testCV && cd testCV`

`vim main.cpp`

`cmake .`

`make`


