# Report for task 'install'

# Report for 'install lua 5.2.4-1 nvim-client'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving

- **Error:** Error getting dependency of "nvim-client 0.0.1-26": No suitable candidate for package "luv" found.
- Trying to force usage of 'lua 5.3.2-1' to solve dependency resolving issues
- **Error:** Package lua 5.2.4-1 needed, but installed at version 5.3.2-1.
- Trying to force usage of 'lua 5.2.4-1' to solve dependency resolving issues
- **Error:** Error getting dependency of "nvim-client 0.0.1-26": No suitable candidate for package "luv" found.
- Trying to force usage of 'lua 5.1.5-1' to solve dependency resolving issues
- **Error:** Package lua 5.2.4-1 needed, but installed at version 5.1.5-1.
- **Error:** Error getting dependency of "nvim-client 0.0.1-26": No suitable candidate for package "luv" found.

# Report for task 'require'

 -  - `require "nvim.child_process_stream"` - FAIL - [[timeout: failed to run command ‘/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua’: No such file or directory
]]
 -  - `require "nvim.msgpack_rpc_stream"` - FAIL - [[timeout: failed to run command ‘/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua’: No such file or directory
]]
 -  - `require "nvim.native"` - FAIL - [[timeout: failed to run command ‘/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua’: No such file or directory
]]
 -  - `require "nvim.session"` - FAIL - [[timeout: failed to run command ‘/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua’: No such file or directory
]]
 -  - `require "nvim.socket_stream"` - FAIL - [[timeout: failed to run command ‘/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua’: No such file or directory
]]
 -  - `require "nvim.stdio_stream"` - FAIL - [[timeout: failed to run command ‘/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua’: No such file or directory
]]
 -  - `require "nvim.tcp_stream"` - FAIL - [[timeout: failed to run command ‘/home/travis/build/LuaDist-testing/_luadist_output/lua 5.2.4-1/install/bin/lua’: No such file or directory
]]

