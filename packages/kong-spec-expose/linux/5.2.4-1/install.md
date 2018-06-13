# Report for task 'install'

# Report for 'install lua 5.2.4-1 kong-spec-expose'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.2.4-1
- kong-spec-expose 0.1-1

## 3. Fetching packages

- **lua 5.2.4-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/lua 5.2.4-1
- **kong-spec-expose 0.1-1**
    - **remote:** git://github.com/LuaDist-testing/kong-spec-expose.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/kong-spec-expose 0.1-1

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

### kong-spec-expose 0.1-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/kong-spec-expose 0.1-1/kong-spec-expose-0.1-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/kong-spec-expose 0.1-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/kong-spec-expose 0.1-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/kong-spec-expose 0.1-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/kong-spec-expose 0.1-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/tmp/kong-spec-expose 0.1-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/share/luadist2/manifest-file'

# Report for task 'require'

 -  - `require "kong.plugins.kong-spec-expose.access"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua: .../bin/../lib/lua/kong/plugins/kong-spec-expose/access.lua:2: module 'pl.stringx' not found:
	no field package.preload['pl.stringx']
	no file '/home/travis/build/LuaDist-testing/kong-spec-expose/../_travis_scripts/pl/stringx.lua'
	no file './pl/stringx.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/pl/stringx.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/pl/stringx/init.lua'
	no file './pl/stringx.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/pl/stringx.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/loadall.so'
	no file './pl.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/pl.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	.../bin/../lib/lua/kong/plugins/kong-spec-expose/access.lua:2: in main chunk
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "kong.plugins.kong-spec-expose.handler"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua: ...bin/../lib/lua/kong/plugins/kong-spec-expose/handler.lua:1: module 'kong.plugins.base_plugin' not found:
	no field package.preload['kong.plugins.base_plugin']
	no file '/home/travis/build/LuaDist-testing/kong-spec-expose/../_travis_scripts/kong/plugins/base_plugin.lua'
	no file './kong/plugins/base_plugin.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/kong/plugins/base_plugin.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/kong/plugins/base_plugin/init.lua'
	no file './kong/plugins/base_plugin.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/kong/plugins/base_plugin.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/loadall.so'
	no file './kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	...bin/../lib/lua/kong/plugins/kong-spec-expose/handler.lua:1: in main chunk
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "kong.plugins.kong-spec-expose.schema"` - OK

