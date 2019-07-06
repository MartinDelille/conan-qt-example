[![Build Status](https://travis-ci.org/MartinDelille/conan-qt-example.svg?branch=master)](https://travis-ci.org/MartinDelille/conan-qt-example)

# conan-qt-example

An example of using Qt from conan:

```
conan remote add bincrafters https://api.bintray.com/conan/bincrafters/public-conan
conan install . --build=missing
source activate_run.sh
qmake conan-qt-example.pro
make
./conan-qt-example
```
