# Report for 'install lua 5.1.5-1 lua-requests'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.1.5-1
- lbase64 20120820-1
- luasocket 3.0rc1-2
- md5 1.2-1
- lua-cjson 2.1.0.6-1
- luafilesystem 1.7.0-2
- lub 1.1.0-1
- xml 1.1.3-1
- luasec 0.7alpha-2
- lua-requests 1.1-1

## 3. Fetching packages

- **lua 5.1.5-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua 5.1.5-1
- **lbase64 20120820-1**
    - **remote:** git://github.com/LuaDist-testing/lbase64.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lbase64 20120820-1
- **luasocket 3.0rc1-2**
    - **remote:** git://github.com/LuaDist-testing/luasocket.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/luasocket 3.0rc1-2
- **md5 1.2-1**
    - **remote:** git://github.com/LuaDist-testing/md5.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/md5 1.2-1
- **lua-cjson 2.1.0.6-1**
    - **remote:** git://github.com/LuaDist-testing/lua-cjson.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua-cjson 2.1.0.6-1
- **luafilesystem 1.7.0-2**
    - **remote:** git://github.com/LuaDist-testing/luafilesystem.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/luafilesystem 1.7.0-2
- **lub 1.1.0-1**
    - **remote:** git://github.com/LuaDist-testing/lub.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lub 1.1.0-1
- **xml 1.1.3-1**
    - **remote:** git://github.com/LuaDist-testing/xml.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/xml 1.1.3-1
- **luasec 0.7alpha-2**
    - **remote:** git://github.com/LuaDist-testing/luasec.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/luasec 0.7alpha-2
- **lua-requests 1.1-1**
    - **remote:** git://github.com/LuaDist-testing/lua-requests.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua-requests 1.1-1

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

### lbase64 20120820-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lbase64 20120820-1/lbase64-20120820-1.rockspec'
- **Error:** Could not generate cmake commands for package 'lbase64 20120820-1': Unhandled rockspec build type: "module"
