# awesome-computer-science
Collect computer related tutorials,tools and codes!
## Contents

- [Reverse Engine](#Reverse-Engine)
- [Compiler](#Compiler)
- [Decompiler](#Decompiler)
- [Hack Program](#Hack-Program)
- [Windows Kernel](#Windows-Kernel)
- [Operation System](#Operation-system)
- [Emulator](#Emulator)
- [Virtualization](#Virtualization)
- [Game Engine](#Game-Engine)
- [Fuzzing](#Fuzzing)

## Reverse Engine
- Framework
	- [miasm](http://www.miasm.re/blog/)
		- [doc](https://miasmdoc.ajax.re/miasm2/index.html) - miasm2 module API
		- [code](https://github.com/cea-sec/miasm/) - [miasm](https://github.com/cea-sec/miasm/) - Reverse engineering framework in Python.Miasm is a free and open source (GPLv2) reverse engineering framework. Miasm aims to analyze / modify / generate binary programs. 
		
	- [Triton](https://triton.quarkslab.com/)
		- [code](https://github.com/JonathanSalwan/Triton) - [Triton](https://github.com/JonathanSalwan/Triton) - Triton is a Dynamic Binary Analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a Taint Engine, AST representations of the x86 and the x86-64 instructions set semantics, SMT simplification passes, an SMT Solver Interface and, the last but not least, Python bindings.
		- [code](https://github.com/JonathanSalwan/Tigress_protection) - [Tigress_protection](https://github.com/JonathanSalwan/Tigress_protection) - Playing with the Tigress binary protection. Break some of its protections and solve some of its challenges. Automatic deobfuscation using symbolic execution, taint analysis and LLVM.
		- [pdf](https://www.reddit.com/r/ReverseEngineering/comments/8uusze/pdf_symbolic_deobfuscation_from_virtualized_code/e1ialz2/) - Symbolic Deobfuscation: From Virtualized Code Back to the Original
	- [angr](http://angr.io/)
		- [doc](https://docs.angr.io/) - angr Documentation
		- [code](https://github.com/angr/angr) - [angr](https://github.com/angr/angr) - angr is a platform-agnostic binary analysis framework. It is brought to you by the Computer Security Lab at UC Santa Barbara, SEFCOM at Arizona State University, their associated CTF team, Shellphish, the open source community, and @rhelmot.
	- [Manticore](https://github.com/trailofbits/manticore)
		- [code](https://github.com/trailofbits/manticore) - [manticore](https://github.com/trailofbits/manticore) - Manticore is a symbolic execution tool for analysis of binaries and smart contracts.
		- [page](https://blog.trailofbits.com/2017/04/27/manticore-symbolic-execution-for-humans/) - Manticore: Symbolic execution for humans
	- [binwalk]
		- [code](https://github.com/ReFirmLabs/binwalk) - [binwalk](https://github.com/ReFirmLabs/binwalk) - Firmware Analysis Tool.Binwalk is a fast, easy to use tool for analyzing, reverse engineering, and extracting firmware images.
		
	
- Tools
	- [code](https://github.com/binsec/binsec) - [binsec](https://github.com/binsec/binsec) - BINSEC binary-level open-source platform
	
- Tutorial
	- [Book](https://github.com/DennisYurichev/RE-for-beginners#readme) - "Reverse Engineering for Beginners" free book http://beginners.re
	- [List](https://github.com/wtsxDev/reverse-engineering) - List of awesome reverse engineering resources
	- [Doc](https://www.hex-rays.com/products/ida/support/idapython_docs/) - [IDAPython](https://www.hex-rays.com/products/ida/support/idapython_docs/) - This document contains the API (Application Programming Interface) documentation for IDAPython. Documentation for the Python objects defined by the project is divided into separate pages for each package, module, and class. The API documentation also includes two pages containing information about the project as a whole: a trees page, and an index page.
	
- File Format
	- [code](https://github.com/corkami/pocs) - [pocs](https://github.com/corkami/pocs) - Proof of Concepts (PE, PDF...)
	
	- [PE]
		- [code](https://github.com/hasherezade/pe-sieve) - [PE-sieve](https://github.com/hasherezade/pe-sieve) - PE-sieve is a light-weight tool that helps to detect malware running on the system, as well as to collect the potentially malicious material for further analysis. Recognizes and dumps variety of implants within the scanned process: replaced/injected PEs, shellcodes, hooks, and other in-memory patches.
	Detects inline hooks, Process Hollowing, Process Doppelgänging, Reflective DLL Injection, etc.
		- [code](https://github.com/zodiacon/PEExplorer) - [PEExplorer](https://github.com/zodiacon/PEExplorer) - Portable Executable Explorer
	
- AntiDebug
	- [code](https://github.com/CoderAldrich/AntiDebug) - [AntiDebug](https://github.com/CoderAldrich/AntiDebug) - 此目录收集整理反调试方法
	- [code](https://github.com/alphaSeclab/anti-debug) - [anti-debug](https://github.com/alphaSeclab/anti-debug) - 
	- [code]() - []() - 
- Debug
	- [code](https://github.com/bootleg/ret-sync) - [ret-sync](https://github.com/bootleg/ret-sync) - ret-sync stands for Reverse-Engineering Tools synchronization. It's a set of plugins that help to synchronize a debugging session (WinDbg/GDB/LLDB/OllyDbg/OllyDbg2/x64dbg) with IDA disassembler. The underlying idea is simple: take the best from both worlds (static and dynamic analysis).
- IDA
	
	- [code](https://github.com/wanttobeno/IDAStealth-v1.3.3) - [IDAStealth-v1.3.3](https://github.com/wanttobeno/IDAStealth-v1.3.3) - IDA反-反调试插件 IDAStealth v1.3.3, created 06/28/2011, Jan Newger
	- [code](https://github.com/illera88/Ponce) - [Ponce](https://github.com/illera88/Ponce) - IDA 2016 plugin contest winner! Symbolic Execution just one-click away!Ponce (pronounced [ 'poN θe ] pon-they ) is an IDA Pro plugin that provides users the ability to perform taint analysis and symbolic execution over binaries in an easy and intuitive fashion. With Ponce you are one click away from getting all the power from cutting edge symbolic execution. Entirely written in C/C++.
	- [code](https://github.com/alexhude/uEmu) - [uEmu](https://github.com/alexhude/uEmu) - Tiny cute emulator plugin for IDA based on unicorn.
	- [code](https://github.com/snare/ida-efiutils) - [ida-efiutils](https://github.com/snare/ida-efiutils) - Some scripts for IDA Pro to assist with reverse engineering EFI binaries
	- [code](https://github.com/DGA-MI-SSI/YaCo) - [YaCo](https://github.com/DGA-MI-SSI/YaCo) - YaCo is an Hex-Rays IDA plugin. When enabled, multiple users can work simultaneously on the same binary. Any modification done by any user is synchronized through git version control.
	- [code](https://github.com/IDArlingTeam/IDArling) - [IDArling](https://github.com/IDArlingTeam/IDArling) - Collaborative Reverse Engineering plugin for IDA Pro & Hex-Rays https://idarling.re
	- [code](https://github.com/keystone-engine/keypatch) - [keypatch](https://github.com/keystone-engine/keypatch) - Multi-architecture assembler for IDA Pro. Powered by Keystone Engine. http://www.keystone-engine.org/keypatch
	- [code](https://github.com/RobinDavid/idasec) - [idasec](https://github.com/RobinDavid/idasec) - IDA plugin for reverse-engineering and dynamic interactions with the Binsec platform
	- [code](https://github.com/techbliss/Python_editor) - [Python_editor](https://github.com/techbliss/Python_editor) - Better CodeEditor for Ida Pro.
	- [code](https://github.com/idapython/src) - [IDAPython](https://github.com/idapython/src) - IDAPython project for Hex-Ray's IDA Pro http://www.hex-rays.com/
	- [code](https://github.com/tmr232/Sark) - [Sark](https://github.com/tmr232/Sark) - IDAPython Made Easy http://sark.readthedocs.io
	

- x64Dbg
	- [code](https://github.com/0ffffffffh/Api-Break-for-x64dbg) - [Api-Break-for-x64dbg](https://github.com/0ffffffffh/Api-Break-for-x64dbg) - x64dbg plugin to set breakpoints automatically to Win32/64 APIs
	- [code](https://github.com/atom0s/CeAutoAsm-x64dbg) - [CeAutoAsm-x64dbg](https://github.com/atom0s/CeAutoAsm-x64dbg) - An x64dbg plugin that allows users to execute Cheat Engine auto assembler scripts within x64dbg.
	- [code](https://github.com/ThunderCls/xAnalyzer) - [xAnalyzer](https://github.com/ThunderCls/xAnalyzer) - xAnalyzer plugin for x64dbg
	
- [OD]





		
- VMProtect
	- Tutorial
		- [Tickling VMProtect with LLVM: Part 1](https://secret.club/2021/09/08/vmprotect-llvm-lifting-1.html)
		- [Tickling VMProtect with LLVM: Part 2](https://secret.club/2021/09/08/vmprotect-llvm-lifting-2.html)
		- [Tickling VMProtect with LLVM: Part 3](https://secret.club/2021/09/08/vmprotect-llvm-lifting-3.html)
	- Tools
 		- [code](https://github.com/can1357/NoVmp) - [NoVmp](https://github.com/can1357/NoVmp) - [Writing An Optimizing IL Compiler, For Dummies, By A Dummy: 0x1 Symbolic Expressions](https://blog.can.ac/2020/04/11/writing-an-optimizing-il-compiler-for-dummies-by-a-dummy/)
		- [code](https://github.com/wanttobeno/vmp3.2crack) - [vmp3.2crack](https://github.com/wanttobeno/vmp3.2crack) - [[调试逆向] [虚拟机保护] [原创]VMP3.2授权分析](https://bbs.pediy.com/thread-247442.htm)
		 - ~~[code](https://github.com/wanttobeno/VmpHandle)~~ - ~~[VmpHandle](https://github.com/wanttobeno/VmpHandle)~~
		- ~~[code](https://github.com/0xbadc0de1/VmP_DBG)~~ - ~~[VmP_DBG](https://github.com/0xbadc0de1/VmP_DBG)~~ - ~~This is a VmProtect integrated debugger, that will essentially allow you to disasm and debug vmp partially virtualized functions at the vmp bytecode level. It was made using TitanEngine for the debug engine and Qt for the gui. Do not expect much of it and feel free to report any bugs.~~
		- ~~[code](https://github.com/uvbs/VMPDBG2)~~ - ~~[VMPDBG2](https://github.com/uvbs/VMPDBG2)~~ - ~~VMPDBG is a (GUI included) debugger and devirtualizer for x86 obfuscted code that was obfuscated by VMProtect. This project was designed only for scientific purposes and / or malware analysis.~~
		- [code](https://github.com/s3team/VMHunt) - [VMHunt](https://github.com/s3team/VMHunt) - VMHunt: Extraction and Simplification of Virtualized Binary Code.
		- [code](https://github.com/lmy375/pinvmp) - [pinvmp](https://github.com/lmy375/pinvmp) - PinVMP：虚拟化代码辅助分析工具
		- [code](https://github.com/anatolikalysch/VMAttack) - [VMAttack](https://github.com/anatolikalysch/VMAttack) - VMAttack PlugIn for IDA Pro.IDA Pro Plugin for static and dynamic virtualization-based packed analysis and deobfuscation.VMAttack was awarded the second place at the annual IDA Pro Plug-in Contest in 2016!
		- [code](https://github.com/OoWoodOne/VMP_ODPlugin) - [VMP_ODPlugin](https://github.com/OoWoodOne/VMP_ODPlugin) - [[原创]VMP分析handler与脱壳插件&源码](https://bbs.pediy.com/thread-203683.htm)
		
	- Implement
		- [code](https://github.com/TinyNiko/VMProtect) - [VMProtect](https://github.com/TinyNiko/VMProtect) - I know this project is impossible ,but i;m possible
		- [code](https://github.com/GkvJwa/vmp) - [vmp demo](https://github.com/GkvJwa/vmp)
		
- Android
	- Tools
		-[book](https://github.com/nowsecure/r2frida-book) - [r2frida-book](https://github.com/nowsecure/r2frida-book) - The radare2 + frida book for Mobile Application assessment https://www.nowsecure.com
	

- IOS

- UnPack
	- [code](https://github.com/cawk/ConfuserEx-Unpacker) - [ConfuserEx-Unpacker](https://github.com/cawk/ConfuserEx-Unpacker) - A dynamic confuserex unpacker that relies on invoke for most things
	
- Pack/Protect
	
## Compiler
- LLVM
	- Tutorial

	- Tools
	
- Book
	- [code](https://github.com/fool2fish/dragon-book-exercise-answers) - [dragon-book-exercise-answers](https://github.com/fool2fish/dragon-book-exercise-answers) - Compilers Principles, Techniques, & Tools (purple dragon book) second edition exercise answers
- code
	- [ShivyC](https://github.com/ShivamSarodia/ShivyC) - A hobby C compiler created in Python.

## Decompiler
- LuaJIT(http://luajit.org/)
	- [code](https://github.com/perfectplug/ljd) - [ljd](https://github.com/perfectplug/ljd) - The original name was ljwthgnd as in LuaJIT 'What The Hell is Going On' Decompiler named under the LuaJIT C sources variable naming convention.
	- [code](https://github.com/EiNSTeiN-/decompiler) - [decompiler](https://github.com/EiNSTeiN-/decompiler) - A decompiler with multiple backend support, written in Python. Works with IDA and Capstone.
	- [code](https://github.com/rexdex/recompiler) - [recompiler](https://github.com/rexdex/recompiler) - Xbox360 -> Windows executable converter
	

## Hack Program
- DDOS
	- [material](https://www.ecrimelabs.com/blog/2018/11/25/ddos-research-data-made-public) - DDOS RESEARCH DATA OPEN-SOURCED ON SCANS.IO
	- [code](https://github.com/maestron/botnets) - [botnets](https://github.com/maestron/botnets) - This is a collection of #botnet source codes, unorganized. For EDUCATIONAL PURPOSES ONLY
- Exploit
	- [code](https://github.com/niklasb/sploits) - [sploits](https://github.com/niklasb/sploits)
	- [code](https://github.com/enddo/awesome-windows-exploitation) - [awesome-windows-exploitation](https://github.com/enddo/awesome-windows-exploitation) - A curated list of awesome Windows Exploitation resources, and shiny things. Inspired by awesom
- Inject
	- [code](https://github.com/rootm0s/Injectors) - [Injectors](https://github.com/rootm0s/Injectors) - DLL/Shellcode injection techniques
	- [code](https://github.com/strivexjun/DriverInjectDll) - [DriverInjectDll](https://github.com/strivexjun/DriverInjectDll) - Use Driver Global Memory Load DLL
	- [code](https://github.com/fdiskyou/injectAllTheThings) - [injectAllTheThings](https://github.com/fdiskyou/injectAllTheThings) - Seven different DLL injection techniques in one single project.
	- [code](https://github.com/dwendt/UniversalInject) - [UniversalInject](https://github.com/dwendt/UniversalInject) - Windows IME-based DLL injection. Able to inject a DLL without OpenProcess or a process handle being necessary..

- PS
	- [code](https://github.com/TheOfficialFloW/h-encore) - [h-encore](https://github.com/TheOfficialFloW/h-encore) - Fully chained kernel exploit for the PS Vita
	
- Sandbox
	- [code](https://github.com/cuckoosandbox/cuckoo) - [cuckoo](https://github.com/cuckoosandbox/cuckoo) - Cuckoo Sandbox is an automated dynamic malware analysis system http://www.cuckoosandbox.org
	- [code](https://github.com/spender-sandbox/cuckoo-modified) - [cuckoo-modified](https://github.com/spender-sandbox/cuckoo-modified) - Modified edition of cuckoo.
	- [code](https://github.com/ctxis/CAPE) - [CAPE](https://github.com/ctxis/CAPE) - Malware Configuration And Payload Extraction https://cape.contextis.com/analysis.CAPE is a malware sandbox. It is derived from Cuckoo and is designed to automate the process of malware analysis with the goal of extracting payloads and configuration from malware. This allows CAPE to detect malware based on payload signatures, as well as automating many of the goals of malware reverse engineering and threat intelligence.
	
- DB
	- [code](https://github.com/woj-ciech/LeakLooker) - [LeakLooker](https://github.com/woj-ciech/LeakLooker) - Find open databases with Shodan
	
## Windows Kernel
- Tools
	- [code](https://github.com/zodiacon/KernelExplorer) - [KernelExplorer](https://github.com/zodiacon/KernelExplorer)
	- [code](https://github.com/zodiacon/DriverMon) - [DriverMon](https://github.com/zodiacon/DriverMon)
- Bootkit

- Rootkit

## Operation System
- File System
	- [code](https://github.com/ufrisk/MemProcFS) - [MemProcFS](https://github.com/ufrisk/MemProcFS) - The Memory Process File System:
	
- Tutorial
	- [os_course_info](https://github.com/chyyuu/os_course_info) - 清华大学操作系统课程(2018)
	- [code](https://github.com/chyyuu/ucore_os_lab) - [ucore_os_lab](https://github.com/chyyuu/ucore_os_lab) - os kernel labs for operating systems course in Tsinghua University.


	
## Emulator
- Cmulator - [code](https://github.com/Coldzer0/Cmulator) - Cmulator is ( x86 - x64 ) Scriptable Reverse Engineering Sandbox Emulator for shellcode and PE binaries . Based on Unicorn & Capstone Engine & javascript


## Virtualization
- Intel
	- [code](https://github.com/tandasat/GuardMon) - [GuardMon](https://github.com/tandasat/GuardMon) - Hypervisor based tool for monitoring system register accesses.
- AMD

## Game Engine
- Client
	- cocos2d
		- [code](https://github.com/cocos2d/cocos2d-x) - [cocos2d-x](https://github.com/cocos2d/cocos2d-x) - Cocos2d-x is a suite of open-source, cross-platform, game-development tools used by millions of developers all over the world.
		- [code](https://github.com/u0u0/Quick-Cocos2dx-Community) - [Quick-Cocos2dx-Community](https://github.com/u0u0/Quick-Cocos2dx-Community) - Cocos2d-Lua 社区版 http://www.cocos2d-lua.org
	- [bs::framework](https://www.bsframework.io/)
		- [code](https://github.com/gamefoundry/bsf) - [bsf](https://github.com/gamefoundry/bsf) - bs::framework is a C++ library that aims to provide a unified foundation for the development of real-time graphical applications, whether games, engines or tools.
- Server
	- [SuperSocket](http://www.supersocket.net/)
		- [code](https://github.com/kerryjiang/SuperSocket) - [SuperSocket](https://github.com/kerryjiang/SuperSocket) - SuperSocket is a light weight, cross platform and extensible socket server application framework.
		- [code](https://github.com/kerryjiang/SuperSocket.ClientEngine) - [SuperSocket.ClientEngine](https://github.com/kerryjiang/SuperSocket.ClientEngine) - A .NET library which can make your socket client development easier

	- forgottenserver
		- [code](https://github.com/otland/forgottenserver) - [forgottenserver](https://github.com/otland/forgottenserver) - A free and open-source MMORPG server emulator written in C++ https://otland.net/
	- Simple-Web-Server
		- [code](https://gitlab.com/eidheim/Simple-Web-Server) - [Simple-Web-Server](https://gitlab.com/eidheim/Simple-Web-Server) - A very simple, fast, multithreaded, platform independent HTTP and HTTPS server and client library implemented using C++11 and Boost.Asio. Created to be an easy way to make REST resources available from C++ applications.
- Game
	- [freeablo](https://freeablo.org/)
		- [code](https://github.com/wheybags/freeablo) - [freeablo](https://github.com/wheybags/freeablo) - Modern reimplementation of the Diablo 1 game engine

## Fuzzing
- applepie
	- [code](https://github.com/gamozolabs/applepie) - A hypervisor for fuzzing built with WHVP and Bochs
