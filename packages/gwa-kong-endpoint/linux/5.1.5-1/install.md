# Report for task 'install'

# Report for 'install lua 5.1.5-1 gwa-kong-endpoint'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.1.5-1
- gwa-kong-endpoint 1.2.3-0

## 3. Fetching packages

- **lua 5.1.5-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua 5.1.5-1
- **gwa-kong-endpoint 1.2.3-0**
    - **remote:** git://github.com/LuaDist-testing/gwa-kong-endpoint.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/gwa-kong-endpoint 1.2.3-0

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

### gwa-kong-endpoint 1.2.3-0
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/gwa-kong-endpoint 1.2.3-0/gwa-kong-endpoint-1.2.3-0.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/gwa-kong-endpoint 1.2.3-0'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/gwa-kong-endpoint 1.2.3-0-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/gwa-kong-endpoint 1.2.3-0-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/gwa-kong-endpoint 1.2.3-0'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/gwa-kong-endpoint 1.2.3-0-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/share/luadist2/manifest-file'

# Report for task 'require'

 -  - `require "kong.plugins.bcgov-gwa-endpoint.access"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/lua: ..../lib/lua/kong/plugins/bcgov-gwa-endpoint/access.lua:1: module 'kong.tools.utils' not found:
	no field package.preload['kong.tools.utils']
	no file '/home/travis/build/LuaDist-testing/gwa-kong-endpoint/../_travis_scripts/kong/tools/utils.lua'
	no file './kong/tools/utils.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/tools/utils.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/tools/utils/init.lua'
	no file './kong/tools/utils/init.lua'
	no file './kong/tools/utils.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/tools/utils.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
	no file './kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	..../lib/lua/kong/plugins/bcgov-gwa-endpoint/access.lua:1: in main chunk
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: ?
]]
 -  - `require "kong.plugins.bcgov-gwa-endpoint.api"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/lua: ...n/../lib/lua/kong/plugins/bcgov-gwa-endpoint/api.lua:1: module 'cjson' not found:
	no field package.preload['cjson']
	no file '/home/travis/build/LuaDist-testing/gwa-kong-endpoint/../_travis_scripts/cjson.lua'
	no file './cjson.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/cjson.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/cjson/init.lua'
	no file './cjson/init.lua'
	no file './cjson.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/cjson.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	...n/../lib/lua/kong/plugins/bcgov-gwa-endpoint/api.lua:1: in main chunk
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: ?
]]
 -  - `require "kong.plugins.bcgov-gwa-endpoint.daos"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/lua: .../../lib/lua/kong/plugins/bcgov-gwa-endpoint/daos.lua:1: module 'kong.singletons' not found:
	no field package.preload['kong.singletons']
	no file '/home/travis/build/LuaDist-testing/gwa-kong-endpoint/../_travis_scripts/kong/singletons.lua'
	no file './kong/singletons.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/singletons.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/singletons/init.lua'
	no file './kong/singletons/init.lua'
	no file './kong/singletons.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/singletons.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
	no file './kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	.../../lib/lua/kong/plugins/bcgov-gwa-endpoint/daos.lua:1: in main chunk
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: ?
]]
 -  - `require "kong.plugins.bcgov-gwa-endpoint.handler"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/lua: .../lib/lua/kong/plugins/bcgov-gwa-endpoint/handler.lua:1: module 'kong.plugins.base_plugin' not found:
	no field package.preload['kong.plugins.base_plugin']
	no file '/home/travis/build/LuaDist-testing/gwa-kong-endpoint/../_travis_scripts/kong/plugins/base_plugin.lua'
	no file './kong/plugins/base_plugin.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/base_plugin.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/base_plugin/init.lua'
	no file './kong/plugins/base_plugin/init.lua'
	no file './kong/plugins/base_plugin.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong/plugins/base_plugin.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
	no file './kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/kong.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	.../lib/lua/kong/plugins/bcgov-gwa-endpoint/handler.lua:1: in main chunk
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: ?
]]
 -  - `require "kong.plugins.bcgov-gwa-endpoint.migrations.cassandra"` - OK
 -  - `require "kong.plugins.bcgov-gwa-endpoint.migrations.postgres"` - OK
 -  - `require "kong.plugins.bcgov-gwa-endpoint.schema"` - OK

