# WebAssembly QuickStart 
WebAssembly QuickStart Project 

## Enviroment MacOs 

```shell
$ brew update
$ brew install  llvm # validate 
$ brew install emscripten
$ emcc -v
==============================================================================
Welcome to Emscripten!

This is the first time any of the Emscripten tools has been run.

A settings file has been copied to ~/.emscripten, at absolute path: $HOME/.emscripten

It contains our best guesses for the important paths, which are:

  LLVM_ROOT       = /usr/bin
  NODE_JS         = /usr/local/bin/node
  EMSCRIPTEN_ROOT = /usr/local/Cellar/emscripten/1.38.44/libexec

Please edit the file if any of those are incorrect.

This command will now exit. When you are done editing those paths, re-run it.
==============================================================================
$ vi $HOME/.emscripten # updated LLVM_ROOT PATH 
$ emcc -v
emcc (Emscripten gcc/clang-like replacement + linker emulating GNU ld) 1.38.44
clang version 9.0.0 (tags/RELEASE_900/final)
Target: x86_64-apple-darwin17.7.0
Thread model: posix
InstalledDir: /usr/local/opt/llvm/bin
shared:WARNING: LLVM version appears incorrect (seeing "9.0", expected "10.0")
shared:INFO: (Emscripten: Running sanity checks)

```

Note : brew package install llvm stable 9 https://formulae.brew.sh/formula/llvm 
 

## Reference 

* https://webassembly.org/
* https://emscripten.org/
* https://webassembly.studio/
* https://emscripten.org/docs/getting_started/Tutorial.html
* https://medium.com/@gruizdevilla/webassembly-for-javascripters-6783f6c11ae9


