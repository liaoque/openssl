
add 
######    SSL_CTX_use_PrivateKey_file
######    SSL_CTX_use_certificate_chain_file
######    X_SSL_CTX_set_ciphersuites
######    X_SSL_CTX_set_mode
  
  
###### must openssl 1.1.1

> No package 'libssl' found 
> 
> Ubuntu: apt-get install libssl-dev
> 
> CentOS：yum install openssl-devel  
  
    
---

# OpenSSL bindings for Go

Please see http://godoc.org/github.com/spacemonkeygo/openssl for more info

### About

This repository is a fork of [Space Monkey Go OpenSSL bindings](https://github.com/spacemonkeygo/openssl)
maintained by Northern.tech. The project has been extended to cover more OpenSSL
function calls.

### License

Copyright (C) 2020 Northern.tech AS & others. See AUTHORS.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

### Using on macOS
1. Install [homebrew](http://brew.sh/)
2. `$ brew install openssl` or `$ brew install openssl@1.1`

### Using on Windows
1. Install [mingw-w64](http://mingw-w64.sourceforge.net/)
2. Install [pkg-config-lite](http://sourceforge.net/projects/pkgconfiglite)
3. Build (or install precompiled) openssl for mingw32-w64
4. Set __PKG\_CONFIG\_PATH__ to the directory containing openssl.pc
   (i.e. c:\mingw64\mingw64\lib\pkgconfig)
