# Report for task 'install'

# Report for 'install lua 5.3.2 lua-minittp'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.3.2-1
- luasocket 3.0rc1-2
- coxpcall 1.17.0-1
- copas 2.0.2-1
- luaposix 33.2.1-1
- lua-minittp 0.1-1

## 3. Fetching packages

- **lua 5.3.2-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lua 5.3.2-1
- **luasocket 3.0rc1-2**
    - **remote:** git://github.com/LuaDist-testing/luasocket.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luasocket 3.0rc1-2
- **coxpcall 1.17.0-1**
    - **remote:** git://github.com/LuaDist-testing/coxpcall.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/coxpcall 1.17.0-1
- **copas 2.0.2-1**
    - **remote:** git://github.com/LuaDist-testing/copas.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/copas 2.0.2-1
- **luaposix 33.2.1-1**
    - **remote:** git://github.com/LuaDist-testing/luaposix.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luaposix 33.2.1-1
- **lua-minittp 0.1-1**
    - **remote:** git://github.com/LuaDist-testing/lua-minittp.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lua-minittp 0.1-1

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

### luasocket 3.0rc1-2
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luasocket 3.0rc1-2/luasocket-3.0rc1-2.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luasocket 3.0rc1-2'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luasocket 3.0rc1-2-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luasocket 3.0rc1-2-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luasocket 3.0rc1-2'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luasocket 3.0rc1-2-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/share/luadist2/manifest-file'

### coxpcall 1.17.0-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/coxpcall 1.17.0-1/coxpcall-1.17.0-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/coxpcall 1.17.0-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/coxpcall 1.17.0-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/coxpcall 1.17.0-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/coxpcall 1.17.0-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/coxpcall 1.17.0-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/share/luadist2/manifest-file'

### copas 2.0.2-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/copas 2.0.2-1/copas-2.0.2-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/copas 2.0.2-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/copas 2.0.2-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/copas 2.0.2-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/copas 2.0.2-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/copas 2.0.2-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/share/luadist2/manifest-file'

### luaposix 33.2.1-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luaposix 33.2.1-1/luaposix-33.2.1-1.rockspec'
- **Error:** Could not generate cmake commands for package 'luaposix 33.2.1-1': Unhandled rockspec build type: "command"
- **Error:** Error installing: Could not generate cmake commands for package 'luaposix 33.2.1-1': Unhandled rockspec build type: "command"

# Report for task 'require'

 -  - `require "minittp"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'minittp' not found:
	no field package.preload['minittp']
	no file '/home/travis/build/LuaDist-testing/lua-minittp/../_travis_scripts/minittp.lua'
	no file './minittp.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/minittp.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/minittp/init.lua'
	no file './minittp.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/minittp.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "minittp_engine"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'minittp_engine' not found:
	no field package.preload['minittp_engine']
	no file '/home/travis/build/LuaDist-testing/lua-minittp/../_travis_scripts/minittp_engine.lua'
	no file './minittp_engine.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/minittp_engine.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/minittp_engine/init.lua'
	no file './minittp_engine.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/minittp_engine.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "minittp_fcgi"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'minittp_fcgi' not found:
	no field package.preload['minittp_fcgi']
	no file '/home/travis/build/LuaDist-testing/lua-minittp/../_travis_scripts/minittp_fcgi.lua'
	no file './minittp_fcgi.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/minittp_fcgi.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/minittp_fcgi/init.lua'
	no file './minittp_fcgi.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/minittp_fcgi.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "minittp_io"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'minittp_io' not found:
	no field package.preload['minittp_io']
	no file '/home/travis/build/LuaDist-testing/lua-minittp/../_travis_scripts/minittp_io.lua'
	no file './minittp_io.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/minittp_io.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/minittp_io/init.lua'
	no file './minittp_io.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/minittp_io.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "minittp_util"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'minittp_util' not found:
	no field package.preload['minittp_util']
	no file '/home/travis/build/LuaDist-testing/lua-minittp/../_travis_scripts/minittp_util.lua'
	no file './minittp_util.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/minittp_util.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/minittp_util/init.lua'
	no file './minittp_util.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/minittp_util.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]

