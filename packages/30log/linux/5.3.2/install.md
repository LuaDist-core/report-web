# Report for task 'install'

# Report for 'install lua 5.3.2 30log'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.3.2-1
- 30log 0.8.0-1

## 3. Fetching packages

- **lua 5.3.2-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lua 5.3.2-1
- **30log 0.8.0-1**
    - **remote:** git://github.com/LuaDist-testing/30log.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/30log 0.8.0-1

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

### 30log 0.8.0-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/30log 0.8.0-1/30log-0.8.0-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/30log 0.8.0-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/30log 0.8.0-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/30log 0.8.0-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/30log 0.8.0-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/30log 0.8.0-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/share/luadist2/manifest-file'

# Report for task 'require'

 -  - `require "30log"` - OK
 -  - `require "30log-clean"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module '30log-clean' not found:
	no field package.preload['30log-clean']
	no file '/home/travis/build/LuaDist-testing/30log/../_travis_scripts/30log-clean.lua'
	no file './30log-clean.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/30log-clean.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/30log-clean/init.lua'
	no file './30log-clean.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/30log-clean.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "30log-commons"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module '30log-commons' not found:
	no field package.preload['30log-commons']
	no file '/home/travis/build/LuaDist-testing/30log/../_travis_scripts/30log-commons.lua'
	no file './30log-commons.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/30log-commons.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/30log-commons/init.lua'
	no file './30log-commons.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/30log-commons.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "30log-global"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module '30log-global' not found:
	no field package.preload['30log-global']
	no file '/home/travis/build/LuaDist-testing/30log/../_travis_scripts/30log-global.lua'
	no file './30log-global.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/30log-global.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/30log-global/init.lua'
	no file './30log-global.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/30log-global.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "30log-singleton"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module '30log-singleton' not found:
	no field package.preload['30log-singleton']
	no file '/home/travis/build/LuaDist-testing/30log/../_travis_scripts/30log-singleton.lua'
	no file './30log-singleton.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/30log-singleton.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/30log-singleton/init.lua'
	no file './30log-singleton.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/30log-singleton.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]

