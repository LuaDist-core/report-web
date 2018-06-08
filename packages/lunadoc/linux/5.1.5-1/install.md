# Report for 'install lua 5.1.5-1 lunadoc'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.1.5-1
- discount 0.2.1-1
- lpeg 1.0.1-1
- alt-getopt 0.8.0-1
- luafilesystem 1.7.0-2
- moonscript 0.5.0-1
- etlua 1.3.0-1
- loadkit 1.1.0-1
- lunadoc 0.4-1

## 3. Fetching packages

- **lua 5.1.5-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua 5.1.5-1
- **discount 0.2.1-1**
    - **remote:** git://github.com/LuaDist-testing/discount.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/discount 0.2.1-1
- **lpeg 1.0.1-1**
    - **remote:** git://github.com/LuaDist-testing/lpeg.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lpeg 1.0.1-1
- **alt-getopt 0.8.0-1**
    - **remote:** git://github.com/LuaDist-testing/alt-getopt.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/alt-getopt 0.8.0-1
- **luafilesystem 1.7.0-2**
    - **remote:** git://github.com/LuaDist-testing/luafilesystem.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luafilesystem 1.7.0-2
- **moonscript 0.5.0-1**
    - **remote:** git://github.com/LuaDist-testing/moonscript.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/moonscript 0.5.0-1
- **etlua 1.3.0-1**
    - **remote:** git://github.com/LuaDist-testing/etlua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/etlua 1.3.0-1
- **loadkit 1.1.0-1**
    - **remote:** git://github.com/LuaDist-testing/loadkit.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/loadkit 1.1.0-1
- **lunadoc 0.4-1**
    - **remote:** git://github.com/LuaDist-testing/lunadoc.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lunadoc 0.4-1

## 4. Installing packages


### lua 5.1.5-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua 5.1.5-1/lua-5.1.5-1.rockspec'
- Package 'lua 5.1.5-1': using CMakeLists.txt provided by package itself
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua 5.1.5-1-build'
- **CMake Variables:**
    - `CMAKE_BUILD_WITH_INSTALL_RPATH` = FALSE
    - `CMAKE_INCLUDE_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/include
    - `CMAKE_INSTALL_NAME_DIR` = @executable_path/../lib
    - `CMAKE_INSTALL_PREFIX` = /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1
    - `CMAKE_INSTALL_RPATH` = $ORIGIN/../lib
    - `CMAKE_INSTALL_RPATH_USE_LINK_PATH` = TRUE
    - `CMAKE_LIBRARY_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/lib;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/bin
    - `CMAKE_PROGRAM_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/bin
    - `CMAKE_SKIP_BUILD_RPATH` = FALSE
    - `INSTALL_BIN` = bin
    - `INSTALL_CMOD` = lib/lua
    - `INSTALL_ETC` = etc
    - `INSTALL_LIB` = lib
    - `INSTALL_LMOD` = lib/lua
    - `INSTALL_SHARE` = share
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua 5.1.5-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua 5.1.5-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua 5.1.5-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/luadist2/manifest-file'

### discount 0.2.1-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/discount 0.2.1-1/discount-0.2.1-1.rockspec'
- **Error:** Could not generate cmake commands for package 'discount 0.2.1-1': Unhandled rockspec build type: "command"
