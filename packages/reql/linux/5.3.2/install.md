# Report for task 'install'

# Report for 'install lua 5.3.2 reql'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.3.2-1
- luacrypto 0.3.2-2
- lpeg 1.0.1-1
- luajson 1.3.4-1
- luasocket 3.0rc1-2
- luasec 0.6-2
- semver 1.2.1-1
- reql 1.0.4-0

## 3. Fetching packages

- **lua 5.3.2-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lua 5.3.2-1
- **luacrypto 0.3.2-2**
    - **remote:** git://github.com/LuaDist-testing/luacrypto.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luacrypto 0.3.2-2
- **lpeg 1.0.1-1**
    - **remote:** git://github.com/LuaDist-testing/lpeg.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/lpeg 1.0.1-1
- **luajson 1.3.4-1**
    - **remote:** git://github.com/LuaDist-testing/luajson.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luajson 1.3.4-1
- **luasocket 3.0rc1-2**
    - **remote:** git://github.com/LuaDist-testing/luasocket.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luasocket 3.0rc1-2
- **luasec 0.6-2**
    - **remote:** git://github.com/LuaDist-testing/luasec.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luasec 0.6-2
- **semver 1.2.1-1**
    - **remote:** git://github.com/LuaDist-testing/semver.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/semver 1.2.1-1
- **reql 1.0.4-0**
    - **remote:** git://github.com/LuaDist-testing/reql.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/reql 1.0.4-0

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

### luacrypto 0.3.2-2
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luacrypto 0.3.2-2/luacrypto-0.3.2-2.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luacrypto 0.3.2-2'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luacrypto 0.3.2-2-build'
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
- **Error:** Error building package 'luacrypto 0.3.2-2': Could not preload the CMake cache script '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luacrypto 0.3.2-2-build/cmake.cache'
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
-- Found Lua: /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/lib/liblua.so;/usr/lib/x86_64-linux-gnu/libm.so (found version "5.3.2") 
-- Configuring incomplete, errors occurred!
See also "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luacrypto 0.3.2-2-build/CMakeFiles/CMakeOutput.log".

stderr:
CMake Warning at CMakeLists.txt:40 (find_package):
  By not providing "FindOPENSSL.cmake" in CMAKE_MODULE_PATH this project has
  asked CMake to find a package configuration file provided by "OPENSSL", but
  CMake did not find one.

  Could not find a package configuration file provided by "OPENSSL" with any
  of the following names:

    OPENSSLConfig.cmake
    openssl-config.cmake

  Add the installation prefix of "OPENSSL" to CMAKE_PREFIX_PATH or set
  "OPENSSL_DIR" to a directory containing one of the above files.  If
  "OPENSSL" provides a separate development package or SDK, be sure it has
  been installed.


CMake Error at CMakeLists.txt:84 (target_link_libraries):
  Target "crypto" of type MODULE_LIBRARY may not be linked into another
  target.  One may link only to STATIC or SHARED libraries, or to executables
  with the ENABLE_EXPORTS property set.



- **Error:** Error installing: Error building package 'luacrypto 0.3.2-2': Could not preload the CMake cache script '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luacrypto 0.3.2-2-build/cmake.cache'
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
-- Found Lua: /home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/lib/liblua.so;/usr/lib/x86_64-linux-gnu/libm.so (found version "5.3.2") 
-- Configuring incomplete, errors occurred!
See also "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/tmp/luacrypto 0.3.2-2-build/CMakeFiles/CMakeOutput.log".

stderr:
CMake Warning at CMakeLists.txt:40 (find_package):
  By not providing "FindOPENSSL.cmake" in CMAKE_MODULE_PATH this project has
  asked CMake to find a package configuration file provided by "OPENSSL", but
  CMake did not find one.

  Could not find a package configuration file provided by "OPENSSL" with any
  of the following names:

    OPENSSLConfig.cmake
    openssl-config.cmake

  Add the installation prefix of "OPENSSL" to CMAKE_PREFIX_PATH or set
  "OPENSSL_DIR" to a directory containing one of the above files.  If
  "OPENSSL" provides a separate development package or SDK, be sure it has
  been installed.


CMake Error at CMakeLists.txt:84 (target_link_libraries):
  Target "crypto" of type MODULE_LIBRARY may not be linked into another
  target.  One may link only to STATIC or SHARED libraries, or to executables
  with the ENABLE_EXPORTS property set.




# Report for task 'require'

Picking the first rockspec file from the following candidates:
{
  "./lua-reql-1.0.4-0.rockspec",
  "./reql-1.0.4-0.rockspec"
}
 -  - `require "rethinkdb"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb' not found:
	no field package.preload['rethinkdb']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb.lua'
	no file './rethinkdb.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/init.lua'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.connection"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.connection' not found:
	no field package.preload['rethinkdb.connection']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/connection.lua'
	no file './rethinkdb/connection.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/connection.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/connection/init.lua'
	no file './rethinkdb/connection.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/connection.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.connection_instance"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.connection_instance' not found:
	no field package.preload['rethinkdb.connection_instance']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/connection_instance.lua'
	no file './rethinkdb/connection_instance.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/connection_instance.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/connection_instance/init.lua'
	no file './rethinkdb/connection_instance.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/connection_instance.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.connector"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.connector' not found:
	no field package.preload['rethinkdb.connector']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/connector.lua'
	no file './rethinkdb/connector.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/connector.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/connector/init.lua'
	no file './rethinkdb/connector.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/connector.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.cursor"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.cursor' not found:
	no field package.preload['rethinkdb.cursor']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/cursor.lua'
	no file './rethinkdb/cursor.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/cursor.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/cursor/init.lua'
	no file './rethinkdb/cursor.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/cursor.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.depreciate"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.depreciate' not found:
	no field package.preload['rethinkdb.depreciate']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/depreciate.lua'
	no file './rethinkdb/depreciate.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/depreciate.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/depreciate/init.lua'
	no file './rethinkdb/depreciate.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/depreciate.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.errors"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.errors' not found:
	no field package.preload['rethinkdb.errors']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/errors.lua'
	no file './rethinkdb/errors.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/errors.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/errors/init.lua'
	no file './rethinkdb/errors.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/errors.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.internal.bits51"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.internal.bits51' not found:
	no field package.preload['rethinkdb.internal.bits51']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/internal/bits51.lua'
	no file './rethinkdb/internal/bits51.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/bits51.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/bits51/init.lua'
	no file './rethinkdb/internal/bits51.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/bits51.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.internal.bits53"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.internal.bits53' not found:
	no field package.preload['rethinkdb.internal.bits53']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/internal/bits53.lua'
	no file './rethinkdb/internal/bits53.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/bits53.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/bits53/init.lua'
	no file './rethinkdb/internal/bits53.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/bits53.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.internal.bytes_to_int"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.internal.bytes_to_int' not found:
	no field package.preload['rethinkdb.internal.bytes_to_int']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/internal/bytes_to_int.lua'
	no file './rethinkdb/internal/bytes_to_int.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/bytes_to_int.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/bytes_to_int/init.lua'
	no file './rethinkdb/internal/bytes_to_int.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/bytes_to_int.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.internal.convert_pseudotype"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.internal.convert_pseudotype' not found:
	no field package.preload['rethinkdb.internal.convert_pseudotype']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/internal/convert_pseudotype.lua'
	no file './rethinkdb/internal/convert_pseudotype.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/convert_pseudotype.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/convert_pseudotype/init.lua'
	no file './rethinkdb/internal/convert_pseudotype.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/convert_pseudotype.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.internal.current_handshake"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.internal.current_handshake' not found:
	no field package.preload['rethinkdb.internal.current_handshake']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/internal/current_handshake.lua'
	no file './rethinkdb/internal/current_handshake.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/current_handshake.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/current_handshake/init.lua'
	no file './rethinkdb/internal/current_handshake.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/current_handshake.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.internal.int_to_bytes"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.internal.int_to_bytes' not found:
	no field package.preload['rethinkdb.internal.int_to_bytes']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/internal/int_to_bytes.lua'
	no file './rethinkdb/internal/int_to_bytes.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/int_to_bytes.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/int_to_bytes/init.lua'
	no file './rethinkdb/internal/int_to_bytes.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/int_to_bytes.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.internal.pbkdf"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.internal.pbkdf' not found:
	no field package.preload['rethinkdb.internal.pbkdf']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/internal/pbkdf.lua'
	no file './rethinkdb/internal/pbkdf.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/pbkdf.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/pbkdf/init.lua'
	no file './rethinkdb/internal/pbkdf.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/pbkdf.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.internal.protect"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.internal.protect' not found:
	no field package.preload['rethinkdb.internal.protect']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/internal/protect.lua'
	no file './rethinkdb/internal/protect.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/protect.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/protect/init.lua'
	no file './rethinkdb/internal/protect.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/protect.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.internal.protocol"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.internal.protocol' not found:
	no field package.preload['rethinkdb.internal.protocol']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/internal/protocol.lua'
	no file './rethinkdb/internal/protocol.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/protocol.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/protocol/init.lua'
	no file './rethinkdb/internal/protocol.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/protocol.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.internal.protodef"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.internal.protodef' not found:
	no field package.preload['rethinkdb.internal.protodef']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/internal/protodef.lua'
	no file './rethinkdb/internal/protodef.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/protodef.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/protodef/init.lua'
	no file './rethinkdb/internal/protodef.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/protodef.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.internal.socket"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.internal.socket' not found:
	no field package.preload['rethinkdb.internal.socket']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/internal/socket.lua'
	no file './rethinkdb/internal/socket.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/socket.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/socket/init.lua'
	no file './rethinkdb/internal/socket.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/socket.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.internal.utilities"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.internal.utilities' not found:
	no field package.preload['rethinkdb.internal.utilities']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/internal/utilities.lua'
	no file './rethinkdb/internal/utilities.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/utilities.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/utilities/init.lua'
	no file './rethinkdb/internal/utilities.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/internal/utilities.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.reql"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.reql' not found:
	no field package.preload['rethinkdb.reql']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/reql.lua'
	no file './rethinkdb/reql.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/reql.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/reql/init.lua'
	no file './rethinkdb/reql.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/reql.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]
 -  - `require "rethinkdb.rtype"` - FAIL - [[/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua: (command line):1: module 'rethinkdb.rtype' not found:
	no field package.preload['rethinkdb.rtype']
	no file '/home/travis/build/LuaDist-testing/reql/../_travis_scripts/rethinkdb/rtype.lua'
	no file './rethinkdb/rtype.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/rtype.lua'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/rtype/init.lua'
	no file './rethinkdb/rtype.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb/rtype.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
	no file './rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/rethinkdb.so'
	no file '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/../lib/lua/loadall.so'
stack traceback:
	[C]: in function 'require'
	(command line):1: in main chunk
	[C]: in ?
]]

