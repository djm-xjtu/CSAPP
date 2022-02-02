# attacklab

- Use this command to test your answer and the n is the number of the level.
> level 1~3
~~~
./hex2raw < phase_n.txt | ./ctarget -q
~~~
> level 4~5
~~~
./hex2raw < phase_n.txt | ./rtarget -q
~~~
- A great tool

> ROPgadget Tool

> This tool lets you search your gadgets on your binaries to facilitate your ROP exploitation. ROPgadget supports ELF/PE/Mach-O format on x86, x64, ARM, ARM64, PowerPC, SPARC and MIPS architectures. Since the version 5, ROPgadget has a new core which is written in Python using Capstone disassembly framework for the gadgets search engine - The older version can be found in the Archives directory but it will not be maintained.

> The easiest way to install the tool
~~~
$ sudo apt install python3-pip
$ sudo -H python3 -m pip install ROPgadget
$ ROPgadget --help
~~~
>
- [Reading materials](https://zhuanlan.zhihu.com/p/28476993)
