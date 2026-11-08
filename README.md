# SocketIo

## Description
Wrapper library for the Boost ASIO library.
																								 
## This Repository
https://github.com/mlbrock/SocketIo

## Related Repositories
* UtilityOld (in https://github.com/mlbrock/UtilityOld)

## External Dependencies
### Git
* Any recent version of git.
### GNU C++ Compiler
* GNU g++ 4.1.2 through gcc 16.1.1 are supported.
### Boost
* Boost 1.36 (in which version ASIO was added to Boost) through Boost 1.90 are supported.

## How-to Build
### Install external dependencies:
* Install git
* Install GNU g++
* Install Boost
### Get the related repositories and build them:
* Clone the related repositories:

    `git clone https://github.com/mlbrock/UtilityOld`

* Follow the build instructions in the related repositories README.md files.
### Get the current source distribution:
    git clone https://github.com/mlbrock/SocketIo
### Change to the cloned top-level directory:
    cd SocketIo
### Clean an existing build (if necessary):
    ./SimpleBuildDriver.sh clean
### Run the build script:
    ./SimpleBuildDriver.sh
### Check for build warnings or errors:
    grep -P '((warning)|(error)):' `ls -1 BuildResults.*|sort -r|head -n 1`

