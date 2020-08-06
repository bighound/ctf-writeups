# Statics and Dynamics

It is a Pwn challenge where the binary is not linked to any external library, that's why everything needed is inside the binary.

In order to exploit this, the ret2syscall technique is used, allowing through ROP (Return-oriented-Programming) to make a call to the system with the available instruction 'syscall' to make a call to execve and be able to obtain a shell
