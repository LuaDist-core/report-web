# Report for 'install lua 5.3.2 notifycenter'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.3.2-1
- luacurl 1.2.1-1
- lua-cjson 2.1.0.6-1
- notifycenter 0.0-1

## 3. Fetching packages

- **lua 5.3.2-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lua 5.3.2-1
- **luacurl 1.2.1-1**
    - **remote:** git://github.com/LuaDist-testing/luacurl.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luacurl 1.2.1-1
- **lua-cjson 2.1.0.6-1**
    - **remote:** git://github.com/LuaDist-testing/lua-cjson.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lua-cjson 2.1.0.6-1
- **notifycenter 0.0-1**
    - **remote:** git://github.com/LuaDist-testing/notifycenter.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/notifycenter 0.0-1

## 4. Installing packages


### lua 5.3.2-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lua 5.3.2-1/lua-5.3.2-1.rockspec'
- Package 'lua 5.3.2-1': using CMakeLists.txt provided by package itself
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lua 5.3.2-1-build'
- **CMake Variables:**
    - `CMAKE_BUILD_WITH_INSTALL_RPATH` = FALSE
    - `CMAKE_INCLUDE_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/include
    - `CMAKE_INSTALL_NAME_DIR` = @executable_path/../lib
    - `CMAKE_INSTALL_PREFIX` = /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install
    - `CMAKE_INSTALL_RPATH` = $ORIGIN/../lib
    - `CMAKE_INSTALL_RPATH_USE_LINK_PATH` = TRUE
    - `CMAKE_LIBRARY_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/lib;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin
    - `CMAKE_PROGRAM_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin
    - `CMAKE_SKIP_BUILD_RPATH` = FALSE
    - `INSTALL_BIN` = bin
    - `INSTALL_CMOD` = lib/lua
    - `INSTALL_ETC` = etc
    - `INSTALL_LIB` = lib
    - `INSTALL_LMOD` = lib/lua
    - `INSTALL_SHARE` = share
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lua 5.3.2-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lua 5.3.2-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lua 5.3.2-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/share/luadist2/manifest-file'

### luacurl 1.2.1-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luacurl 1.2.1-1/luacurl-1.2.1-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luacurl 1.2.1-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luacurl 1.2.1-1-build'
- **CMake Variables:**
    - `CMAKE_BUILD_WITH_INSTALL_RPATH` = FALSE
    - `CMAKE_INCLUDE_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/include
    - `CMAKE_INSTALL_NAME_DIR` = @executable_path/../lib
    - `CMAKE_INSTALL_PREFIX` = /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install
    - `CMAKE_INSTALL_RPATH` = $ORIGIN/../lib
    - `CMAKE_INSTALL_RPATH_USE_LINK_PATH` = TRUE
    - `CMAKE_LIBRARY_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/lib;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin
    - `CMAKE_PROGRAM_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin
    - `CMAKE_SKIP_BUILD_RPATH` = FALSE
    - `INSTALL_BIN` = bin
    - `INSTALL_CMOD` = lib/lua
    - `INSTALL_ETC` = etc
    - `INSTALL_LIB` = lib
    - `INSTALL_LMOD` = lib/lua
    - `INSTALL_SHARE` = share
- **Error:** Error building package 'luacurl 1.2.1-1': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luacurl 1.2.1-1-build'
stdout:
Scanning dependencies of target luacurl
[ 50%] Building C object CMakeFiles/luacurl.dir/luacurl.c.o

stderr:
/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luacurl 1.2.1-1/luacurl.c:813:30: error: array type has incomplete element type
 static const struct luaL_reg luacurl_meths[] =
                              ^
/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luacurl 1.2.1-1/luacurl.c:823:30: error: array type has incomplete element type
 static const struct luaL_reg luacurl_funcs[] =
                              ^
make[2]: *** [CMakeFiles/luacurl.dir/luacurl.c.o] Error 1
make[1]: *** [CMakeFiles/luacurl.dir/all] Error 2
make: *** [all] Error 2

