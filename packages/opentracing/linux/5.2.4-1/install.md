# Report for task 'install'

# Report for 'install lua 5.2.4-1 opentracing'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.2.4-1
- luatz 0.4-1
- luaossl 20180530-0
- opentracing 0.0.1-0

## 3. Fetching packages

- **lua 5.2.4-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/lua 5.2.4-1
- **luatz 0.4-1**
    - **remote:** git://github.com/LuaDist-testing/luatz.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/luatz 0.4-1
- **luaossl 20180530-0**
    - **remote:** git://github.com/LuaDist-testing/luaossl.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/luaossl 20180530-0
- **opentracing 0.0.1-0**
    - **remote:** git://github.com/LuaDist-testing/opentracing.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/opentracing 0.0.1-0

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

### luatz 0.4-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/luatz 0.4-1/luatz-0.4-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/luatz 0.4-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/luatz 0.4-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/luatz 0.4-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/luatz 0.4-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/luatz 0.4-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/share/luadist2/manifest-file'

### luaossl 20180530-0
- **Error:** Could not find rockspec for package 'luaossl 20180530-0', expected location: '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/luaossl 20180530-0/luaossl-20180530-0.rockspec'
- **Error:** Error installing: Could not find rockspec for package 'luaossl 20180530-0', expected location: '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/luaossl 20180530-0/luaossl-20180530-0.rockspec'

# Report for task 'require'

 -  - `require "opentracing"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua: (command line):1: module 'opentracing' not found:
	no field package.preload['opentracing']
	no file '/home/travis/build/LuaDist-testing/opentracing/../_travis_scripts/opentracing.lua'
	no file './opentracing.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/opentracing.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/opentracing/init.lua'
	no file './opentracing.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/opentracing.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "opentracing.span"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua: (command line):1: module 'opentracing.span' not found:
	no field package.preload['opentracing.span']
	no file '/home/travis/build/LuaDist-testing/opentracing/../_travis_scripts/opentracing/span.lua'
	no file './opentracing/span.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/opentracing/span.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/opentracing/span/init.lua'
	no file './opentracing/span.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/opentracing/span.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/loadall.so'
	no file './opentracing.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/opentracing.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "opentracing.span_context"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua: (command line):1: module 'opentracing.span_context' not found:
	no field package.preload['opentracing.span_context']
	no file '/home/travis/build/LuaDist-testing/opentracing/../_travis_scripts/opentracing/span_context.lua'
	no file './opentracing/span_context.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/opentracing/span_context.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/opentracing/span_context/init.lua'
	no file './opentracing/span_context.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/opentracing/span_context.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/loadall.so'
	no file './opentracing.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/opentracing.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "opentracing.tracer"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua: (command line):1: module 'opentracing.tracer' not found:
	no field package.preload['opentracing.tracer']
	no file '/home/travis/build/LuaDist-testing/opentracing/../_travis_scripts/opentracing/tracer.lua'
	no file './opentracing/tracer.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/opentracing/tracer.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/opentracing/tracer/init.lua'
	no file './opentracing/tracer.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/opentracing/tracer.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/loadall.so'
	no file './opentracing.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/opentracing.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]

