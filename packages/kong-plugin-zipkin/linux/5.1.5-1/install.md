# Report for task 'install'

# Report for 'install lua 5.1.5-1 kong-plugin-zipkin'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.1.5-1
- lua-cjson 2.1.0.6-1
- lua-resty-http 0.12-0
- luatz 0.4-1
- luaossl 20180530-0
- opentracing 0.0.1-0
- kong-plugin-zipkin 0.0.1-0

## 3. Fetching packages

- **lua 5.1.5-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua 5.1.5-1
- **lua-cjson 2.1.0.6-1**
    - **remote:** git://github.com/LuaDist-testing/lua-cjson.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua-cjson 2.1.0.6-1
- **lua-resty-http 0.12-0**
    - **remote:** git://github.com/LuaDist-testing/lua-resty-http.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua-resty-http 0.12-0
- **luatz 0.4-1**
    - **remote:** git://github.com/LuaDist-testing/luatz.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/luatz 0.4-1
- **luaossl 20180530-0**
    - **remote:** git://github.com/LuaDist-testing/luaossl.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/luaossl 20180530-0
- **opentracing 0.0.1-0**
    - **remote:** git://github.com/LuaDist-testing/opentracing.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/opentracing 0.0.1-0
- **kong-plugin-zipkin 0.0.1-0**
    - **remote:** git://github.com/LuaDist-testing/kong-plugin-zipkin.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/kong-plugin-zipkin 0.0.1-0

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

### lua-cjson 2.1.0.6-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua-cjson 2.1.0.6-1/lua-cjson-2.1.0.6-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua-cjson 2.1.0.6-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua-cjson 2.1.0.6-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua-cjson 2.1.0.6-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua-cjson 2.1.0.6-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua-cjson 2.1.0.6-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/share/luadist2/manifest-file'

### lua-resty-http 0.12-0
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua-resty-http 0.12-0/lua-resty-http-0.12-0.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua-resty-http 0.12-0'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua-resty-http 0.12-0-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua-resty-http 0.12-0-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua-resty-http 0.12-0'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua-resty-http 0.12-0-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/share/luadist2/manifest-file'

### luatz 0.4-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/luatz 0.4-1/luatz-0.4-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/luatz 0.4-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/luatz 0.4-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/luatz 0.4-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/luatz 0.4-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/luatz 0.4-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/share/luadist2/manifest-file'

### luaossl 20180530-0
- **Error:** Could not find rockspec for package 'luaossl 20180530-0', expected location: '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/luaossl 20180530-0/luaossl-20180530-0.rockspec'
- **Error:** Error installing: Could not find rockspec for package 'luaossl 20180530-0', expected location: '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/luaossl 20180530-0/luaossl-20180530-0.rockspec'

# Report for task 'require'

 -  - `require "kong.plugins.zipkin.codec"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/lua: (command line):1: module 'kong.plugins.zipkin.codec' not found:
	no field package.preload['kong.plugins.zipkin.codec']
	no file '/home/travis/build/LuaDist-testing/kong-plugin-zipkin/../_travis_scripts/kong/plugins/zipkin/codec.lua'
	no file './kong/plugins/zipkin/codec.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/zipkin/codec.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/zipkin/codec/init.lua'
	no file './kong/plugins/zipkin/codec/init.lua'
	no file './kong/plugins/zipkin/codec.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/zipkin/codec.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
	no file './kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: ?
]]
 -  - `require "kong.plugins.zipkin.handler"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/lua: (command line):1: module 'kong.plugins.zipkin.handler' not found:
	no field package.preload['kong.plugins.zipkin.handler']
	no file '/home/travis/build/LuaDist-testing/kong-plugin-zipkin/../_travis_scripts/kong/plugins/zipkin/handler.lua'
	no file './kong/plugins/zipkin/handler.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/zipkin/handler.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/zipkin/handler/init.lua'
	no file './kong/plugins/zipkin/handler/init.lua'
	no file './kong/plugins/zipkin/handler.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/zipkin/handler.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
	no file './kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: ?
]]
 -  - `require "kong.plugins.zipkin.opentracing"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/lua: (command line):1: module 'kong.plugins.zipkin.opentracing' not found:
	no field package.preload['kong.plugins.zipkin.opentracing']
	no file '/home/travis/build/LuaDist-testing/kong-plugin-zipkin/../_travis_scripts/kong/plugins/zipkin/opentracing.lua'
	no file './kong/plugins/zipkin/opentracing.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/zipkin/opentracing.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/zipkin/opentracing/init.lua'
	no file './kong/plugins/zipkin/opentracing/init.lua'
	no file './kong/plugins/zipkin/opentracing.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/zipkin/opentracing.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
	no file './kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: ?
]]
 -  - `require "kong.plugins.zipkin.random_sampler"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/lua: (command line):1: module 'kong.plugins.zipkin.random_sampler' not found:
	no field package.preload['kong.plugins.zipkin.random_sampler']
	no file '/home/travis/build/LuaDist-testing/kong-plugin-zipkin/../_travis_scripts/kong/plugins/zipkin/random_sampler.lua'
	no file './kong/plugins/zipkin/random_sampler.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/zipkin/random_sampler.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/zipkin/random_sampler/init.lua'
	no file './kong/plugins/zipkin/random_sampler/init.lua'
	no file './kong/plugins/zipkin/random_sampler.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/zipkin/random_sampler.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
	no file './kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: ?
]]
 -  - `require "kong.plugins.zipkin.reporter"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/lua: (command line):1: module 'kong.plugins.zipkin.reporter' not found:
	no field package.preload['kong.plugins.zipkin.reporter']
	no file '/home/travis/build/LuaDist-testing/kong-plugin-zipkin/../_travis_scripts/kong/plugins/zipkin/reporter.lua'
	no file './kong/plugins/zipkin/reporter.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/zipkin/reporter.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/zipkin/reporter/init.lua'
	no file './kong/plugins/zipkin/reporter/init.lua'
	no file './kong/plugins/zipkin/reporter.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/zipkin/reporter.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
	no file './kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: ?
]]
 -  - `require "kong.plugins.zipkin.schema"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/lua: (command line):1: module 'kong.plugins.zipkin.schema' not found:
	no field package.preload['kong.plugins.zipkin.schema']
	no file '/home/travis/build/LuaDist-testing/kong-plugin-zipkin/../_travis_scripts/kong/plugins/zipkin/schema.lua'
	no file './kong/plugins/zipkin/schema.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/zipkin/schema.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/zipkin/schema/init.lua'
	no file './kong/plugins/zipkin/schema/init.lua'
	no file './kong/plugins/zipkin/schema.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/zipkin/schema.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
	no file './kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: ?
]]

