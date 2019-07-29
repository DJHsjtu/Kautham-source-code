# kautham installation
```shell
$ sudo apt install gcc g++ git cmake build-essential
$ sudo apt-get install libompl-dev libsoqt4-dev libcoin80-dev cmake libboost-system-dev libboost-serialization-dev libboost-thread-dev libfcl-dev libassimp-dev  libarmadillo-dev libode-dev libpugixml-dev libeigen3-dev   freeglut3-dev

$ cd
$ git clone https://github.com/usman151mrd/Kautham-source-code.git
$ cd Kautham-source-code
$ mkdir build
$ cd build
$ cmake ../      
$ make
$ sudo make install

# Run kautham
kautham-gui
