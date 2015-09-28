# flth
LLVM ANS Forth

flth is an implementation of ANS forth. It strives to be compatible with gforth so that it can be bootstrapped with either gforth or flth.

It should also hopefully be able to somehow offer a way to compile code into native binaries and static and shared libraries that
can be statically linked with C (by compiling to llvm ir). This should enable you to use forth along with other languages and to make applications for more platforms (android ios etc)
