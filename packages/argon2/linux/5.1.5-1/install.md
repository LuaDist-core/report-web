# Report for task 'install'

# Report for 'install lua 5.1.5-1 argon2'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.1.5-1
- argon2 3.0.0-1

## 3. Fetching packages

- **lua 5.1.5-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua 5.1.5-1
- **argon2 3.0.0-1**
    - **remote:** git://github.com/LuaDist-testing/argon2.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/argon2 3.0.0-1

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

### argon2 3.0.0-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/argon2 3.0.0-1/argon2-3.0.0-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/argon2 3.0.0-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/argon2 3.0.0-1-build'
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
- **Error:** Error building package 'argon2 3.0.0-1': Could not preload the CMake cache script '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/argon2 3.0.0-1-build/cmake.cache'
stdout:
loading initial cache file cache.cmake
-- The C compiler identification is GNU 4.8.4
-- The CXX compiler identification is GNU 4.8.4
-- Check for working C compiler: /usr/bin/gcc
-- Check for working C compiler: /usr/bin/gcc -- works
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Detecting C compile features
-- Detecting C compile features - done
-- Check for working CXX compiler: /usr/bin/c++
-- Check for working CXX compiler: /usr/bin/c++ -- works
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- Found Lua: /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/lib/liblua.so;/usr/lib/x86_64-linux-gnu/libm.so (found version "5.1.5") 
-- Configuring incomplete, errors occurred!
See also "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/argon2 3.0.0-1-build/CMakeFiles/CMakeOutput.log".

stderr:
CMake Error at CMakeLists.txt:71 (target_link_libraries):
  Target "argon2" of type MODULE_LIBRARY may not be linked into another
  target.  One may link only to STATIC or SHARED libraries, or to executables
  with the ENABLE_EXPORTS property set.



- **Error:** Error installing: Error building package 'argon2 3.0.0-1': Could not preload the CMake cache script '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/argon2 3.0.0-1-build/cmake.cache'
stdout:
loading initial cache file cache.cmake
-- The C compiler identification is GNU 4.8.4
-- The CXX compiler identification is GNU 4.8.4
-- Check for working C compiler: /usr/bin/gcc
-- Check for working C compiler: /usr/bin/gcc -- works
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Detecting C compile features
-- Detecting C compile features - done
-- Check for working CXX compiler: /usr/bin/c++
-- Check for working CXX compiler: /usr/bin/c++ -- works
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- Found Lua: /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/lib/liblua.so;/usr/lib/x86_64-linux-gnu/libm.so (found version "5.1.5") 
-- Configuring incomplete, errors occurred!
See also "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/argon2 3.0.0-1-build/CMakeFiles/CMakeOutput.log".

stderr:
CMake Error at CMakeLists.txt:71 (target_link_libraries):
  Target "argon2" of type MODULE_LIBRARY may not be linked into another
  target.  One may link only to STATIC or SHARED libraries, or to executables
  with the ENABLE_EXPORTS property set.




# Report for task 'require'

 -  - `require "argon2"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/lua: (command line):1: module 'argon2' not found:
	no field package.preload['argon2']
	no file '/home/travis/build/LuaDist-testing/argon2/../_travis_scripts/argon2.lua'
	no file './argon2.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/argon2.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/argon2/init.lua'
	no file './argon2/init.lua'
	no file './argon2.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/argon2.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: ?
]]

