# Report for task 'install'

# Report for 'install lua 5.2.4-1 net'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving

- **Error:** Error getting dependency of "net 0.16.0-1": No suitable candidate for package "libtls >= 2.5.4" found.
- Trying to force usage of 'lua 5.3.2-1' to solve dependency resolving issues
- **Error:** Package lua 5.2.4-1 needed, but installed at version 5.3.2-1.
- Trying to force usage of 'lua 5.2.4-1' to solve dependency resolving issues
- **Error:** Error getting dependency of "net 0.16.0-1": No suitable candidate for package "libtls >= 2.5.4" found.
- Trying to force usage of 'lua 5.1.5-1' to solve dependency resolving issues
- **Error:** Package lua 5.2.4-1 needed, but installed at version 5.1.5-1.
- **Error:** Error getting dependency of "net 0.16.0-1": No suitable candidate for package "libtls >= 2.5.4" found.

# Report for task 'require'

 -  - `require "net"` - FAIL - [[timeout: failed to run command ‘/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua’: No such file or directory
]]
 -  - `require "net.dgram"` - FAIL - [[timeout: failed to run command ‘/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua’: No such file or directory
]]
 -  - `require "net.dgram.inet"` - FAIL - [[timeout: failed to run command ‘/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua’: No such file or directory
]]
 -  - `require "net.dgram.unix"` - FAIL - [[timeout: failed to run command ‘/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua’: No such file or directory
]]
 -  - `require "net.poll"` - FAIL - [[timeout: failed to run command ‘/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua’: No such file or directory
]]
 -  - `require "net.stream"` - FAIL - [[timeout: failed to run command ‘/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua’: No such file or directory
]]
 -  - `require "net.stream.inet"` - FAIL - [[timeout: failed to run command ‘/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua’: No such file or directory
]]
 -  - `require "net.stream.unix"` - FAIL - [[timeout: failed to run command ‘/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua’: No such file or directory
]]
 -  - `require "net.syscall"` - FAIL - [[timeout: failed to run command ‘/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua’: No such file or directory
]]
 -  - `require "net.unix"` - FAIL - [[timeout: failed to run command ‘/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua’: No such file or directory
]]

