# Report for 'install lua 5.1.5-1 commandlineui'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.1.5-1
- bit32 5.3.0-1
- std._debug 1.0-1
- std.normalize 2.0.2-1
- luaposix 34.0.4-1
- readline 1.8-0
- terminfo 1.5-0
- readkey 1.5-0
- lgdbm 20130702-2
- commandlineui 1.76-0

## 3. Fetching packages

- **lua 5.1.5-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua 5.1.5-1
- **bit32 5.3.0-1**
    - **remote:** git://github.com/LuaDist-testing/bit32.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/bit32 5.3.0-1
- **std._debug 1.0-1**
    - **remote:** git://github.com/LuaDist-testing/std._debug.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/std._debug 1.0-1
- **std.normalize 2.0.2-1**
    - **remote:** git://github.com/LuaDist-testing/std.normalize.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/std.normalize 2.0.2-1
- **luaposix 34.0.4-1**
    - **remote:** git://github.com/LuaDist-testing/luaposix.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/luaposix 34.0.4-1
- **readline 1.8-0**
    - **remote:** git://github.com/LuaDist-testing/readline.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/readline 1.8-0
- **terminfo 1.5-0**
    - **remote:** git://github.com/LuaDist-testing/terminfo.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/terminfo 1.5-0
- **readkey 1.5-0**
    - **remote:** git://github.com/LuaDist-testing/readkey.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/readkey 1.5-0
- **lgdbm 20130702-2**
    - **remote:** git://github.com/LuaDist-testing/lgdbm.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lgdbm 20130702-2
- **commandlineui 1.76-0**
    - **remote:** git://github.com/LuaDist-testing/commandlineui.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/commandlineui 1.76-0

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

### bit32 5.3.0-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/bit32 5.3.0-1/bit32-5.3.0-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/bit32 5.3.0-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/bit32 5.3.0-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/bit32 5.3.0-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/bit32 5.3.0-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/bit32 5.3.0-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/share/luadist2/manifest-file'

### std._debug 1.0-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/std._debug 1.0-1/std._debug-1.0-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/std._debug 1.0-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/std._debug 1.0-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/std._debug 1.0-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/std._debug 1.0-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/std._debug 1.0-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/share/luadist2/manifest-file'

### std.normalize 2.0.2-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/std.normalize 2.0.2-1/std.normalize-2.0.2-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/std.normalize 2.0.2-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/std.normalize 2.0.2-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/std.normalize 2.0.2-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/std.normalize 2.0.2-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/std.normalize 2.0.2-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/share/luadist2/manifest-file'

### luaposix 34.0.4-1
- **Error:** Could not find rockspec for package 'luaposix 34.0.4-1', expected location: '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/luaposix 34.0.4-1/luaposix-34.0.4-1.rockspec'
