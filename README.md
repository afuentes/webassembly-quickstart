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
$ emcc src/hello_world.c -o out/hello.html
$ ls out/
hello.html	hello.js	hello.wasm
$ cd out 
$ python -m SimpleHTTPServer 8080
Serving HTTP on 0.0.0.0 port 8080 ...
```
Note : Open browser in http://localhost:8080/hello.html 

### Page using Wasm Module  


### Reference 

* https://webassembly.org/
* https://emscripten.org/
* https://webassembly.studio/
* https://wasdk.github.io/WasmFiddle/
* https://emscripten.org/docs/getting_started/Tutorial.html
* https://medium.com/@gruizdevilla/webassembly-for-javascripters-6783f6c11ae9
* https://libp2p.io/



