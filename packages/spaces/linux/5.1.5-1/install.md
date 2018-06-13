# Report for task 'install'

# Report for 'install lua 5.1.5-1 spaces'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.1.5-1
- spaces 0.3-13

## 3. Fetching packages

- **lua 5.1.5-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua 5.1.5-1
- **spaces 0.3-13**
    - **remote:** git://github.com/LuaDist-testing/spaces.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13

## 4. Installing packages


### lua 5.1.5-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua 5.1.5-1/lua-5.1.5-1.rockspec'
- Package 'lua 5.1.5-1': using CMakeLists.txt provided by package itself
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua 5.1.5-1-build'
- **CMake Variables:**
    - `CMAKE_BUILD_WITH_INSTALL_RPATH` = FALSE
    - `CMAKE_INCLUDE_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/include
    - `CMAKE_INSTALL_NAME_DIR` = @executable_path/../lib
    - `CMAKE_INSTALL_PREFIX` = /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install
    - `CMAKE_INSTALL_RPATH` = $ORIGIN/../lib
    - `CMAKE_INSTALL_RPATH_USE_LINK_PATH` = TRUE
    - `CMAKE_LIBRARY_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/lib;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin
    - `CMAKE_PROGRAM_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin
    - `CMAKE_SKIP_BUILD_RPATH` = FALSE
    - `INSTALL_BIN` = bin
    - `INSTALL_CMOD` = lib/lua
    - `INSTALL_ETC` = etc
    - `INSTALL_LIB` = lib
    - `INSTALL_LMOD` = lib/lua
    - `INSTALL_SHARE` = share
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua 5.1.5-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua 5.1.5-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua 5.1.5-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/share/luadist2/manifest-file'

### spaces 0.3-13
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13/spaces-0.3-13.rockspec'
- Package 'spaces 0.3-13': using CMakeLists.txt provided by package itself
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13-build'
- **CMake Variables:**
    - `CMAKE_BUILD_TYPE` = Release
    - `CMAKE_BUILD_WITH_INSTALL_RPATH` = FALSE
    - `CMAKE_INCLUDE_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/include
    - `CMAKE_INSTALL_NAME_DIR` = @executable_path/../lib
    - `CMAKE_INSTALL_PREFIX` = /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install
    - `CMAKE_INSTALL_RPATH` = $ORIGIN/../lib
    - `CMAKE_INSTALL_RPATH_USE_LINK_PATH` = TRUE
    - `CMAKE_LIBRARY_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/lib;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin
    - `CMAKE_PROGRAM_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin
    - `CMAKE_SKIP_BUILD_RPATH` = FALSE
    - `INSTALL_BIN` = bin
    - `INSTALL_CMOD` = lib/lua
    - `INSTALL_ETC` = etc
    - `INSTALL_LIB` = lib
    - `INSTALL_LMOD` = lib/lua
    - `INSTALL_SHARE` = share
    - `INST_LIBDIR` = $(LIBDIR)
    - `LUA` = $(LUA)
    - `LUA_INCDIR` = $(LUA_INCDIR)
    - `LUA_LIBDIR` = $(LUA_LIBDIR)
- **Error:** Error building package 'spaces 0.3-13': Could not preload the CMake cache script '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13-build/cmake.cache'
stdout:
loading initial cache file cache.cmake
-- The C compiler identification is GNU 4.8.4
-- The CXX compiler identification is GNU 4.8.4
-- Check for working C compiler: /usr/bin/gcc
-- Check for working C compiler: /usr/bin/gcc -- works
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Detecting C compile features
-- Detecting C compile features - done
-- Check for working CXX compiler: /usr/bin/c++
-- Check for working CXX compiler: /usr/bin/c++ -- works
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- Configuring incomplete, errors occurred!
See also "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13-build/CMakeFiles/CMakeOutput.log".

stderr:
CMake Warning at /usr/local/cmake-3.9.2/share/cmake-3.9/Modules/FindBoost.cmake:767 (message):
  Imported targets not available for Boost version
Call Stack (most recent call first):
  /usr/local/cmake-3.9.2/share/cmake-3.9/Modules/FindBoost.cmake:871 (_Boost_COMPONENT_DEPENDENCIES)
  /usr/local/cmake-3.9.2/share/cmake-3.9/Modules/FindBoost.cmake:1501 (_Boost_MISSING_DEPENDENCIES)
  CMakeLists.txt:10 (find_package)


CMake Warning at /usr/local/cmake-3.9.2/share/cmake-3.9/Modules/FindBoost.cmake:767 (message):
  Imported targets not available for Boost version
Call Stack (most recent call first):
  /usr/local/cmake-3.9.2/share/cmake-3.9/Modules/FindBoost.cmake:871 (_Boost_COMPONENT_DEPENDENCIES)
  /usr/local/cmake-3.9.2/share/cmake-3.9/Modules/FindBoost.cmake:1501 (_Boost_MISSING_DEPENDENCIES)
  CMakeLists.txt:10 (find_package)


CMake Error at /usr/local/cmake-3.9.2/share/cmake-3.9/Modules/FindBoost.cmake:1878 (message):
  Unable to find the requested Boost libraries.

  Unable to find the Boost header files.  Please set BOOST_ROOT to the root
  directory containing Boost or BOOST_INCLUDEDIR to the directory containing
  Boost's headers.
Call Stack (most recent call first):
  CMakeLists.txt:10 (find_package)


CMake Error: The following variables are used in this project, but they are set to NOTFOUND.
Please set them or make sure they are set and tested correctly in the CMake files:
Boost_INCLUDE_DIR (ADVANCED)
   used as include directory in directory /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13
   used as include directory in directory /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13
   used as include directory in directory /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13
   used as include directory in directory /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13
   used as include directory in directory /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13
   used as include directory in directory /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13
   used as include directory in directory /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13


- **Error:** Error installing: Error building package 'spaces 0.3-13': Could not preload the CMake cache script '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13-build/cmake.cache'
stdout:
loading initial cache file cache.cmake
-- The C compiler identification is GNU 4.8.4
-- The CXX compiler identification is GNU 4.8.4
-- Check for working C compiler: /usr/bin/gcc
-- Check for working C compiler: /usr/bin/gcc -- works
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Detecting C compile features
-- Detecting C compile features - done
-- Check for working CXX compiler: /usr/bin/c++
-- Check for working CXX compiler: /usr/bin/c++ -- works
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- Configuring incomplete, errors occurred!
See also "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13-build/CMakeFiles/CMakeOutput.log".

stderr:
CMake Warning at /usr/local/cmake-3.9.2/share/cmake-3.9/Modules/FindBoost.cmake:767 (message):
  Imported targets not available for Boost version
Call Stack (most recent call first):
  /usr/local/cmake-3.9.2/share/cmake-3.9/Modules/FindBoost.cmake:871 (_Boost_COMPONENT_DEPENDENCIES)
  /usr/local/cmake-3.9.2/share/cmake-3.9/Modules/FindBoost.cmake:1501 (_Boost_MISSING_DEPENDENCIES)
  CMakeLists.txt:10 (find_package)


CMake Warning at /usr/local/cmake-3.9.2/share/cmake-3.9/Modules/FindBoost.cmake:767 (message):
  Imported targets not available for Boost version
Call Stack (most recent call first):
  /usr/local/cmake-3.9.2/share/cmake-3.9/Modules/FindBoost.cmake:871 (_Boost_COMPONENT_DEPENDENCIES)
  /usr/local/cmake-3.9.2/share/cmake-3.9/Modules/FindBoost.cmake:1501 (_Boost_MISSING_DEPENDENCIES)
  CMakeLists.txt:10 (find_package)


CMake Error at /usr/local/cmake-3.9.2/share/cmake-3.9/Modules/FindBoost.cmake:1878 (message):
  Unable to find the requested Boost libraries.

  Unable to find the Boost header files.  Please set BOOST_ROOT to the root
  directory containing Boost or BOOST_INCLUDEDIR to the directory containing
  Boost's headers.
Call Stack (most recent call first):
  CMakeLists.txt:10 (find_package)


CMake Error: The following variables are used in this project, but they are set to NOTFOUND.
Please set them or make sure they are set and tested correctly in the CMake files:
Boost_INCLUDE_DIR (ADVANCED)
   used as include directory in directory /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13
   used as include directory in directory /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13
   used as include directory in directory /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13
   used as include directory in directory /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13
   used as include directory in directory /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13
   used as include directory in directory /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13
   used as include directory in directory /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/spaces 0.3-13



# Report for task 'require'

Build type "cmake" not supported for testing module requires.

