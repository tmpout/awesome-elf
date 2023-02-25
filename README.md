# Awesome ELF Resources

                           ┌───────────────────────┐                            
                           ▄▄▄▄▄ ▄▄▄▄▄ ▄▄▄▄▄       │                            
                           │ █   █ █ █ █   █       │                            
                           │ █   █ █ █ █▀▀▀▀       │                            
                           │ █   █   █ █     ▄     │                            
                           │                 ▄▄▄▄▄ │                            
                           │                 █   █ │                            
                           │                 █   █ │                            
                           │                 █▄▄▄█ │                            
                           │                 ▄   ▄ │                            
                           │                 █   █ │                            
                           │                 █   █ │                            
                           │                 █▄▄▄█ │                            
                           │                 ▄▄▄▄▄ │                            
                           │                   █   │                            
                           │                   █   │                            
                           └───────────────────█ ──┘ 

TMP.0UT stands on the shoulders of giants, and we lend a hand for the next generation of giants to stand on ours.

This repo contains an appendix of resources and links to our own work and the work of others.

If you see your work cited here and would like us to credit in a more specific way, please let us know!

**A collection of awesome ELF resources**

Your [contributions](contributing.md) are always welcome !

## Awesome Repositories

### ELF binary format

- Amos on ELF packers
  - [Making your own executable packer - 18 part series](https://fasterthanli.me/series/making-our-own-executable-packer)

- Aprodu Andrei Ciprian and ELF linking process
  - [Interactive Exploration of the Process of Linking Executables](https://github.com/Eteru/Elf-Detective---Bachelor-Paper/blob/master/thesis.pdf)
  - [ELF_Detective](https://github.com/Eteru/ELF-Detective)

- Brian Raiter's essays on tiny ELF (1999)
  - [Guide about creating tiny ELF](https://www.muppetlabs.com/~breadbox/software/tiny/)
  - [Return 42 collection](https://www.muppetlabs.com/~breadbox/software/tiny/return42.html)
  - [Usefull tiny programs](https://www.muppetlabs.com/~breadbox/software/tiny/useful.html)

- Bx and the ELF metadata
  - [Returning from ELF to Libc by Bx](https://archive.org/details/Pocorgtfo00/page/n9/mode/1up?view=theater)
  - [“Weird Machines” in ELF by Bx](https://www.usenix.org/system/files/conference/woot13/woot13-shapiro.pdf)

- David Smith and Handmade ELFs
  - [Handmade Linux x86 executables](https://youtube.com/playlist?list=PLZCIHSjpQ12woLj0sjsnqDH8yVuXwTy3p)

- Robin Hoksbergen and Manually Creating An ELF
  - [Manually Creating An ELF Executable](https://web.archive.org/web/20140130143820/http://www.robinhoksbergen.com/papers/howto_elf.html)

- elfmaster and everything about ELF
  - [ELF shared library injection forensics](https://engineering.backtrace.io/2016-04-14-elf-shared-library-injection-forensics/)
  - [Secure ELF parsing/loading library](https://github.com/elfmaster/libelfmaster)
  - [... and examples](https://github.com/elfmaster/libelfmaster_examples)
  - [Transform vmlinuz into a fully debuggable vmlinux that can be used with /proc/kcore](https://github.com/elfmaster/kdress)
  - [fork-trace](https://github.com/elfmaster/fork_trace)
  - [extended core file snapshot format](https://github.com/elfmaster/ecfs) and [exec](https://github.com/elfmaster/ecfs_exec)
  - [Obfuscates dynamic symbol table](https://github.com/elfmaster/dsym_obfuscate)
  - [ftrace](https://github.com/elfmaster/ftrace) and [new ftrace](https://github.com/elfmaster/binflow)
  - [hidden process /bin/ps](https://github.com/elfmaster/taskverse)
  - [davinci](https://github.com/elfmaster/davinci)
  - [sherlocked](https://github.com/elfmaster/sherlocked)

- Ignacio Sanmillan / Paul Litvak and ELF 101
  - [Executable and Linkable Format 101 - Part 1 Sections and Segments](https://www.intezer.com/blog/research/executable-linkable-format-101-part1-sections-segments/)
  - [Executable and Linkable Format 101. Part 2: Symbols](https://www.intezer.com/blog/malware-analysis/executable-linkable-format-101-part-2-symbols/)
  - [Executable and Linkable Format 101 Part 3: Relocations](https://www.intezer.com/blog/malware-analysis/executable-and-linkable-format-101-part-3-relocations/)
  - [Executable and Linkable Format 101 Part 4: Dynamic Linking](https://www.intezer.com/blog/malware-analysis/executable-linkable-format-101-part-4-dynamic-linking/)

- Ignat Korchagin and object files
  - [How to execute an object file: Part 1](https://blog.cloudflare.com/how-to-execute-an-object-file-part-1/)
  - [How to execute an object file: Part 2](https://blog.cloudflare.com/how-to-execute-an-object-file-part-2/)
  - [How to execute an object file: Part 3](https://blog.cloudflare.com/how-to-execute-an-object-file-part-3/)

- Manu Garg and ELF Auxiliary Vectors
  - [About ELF Auxiliary Vectors](https://articles.manugarg.com/aboutelfauxiliaryvectors.html)

- MaskRay and ELF interposition
  - [ELF interposition and -Bsymbolic](https://maskray.me/blog/2021-05-16-elf-interposition-and-bsymbolic)

- netspooky and ELF Binary Mangling
  - [ELF Binary Mangling Part 1: Concepts](https://n0.lol/ebm/1.html)
  - [Elf Binary Mangling Pt. 2: Golfin'](https://n0.lol/ebm/2.html)
  - [Elf Binary Mangling Pt. 3: Weaponization](https://n0.lol/ebm/3.html)
  - [Elf Binary Mangling Pt. 4: Limit Break](https://n0.lol/ebm/4.html)

- Orlando Padilla and binary parsers
  - [Analyzing Common Binary Parser Mistakes](http://www.uninformed.org/?v=all&a=12&t=txt)

- Patrick Horgan and main()
  - [How the heck do we get to main()?](http://dbp-consulting.com/tutorials/debugging/linuxProgramStartup.html)

- Samuel A. Falvo II and ELF
  - [On ELF, Part 1](https://kestrelcomputer.github.io/kestrel/2018/01/29/on-elf)
  - [On ELF, Part 2](https://kestrelcomputer.github.io/kestrel/2018/02/01/on-elf-2)

- Tools
  - [BioDiff - hex diff viewer](https://github.com/8051Enthusiast/biodiff)
  - [clodl: self-contained dynamic libraries](https://github.com/tweag/clodl)
  - [d0zer - ELF infector written in Go](https://github.com/sad0p/d0zer)
  - [elfcat - ELF visualizer](https://github.com/ruslashev/elfcat)
  - [Embuche - Anti reverse compiling tool](https://github.com/magnussen7/Embuche)
  - [Hellf - ELF patching lib in Python](https://github.com/0xswitch/Hellf)
  - [Hexyl - hexdumper with colors](https://github.com/sharkdp/hexyl)
  - [lief](https://github.com/lief-project/LIEF)
  - [Macaw - binary analysis framework(ELF/DWARF/more)](https://github.com/GaloisInc/macaw)
  - [PatchELF - a simple utility for modifying existing ELF executables and libraries](https://github.com/NixOS/patchelf)
  - [PLTHook - utility library to hook library function calls](https://github.com/kubo/plthook)
  - [StaticX ](https://github.com/JonathonReinhart/staticx)
  - [The Backdoor Factory](https://github.com/Binject/backdoorfactory)
  - [xELFViewer - ELF file viewer](https://github.com/horsicq/XELFViewer)

### ELF VX technology

- TMZ
  - [Linux.Midrashim: Assembly x64 ELF virus](https://www.guitmz.com/linux-midrashim-elf-virus/)
  - [Linux.Nasty: Assembly x64 ELF virus](https://www.guitmz.com/linux-nasty-elf-virus/)
  - [Ezuri: Linux ELF Runtime Crypter](https://www.guitmz.com/linux-elf-runtime-crypter/)
  - [Running ELF executables from memory](https://www.guitmz.com/running-elf-from-memory/)
  - [Linux.Fe2O3: a Rust virus](https://www.guitmz.com/linux-fe2o3-rust-virus/)
  - [Linux.Cephei: a Nim virus](https://www.guitmz.com/linux-cephei-a-nim-virus/)
  - [Linux.Liora: a Go virus](https://www.guitmz.com/linux-liora/)
  - [Linux.Zariche: a Vala virus](https://www.guitmz.com/vala-virus/)

- elfmaster and ELF vx
  - [Devestating and awesome Linux X86_64 ELF Virus](https://github.com/elfmaster/skeksi_virus)
  - [ELF Shared library injector using DT_NEEDED precedence infection](https://github.com/elfmaster/dt_infect)
  - [SCOP ELF vx](https://github.com/elfmaster/scop_virus_paper)
  - [Saruman - ELF anti-forensics exec](https://github.com/elfmaster/saruman)
  - [AV prototype - 32bit](https://github.com/elfmaster/avu32)
  - [LK rootkit](https://github.com/elfmaster/kprobe_rootkit)

- Intezer Labs and malware analysis
  - [ELF Malware Analysis 101: Linux Threats No Longer an Afterthought](https://www.intezer.com/blog/malware-analysis/elf-malware-analysis-101-linux-threats-no-longer-an-afterthought/)
  - [ELF Malware Analysis 101 Part 2: Initial Analysis](https://www.intezer.com/blog/malware-analysis/elf-malware-analysis-101-initial-analysis/)
  - [ELF Malware Analysis 101: Part 3 - Advanced Analysis](https://www.intezer.com/blog/malware-analysis/elf-malware-analysis-101-part-3-advanced-analysis/)

- Lucas Galante + Marcus Botacin and (malware/goodware) binary classification
  - [Forseti](https://github.com/marcusbotacin/ELF.Classifier)
  - [Machine Learning for Malware Detection](https://github.com/marcusbotacin/ELF.Classifier/blob/master/paper/classifier.pdf)

- Peter Ferrie and Flibi
  - [FLIBI: EVOLUTION](http://pferrie.epizy.com/papers/flibi2.pdf?i=1)
  - [FLIBI: RELOADED](http://pferrie.epizy.com/papers/flibi3.pdf)

- Shane tully on ELF vx
  - [Writing a Self-Mutating x86_64 C Program](https://shanetully.com/2013/12/writing-a-self-mutating-x86_64-c-program/) 

- Shreyansh Singh and ELF-Miner
  - [Paper: ELF-Miner: using structural knowledge and data mining methods to detect new (Linux) malicious executables](https://link.springer.com/article/10.1007/s10115-011-0393-5)
  - [Code](https://github.com/shreyansh26/ELF-Miner)

- TheXcellerator and Linux Rootkits
  - [Linux Rootkits Part 1: Introduction and Workflow](https://xcellerator.github.io/posts/linux_rootkits_01/)
  - [Linux Rootkits Part 2: Ftrace and Function Hooking](https://xcellerator.github.io/posts/linux_rootkits_02/)
  - [Linux Rootkits Part 3: A Backdoor to Root](https://xcellerator.github.io/posts/linux_rootkits_03/)
  - [Linux Rootkits Part 4: Backdooring PRNGs by Interfering with Char Devices](https://xcellerator.github.io/posts/linux_rootkits_04/)
  - [Linux Rootkits Part 5: Hiding Kernel Modules from Userspace](https://xcellerator.github.io/posts/linux_rootkits_05/)
  - [Linux Rootkits Part 6: Hiding Directories](https://xcellerator.github.io/posts/linux_rootkits_06/)
  - [Linux Rootkits Part 7: Hiding Processes](https://xcellerator.github.io/posts/linux_rootkits_07/)
  - [Linux Rootkits Part 8: Hiding Open Ports](https://xcellerator.github.io/posts/linux_rootkits_08/)
  - [Linux Rootkits Part 9: Hiding Logged In Users (Modifying File Contents Without Touching Disk)](https://xcellerator.github.io/posts/linux_rootkits_09/)
  - [Fancy Bear’s a Lumberjack and It’s Okay - A Dive into the Kernel Component of Drovorub](https://xcellerator.github.io/posts/linux_rootkits_10/)
  - [Linux Rootkits: New Methods for Kernel 5.7+](https://xcellerator.github.io/posts/linux_rootkits_11/)

- [Becoming a rat in your system](https://devilinside.me/blogs/becoming-rat-your-system)
- [Kernel mode hooking [EN]](https://is.muni.cz/el/fi/jaro2011/PV204/um/LinuxRootkits/sys_call_table_complete.htm)
- [Last Digital Common Ancestor (LDCA)](https://github.com/mertyildiran/ldca/blob/master/linux_x86/dev.asm)
- [(nearly) Complete Linux Loadable Kernel Modules](http://www.ouah.org/LKM_HACKING.html)
- [Reflections on Trusting Trust](https://www.cs.cmu.edu/~rdriley/487/papers/Thompson_1984_ReflectionsonTrustingTrust.pdf)
- [Static linked ELF infecting](https://packetstormsecurity.com/files/34013/0x4553-Static_Infecting.html.html)

### ELF header hacks

### DWARF stuff

### PROGRAMMING

- [The Art of Assembly Programming Language](https://www.phatcode.net/res/223/files/html/toc.html)
- [Bit twiddling hacks](https://graphics.stanford.edu/~seander/bithacks.html)
- [Intel® 64 and IA-32 Instruction Set Reference](https://namazso.github.io/x86/)
- [System call reference tables for x86, x64, arm and arm64](https://syscall.sh)
- [API for system call references for x86, x64, arm and arm64](https://api.syscall.sh/swagger/index.html)
 
### MISC

- [vxer.io (vxheaven successor)](https://vxer.io/)
- [ANSIWAVE BBS](https://ansiwave.net/)
- [PageBuster](https://rev.ng/blog/pagebuster/post.html)
- [vx-underground heaven](https://www.vx-underground.org/archive/VxHeaven/lib/vsp44.html)
- [WIZARD BIBLE (in Japanese)](https://wizardbible.github.io/)

### Polyglots

- [αcτµαlly pδrταblε εxεcµταblε](https://justine.lol/ape.html)
- [Architecture Spanning Shellcode](http://phrack.org/issues/57/14.html#article)
- [Doublethink – 8-Architecture Assembly Polyglot](https://www.robertxiao.ca/hacking/defcon2018-assembly-polyglot/)
- [tweetable-polyglot-png](https://github.com/DavidBuchanan314/tweetable-polyglot-png)

### Linker Script Tutorials

- [Everything You Never Wanted To Know About Linker Script](https://mcyoung.xyz/2021/06/01/linker-script/)
- [Linker Script Guide](https://www.phaedsys.com/principals/emprog/emprogdata/thunderbench-Linker-Script-guide.pdf)
- [Most Commented Linker Script in the World](https://blog.thea.codes/the-most-thoroughly-commented-linker-script/)
