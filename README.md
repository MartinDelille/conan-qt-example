[![Build Status](https://travis-ci.org/MartinDelille/conan-qt-example.svg?branch=master)](https://travis-ci.org/MartinDelille/conan-qt-example)

# conan-qt-example

An example of using Qt from conan:

```
conan remote add bincrafters https://api.bintray.com/conan/bincrafters/public-conan
conan install . --build=missing
source activate.sh
PATH=$CMAKE_PREFIX_PATH/bin:$PATH
qmake conan-qt-example.pro
make
./conan-qt-example
```
