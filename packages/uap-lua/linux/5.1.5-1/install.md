# Report for task 'install'

# Report for 'install lua 5.1.5-1 uap-lua'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.1.5-1
- lrexlib-pcre2 2.9.0-1
- datafile 0.4-1
- uap-lua 1.2-1

## 3. Fetching packages

- **lua 5.1.5-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua 5.1.5-1
- **lrexlib-pcre2 2.9.0-1**
    - **remote:** git://github.com/LuaDist-testing/lrexlib-pcre2.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lrexlib-pcre2 2.9.0-1
- **datafile 0.4-1**
    - **remote:** git://github.com/LuaDist-testing/datafile.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/datafile 0.4-1
- **uap-lua 1.2-1**
    - **remote:** git://github.com/LuaDist-testing/uap-lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/uap-lua 1.2-1

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

### lrexlib-pcre2 2.9.0-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lrexlib-pcre2 2.9.0-1/lrexlib-pcre2-2.9.0-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lrexlib-pcre2 2.9.0-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lrexlib-pcre2 2.9.0-1-build'
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
- **Error:** Error building package 'lrexlib-pcre2 2.9.0-1': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lrexlib-pcre2 2.9.0-1-build'
stdout:
Scanning dependencies of target rex_pcre2
[ 25%] Building C object CMakeFiles/rex_pcre2.dir/src/common.c.o
[ 50%] Building C object CMakeFiles/rex_pcre2.dir/src/pcre2/lpcre2.c.o

stderr:
/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lrexlib-pcre2 2.9.0-1/src/pcre2/lpcre2.c:9:19: fatal error: pcre2.h: No such file or directory
 #include <pcre2.h>
                   ^
compilation terminated.
make[2]: *** [CMakeFiles/rex_pcre2.dir/src/pcre2/lpcre2.c.o] Error 1
make[1]: *** [CMakeFiles/rex_pcre2.dir/all] Error 2
make: *** [all] Error 2

- **Error:** Error installing: Error building package 'lrexlib-pcre2 2.9.0-1': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lrexlib-pcre2 2.9.0-1-build'
stdout:
Scanning dependencies of target rex_pcre2
[ 25%] Building C object CMakeFiles/rex_pcre2.dir/src/common.c.o
[ 50%] Building C object CMakeFiles/rex_pcre2.dir/src/pcre2/lpcre2.c.o

stderr:
/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lrexlib-pcre2 2.9.0-1/src/pcre2/lpcre2.c:9:19: fatal error: pcre2.h: No such file or directory
 #include <pcre2.h>
                   ^
compilation terminated.
make[2]: *** [CMakeFiles/rex_pcre2.dir/src/pcre2/lpcre2.c.o] Error 1
make[1]: *** [CMakeFiles/rex_pcre2.dir/all] Error 2
make: *** [all] Error 2


# Report for task 'require'

 -  - `require "uap"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/lua: (command line):1: module 'uap' not found:
	no field package.preload['uap']
	no file '/home/travis/build/LuaDist-testing/uap-lua/../_travis_scripts/uap.lua'
	no file './uap.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/uap.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/uap/init.lua'
	no file './uap/init.lua'
	no file './uap.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/uap.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: ?
]]
 -  - `require "uap.patterns"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/lua: (command line):1: module 'uap.patterns' not found:
	no field package.preload['uap.patterns']
	no file '/home/travis/build/LuaDist-testing/uap-lua/../_travis_scripts/uap/patterns.lua'
	no file './uap/patterns.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/uap/patterns.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/uap/patterns/init.lua'
	no file './uap/patterns/init.lua'
	no file './uap/patterns.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/uap/patterns.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
	no file './uap.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/uap.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: ?
]]

