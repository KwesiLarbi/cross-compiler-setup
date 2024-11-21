# GCC Custom Cross Compiler

This tutorial focuses on creating a GCC cross-compiler for your own operating system. This compiler that we build here will have a generic target (i686-elf) that allows you to leave the current operating system behind, meaning that no headers or libraries of the host operating system will be used. Without using a cross-compiler for operating system development, a lot of unexpected things can happen because the compiler assumes that the code is running on the host operating system.
