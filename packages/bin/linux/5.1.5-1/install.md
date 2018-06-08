# Report for 'install lua 5.1.5-1 bin'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.1.5-1
- bin 5.0-6

## 3. Fetching packages

- **lua 5.1.5-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/lua 5.1.5-1
- **bin 5.0-6**
    - **remote:** git://github.com/LuaDist-testing/bin.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/bin 5.0-6

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

### bin 5.0-6
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/bin 5.0-6/bin-5.0-6.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/bin 5.0-6'
- Building into '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/bin 5.0-6-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/bin 5.0-6-build" && cmake -P cmake_install.cmake'
- **Error:** Could not install package 'bin 5.0-6' from directory '/home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/tmp/bin 5.0-6-build'
stdout:
-- Install configuration: ""
-- Installing: /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/share/bin
-- Installing: /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/lib/lua/bin/compressors/lzw.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/lib/lua/bin/converters/base64.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/lib/lua/bin/converters/base91.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/lib/lua/bin/hashes/md5.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/lib/lua/bin/init.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/lib/lua/bin/numbers/BigNum.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/lib/lua/bin/numbers/BigRat.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/lib/lua/bin/numbers/bits.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/lib/lua/bin/numbers/infinabits.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/lib/lua/bin/numbers/no_jit_bit.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_output/lua 5.1.5-1/install/lib/lua/bin/numbers/random.lua

stderr:
CMake Error at cmake_install.cmake:84 (file):
  file INSTALL cannot find
  "/home/travis/build/LuaDist-testing/_luadist_output/lua
  5.1.5-1/install/tmp/bin 5.0-6/bin/support/extrablocks.lua".


