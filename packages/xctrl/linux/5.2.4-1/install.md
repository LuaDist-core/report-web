# Report for 'install lua 5.2.4-1 xctrl'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.2.4-1
- xctrl 20101026-1

## 3. Fetching packages

- **lua 5.2.4-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/lua 5.2.4-1
- **xctrl 20101026-1**
    - **remote:** git://github.com/LuaDist-testing/xctrl.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/xctrl 20101026-1

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

### xctrl 20101026-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/xctrl 20101026-1/xctrl-20101026-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/xctrl 20101026-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/xctrl 20101026-1-build'
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
- **Error:** Error building package 'xctrl 20101026-1': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/xctrl 20101026-1-build'
stdout:
Scanning dependencies of target xctrl
[ 33%] Building C object CMakeFiles/xctrl.dir/src/xctrl.c.o
[ 66%] Building C object CMakeFiles/xctrl.dir/src/lxctrl.c.o

stderr:
/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/xctrl 20101026-1/src/lxctrl.c:724:30: error: array type has incomplete element type
 static const struct luaL_reg lwmc_funcs[] = {
                              ^
make[2]: *** [CMakeFiles/xctrl.dir/src/lxctrl.c.o] Error 1
make[1]: *** [CMakeFiles/xctrl.dir/all] Error 2
make: *** [all] Error 2

