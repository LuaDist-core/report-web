# Report for task 'install'

# Report for 'install lua 5.3.2 pkg'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving

- **Error:** Error getting dependency of "pkg 0.1-0": Package lua == 5.1 needed, but selected at version 5.3.2-1.
- Trying to force usage of 'lua 5.3.2-1' to solve dependency resolving issues
- **Error:** Error getting dependency of "pkg 0.1-0": Package lua == 5.1 needed, but installed at version 5.3.2-1.
- Trying to force usage of 'lua 5.2.4-1' to solve dependency resolving issues
- **Error:** Package lua 5.3.2 needed, but installed at version 5.2.4-1.
- Trying to force usage of 'lua 5.1.5-1' to solve dependency resolving issues
- **Error:** Package lua 5.3.2 needed, but installed at version 5.1.5-1.
- **Error:** Error getting dependency of "pkg 0.1-0": Package lua == 5.1 needed, but selected at version 5.3.2-1.

# Report for task 'require'

 -  - `require "pkg.version"` - FAIL - [[timeout: failed to run command ‘/home/travis/build/LuaDist-testing/_luadist_output/lua 5.3.2/install/bin/lua’: No such file or directory
]]

