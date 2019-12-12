## WebAssembly QuickStart 
WebAssembly QuickStart Project 

### Enviroment MacOs 

```shell
$ git clone https://github.com/emscripten-core/emsdk.git
$ cd emsdk
$ git pull
$ ./emsdk install latest
$ ./emsdk activate latest
$ source ./emsdk_env.sh
$ $ emcc -v
cache:INFO: generating system asset: is_vanilla.txt..
cache:INFO:  - ok
emcc (Emscripten gcc/clang-like replacement + linker emulating GNU ld) 1.39.4
clang version 10.0.0 (/b/s/w/ir/cache/git/chromium.googlesource.com-external-github.com-llvm-llvm--project b5f295ffcec2fa7402e39eb1262acbd55a7d39f5)
Target: x86_64-apple-darwin17.7.0
Thread model: posix
InstalledDir: $HOME/emsdk/upstream/bin
shared:INFO: (Emscripten: Running sanity checks)

```

### Start Project 

```shell
$ git clone https://github.com/afuentes/webassembly-quickstart.git
$ cd webassembly-quickstart
$  emcc src/hello_world.c
... 
cache:INFO: generating system library: libc_rt_wasm.a
...
cache:INFO:  - ok
$ ls # validate output file 
LICENSE		README.md	a.out.js	a.out.wasm	src
$ node a.out.js
hello, world!
```
### Page using Wasm Module  


### Reference 

* https://webassembly.org/
* https://emscripten.org/
* https://webassembly.studio/
* https://emscripten.org/docs/getting_started/Tutorial.html
* https://medium.com/@gruizdevilla/webassembly-for-javascripters-6783f6c11ae9
* https://libp2p.io/



