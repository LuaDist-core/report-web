# Report for task 'install'

# Report for 'install lua 5.3.2 lua-spore'


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
- lpeg 1.0.1-1
- luajson 1.3.4-1
- lua-spore 0.3.3-1

## 3. Fetching packages

- **lua 5.3.2-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lua 5.3.2-1
- **luasocket 3.0rc1-2**
    - **remote:** git://github.com/LuaDist-testing/luasocket.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luasocket 3.0rc1-2
- **lpeg 1.0.1-1**
    - **remote:** git://github.com/LuaDist-testing/lpeg.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lpeg 1.0.1-1
- **luajson 1.3.4-1**
    - **remote:** git://github.com/LuaDist-testing/luajson.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luajson 1.3.4-1
- **lua-spore 0.3.3-1**
    - **remote:** git://github.com/LuaDist-testing/lua-spore.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lua-spore 0.3.3-1

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

### lpeg 1.0.1-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lpeg 1.0.1-1/lpeg-1.0.1-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lpeg 1.0.1-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lpeg 1.0.1-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lpeg 1.0.1-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lpeg 1.0.1-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lpeg 1.0.1-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/share/luadist2/manifest-file'

### luajson 1.3.4-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luajson 1.3.4-1/luajson-1.3.4-1.rockspec'
- **Error:** Could not generate cmake commands for package 'luajson 1.3.4-1': Unhandled rockspec build type: "module"
- **Error:** Error installing: Could not generate cmake commands for package 'luajson 1.3.4-1': Unhandled rockspec build type: "module"

# Report for task 'require'

 -  - `require "Spore"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore' not found:
	no field package.preload['Spore']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore.lua'
	no file './Spore.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/init.lua'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Core"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Core' not found:
	no field package.preload['Spore.Core']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Core.lua'
	no file './Spore/Core.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Core.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Core/init.lua'
	no file './Spore/Core.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Core.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.GoogleDiscovery"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.GoogleDiscovery' not found:
	no field package.preload['Spore.GoogleDiscovery']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/GoogleDiscovery.lua'
	no file './Spore/GoogleDiscovery.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/GoogleDiscovery.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/GoogleDiscovery/init.lua'
	no file './Spore/GoogleDiscovery.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/GoogleDiscovery.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Middleware.Auth.AWS"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Middleware.Auth.AWS' not found:
	no field package.preload['Spore.Middleware.Auth.AWS']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Middleware/Auth/AWS.lua'
	no file './Spore/Middleware/Auth/AWS.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Auth/AWS.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Auth/AWS/init.lua'
	no file './Spore/Middleware/Auth/AWS.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Auth/AWS.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Middleware.Auth.Basic"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Middleware.Auth.Basic' not found:
	no field package.preload['Spore.Middleware.Auth.Basic']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Middleware/Auth/Basic.lua'
	no file './Spore/Middleware/Auth/Basic.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Auth/Basic.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Auth/Basic/init.lua'
	no file './Spore/Middleware/Auth/Basic.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Auth/Basic.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Middleware.Auth.Bearer"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Middleware.Auth.Bearer' not found:
	no field package.preload['Spore.Middleware.Auth.Bearer']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Middleware/Auth/Bearer.lua'
	no file './Spore/Middleware/Auth/Bearer.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Auth/Bearer.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Auth/Bearer/init.lua'
	no file './Spore/Middleware/Auth/Bearer.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Auth/Bearer.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Middleware.Auth.DataPublica"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Middleware.Auth.DataPublica' not found:
	no field package.preload['Spore.Middleware.Auth.DataPublica']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Middleware/Auth/DataPublica.lua'
	no file './Spore/Middleware/Auth/DataPublica.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Auth/DataPublica.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Auth/DataPublica/init.lua'
	no file './Spore/Middleware/Auth/DataPublica.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Auth/DataPublica.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Middleware.Auth.Digest"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Middleware.Auth.Digest' not found:
	no field package.preload['Spore.Middleware.Auth.Digest']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Middleware/Auth/Digest.lua'
	no file './Spore/Middleware/Auth/Digest.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Auth/Digest.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Auth/Digest/init.lua'
	no file './Spore/Middleware/Auth/Digest.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Auth/Digest.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Middleware.Auth.OAuth"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Middleware.Auth.OAuth' not found:
	no field package.preload['Spore.Middleware.Auth.OAuth']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Middleware/Auth/OAuth.lua'
	no file './Spore/Middleware/Auth/OAuth.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Auth/OAuth.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Auth/OAuth/init.lua'
	no file './Spore/Middleware/Auth/OAuth.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Auth/OAuth.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Middleware.Cache"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Middleware.Cache' not found:
	no field package.preload['Spore.Middleware.Cache']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Middleware/Cache.lua'
	no file './Spore/Middleware/Cache.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Cache.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Cache/init.lua'
	no file './Spore/Middleware/Cache.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Cache.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Middleware.DoNotTrack"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Middleware.DoNotTrack' not found:
	no field package.preload['Spore.Middleware.DoNotTrack']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Middleware/DoNotTrack.lua'
	no file './Spore/Middleware/DoNotTrack.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/DoNotTrack.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/DoNotTrack/init.lua'
	no file './Spore/Middleware/DoNotTrack.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/DoNotTrack.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Middleware.Format.JSON"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Middleware.Format.JSON' not found:
	no field package.preload['Spore.Middleware.Format.JSON']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Middleware/Format/JSON.lua'
	no file './Spore/Middleware/Format/JSON.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Format/JSON.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Format/JSON/init.lua'
	no file './Spore/Middleware/Format/JSON.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Format/JSON.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Middleware.Format.XML"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Middleware.Format.XML' not found:
	no field package.preload['Spore.Middleware.Format.XML']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Middleware/Format/XML.lua'
	no file './Spore/Middleware/Format/XML.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Format/XML.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Format/XML/init.lua'
	no file './Spore/Middleware/Format/XML.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Format/XML.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Middleware.Format.YAML"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Middleware.Format.YAML' not found:
	no field package.preload['Spore.Middleware.Format.YAML']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Middleware/Format/YAML.lua'
	no file './Spore/Middleware/Format/YAML.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Format/YAML.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Format/YAML/init.lua'
	no file './Spore/Middleware/Format/YAML.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Format/YAML.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Middleware.Logging"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Middleware.Logging' not found:
	no field package.preload['Spore.Middleware.Logging']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Middleware/Logging.lua'
	no file './Spore/Middleware/Logging.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Logging.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Logging/init.lua'
	no file './Spore/Middleware/Logging.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Logging.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Middleware.Mock"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Middleware.Mock' not found:
	no field package.preload['Spore.Middleware.Mock']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Middleware/Mock.lua'
	no file './Spore/Middleware/Mock.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Mock.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Mock/init.lua'
	no file './Spore/Middleware/Mock.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Mock.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Middleware.Parameter.Default"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Middleware.Parameter.Default' not found:
	no field package.preload['Spore.Middleware.Parameter.Default']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Middleware/Parameter/Default.lua'
	no file './Spore/Middleware/Parameter/Default.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Parameter/Default.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Parameter/Default/init.lua'
	no file './Spore/Middleware/Parameter/Default.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Parameter/Default.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Middleware.Parameter.Force"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Middleware.Parameter.Force' not found:
	no field package.preload['Spore.Middleware.Parameter.Force']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Middleware/Parameter/Force.lua'
	no file './Spore/Middleware/Parameter/Force.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Parameter/Force.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Parameter/Force/init.lua'
	no file './Spore/Middleware/Parameter/Force.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Parameter/Force.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Middleware.Proxy.Basic"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Middleware.Proxy.Basic' not found:
	no field package.preload['Spore.Middleware.Proxy.Basic']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Middleware/Proxy/Basic.lua'
	no file './Spore/Middleware/Proxy/Basic.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Proxy/Basic.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Proxy/Basic/init.lua'
	no file './Spore/Middleware/Proxy/Basic.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Proxy/Basic.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Middleware.Redirection"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Middleware.Redirection' not found:
	no field package.preload['Spore.Middleware.Redirection']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Middleware/Redirection.lua'
	no file './Spore/Middleware/Redirection.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Redirection.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Redirection/init.lua'
	no file './Spore/Middleware/Redirection.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Redirection.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Middleware.Runtime"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Middleware.Runtime' not found:
	no field package.preload['Spore.Middleware.Runtime']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Middleware/Runtime.lua'
	no file './Spore/Middleware/Runtime.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Runtime.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Runtime/init.lua'
	no file './Spore/Middleware/Runtime.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/Runtime.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Middleware.UserAgent"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Middleware.UserAgent' not found:
	no field package.preload['Spore.Middleware.UserAgent']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Middleware/UserAgent.lua'
	no file './Spore/Middleware/UserAgent.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/UserAgent.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/UserAgent/init.lua'
	no file './Spore/Middleware/UserAgent.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Middleware/UserAgent.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Protocols"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Protocols' not found:
	no field package.preload['Spore.Protocols']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Protocols.lua'
	no file './Spore/Protocols.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Protocols.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Protocols/init.lua'
	no file './Spore/Protocols.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Protocols.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Request"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Request' not found:
	no field package.preload['Spore.Request']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Request.lua'
	no file './Spore/Request.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Request.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Request/init.lua'
	no file './Spore/Request.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Request.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.Swagger"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.Swagger' not found:
	no field package.preload['Spore.Swagger']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/Swagger.lua'
	no file './Spore/Swagger.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Swagger.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Swagger/init.lua'
	no file './Spore/Swagger.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/Swagger.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.WADL"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.WADL' not found:
	no field package.preload['Spore.WADL']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/WADL.lua'
	no file './Spore/WADL.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/WADL.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/WADL/init.lua'
	no file './Spore/WADL.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/WADL.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "Spore.XML"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'Spore.XML' not found:
	no field package.preload['Spore.XML']
	no file '/home/travis/build/LuaDist-testing/lua-spore/../_travis_scripts/Spore/XML.lua'
	no file './Spore/XML.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/XML.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/XML/init.lua'
	no file './Spore/XML.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore/XML.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/Spore.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]

