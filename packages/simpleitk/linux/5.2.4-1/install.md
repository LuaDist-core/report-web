# Report for 'install lua 5.2.4-1 simpleitk'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.2.4-1
- simpleitk 1.1.0-0

## 3. Fetching packages

- **lua 5.2.4-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/lua 5.2.4-1
- **simpleitk 1.1.0-0**
    - **remote:** git://github.com/LuaDist-testing/simpleitk.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/simpleitk 1.1.0-0

## 4. Installing packages


### lua 5.2.4-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/lua 5.2.4-1/lua-5.2.4-1.rockspec'
- Package 'lua 5.2.4-1': using CMakeLists.txt provided by package itself
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/lua 5.2.4-1-build'
- **CMake Variables:**
    - `CMAKE_BUILD_WITH_INSTALL_RPATH` = FALSE
    - `CMAKE_INCLUDE_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/include
    - `CMAKE_INSTALL_NAME_DIR` = @executable_path/../lib
    - `CMAKE_INSTALL_PREFIX` = /home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install
    - `CMAKE_INSTALL_RPATH` = $ORIGIN/../lib
    - `CMAKE_INSTALL_RPATH_USE_LINK_PATH` = TRUE
    - `CMAKE_LIBRARY_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/lib;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin
    - `CMAKE_PROGRAM_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin
    - `CMAKE_SKIP_BUILD_RPATH` = FALSE
    - `INSTALL_BIN` = bin
    - `INSTALL_CMOD` = lib/lua
    - `INSTALL_ETC` = etc
    - `INSTALL_LIB` = lib
    - `INSTALL_LMOD` = lib/lua
    - `INSTALL_SHARE` = share
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/lua 5.2.4-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/lua 5.2.4-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/lua 5.2.4-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/share/luadist2/manifest-file'

### simpleitk 1.1.0-0
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/simpleitk 1.1.0-0/simpleitk-1.1.0-0.rockspec'
- Package 'simpleitk 1.1.0-0': using CMakeLists.txt provided by package itself
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/simpleitk 1.1.0-0-build'
- **CMake Variables:**
    - `CFLAGS:STRING` = $(CFLAGS)
    - `CMAKE_BUILD_TYPE` = $(CMAKE_BUILD_TYPE)
    - `CMAKE_BUILD_WITH_INSTALL_RPATH` = FALSE
    - `CMAKE_INCLUDE_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/include
    - `CMAKE_INSTALL_NAME_DIR` = @executable_path/../lib
    - `CMAKE_INSTALL_PREFIX` = /home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install
    - `CMAKE_INSTALL_RPATH` = $ORIGIN/../lib
    - `CMAKE_INSTALL_RPATH_USE_LINK_PATH` = TRUE
    - `CMAKE_LIBRARY_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/lib;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin
    - `CMAKE_PROGRAM_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin
    - `CMAKE_SKIP_BUILD_RPATH` = FALSE
    - `INSTALL_BIN` = bin
    - `INSTALL_CMOD` = lib/lua
    - `INSTALL_ETC` = etc
    - `INSTALL_LIB` = lib
    - `INSTALL_LMOD` = lib/lua
    - `INSTALL_SHARE` = share
    - `SimpleITK_VERSION` = 1.1.0
- **Error:** Error building package 'simpleitk 1.1.0-0': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/simpleitk 1.1.0-0-build'
stdout:
Scanning dependencies of target SimpleITKSuperbuild-download
[  6%] Creating directories for 'SimpleITKSuperbuild-download'
[ 12%] Performing download step (git clone) for 'SimpleITKSuperbuild-download'
Your branch is up to date with 'origin/master'.
[ 18%] No patch step for 'SimpleITKSuperbuild-download'
[ 25%] Performing update step for 'SimpleITKSuperbuild-download'
Current branch master is up to date.
[ 31%] No configure step for 'SimpleITKSuperbuild-download'
[ 37%] No build step for 'SimpleITKSuperbuild-download'
[ 43%] No install step for 'SimpleITKSuperbuild-download'
[ 50%] Completed 'SimpleITKSuperbuild-download'
[ 50%] Built target SimpleITKSuperbuild-download
Scanning dependencies of target SimpleITKSuperbuild
[ 56%] Creating directories for 'SimpleITKSuperbuild'
[ 62%] No download step for 'SimpleITKSuperbuild'
[ 68%] No patch step for 'SimpleITKSuperbuild'
[ 75%] No update step for 'SimpleITKSuperbuild'
[ 81%] Performing configure step for 'SimpleITKSuperbuild'
loading initial cache file /home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/simpleitk 1.1.0-0-build/SimpleITKSuperbuild-prefix/tmp/SimpleITKSuperbuild-cache-.cmake
-- Configuring incomplete, errors occurred!

stderr:
Cloning into 'SimpleITKSuperbuild'...
warning: redirecting to https://itk.org/SimpleITK.git/
Already on 'master'
warning: redirecting to https://itk.org/SimpleITK.git/
CMake Error: Error processing file: /home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/simpleitk 1.1.0-0-build/SimpleITKSuperbuild-prefix/tmp/SimpleITKSuperbuild-cache-.cmake
CMake Error at CMakeLists.txt:15 (cmake_minimum_required):
  CMake 3.10 or higher is required.  You are running version 3.9.2


make[2]: *** [SimpleITKSuperbuild-prefix/src/SimpleITKSuperbuild-stamp/SimpleITKSuperbuild-configure] Error 1
make[1]: *** [CMakeFiles/SimpleITKSuperbuild.dir/all] Error 2
make: *** [all] Error 2

