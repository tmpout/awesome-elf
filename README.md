# Awesome _X Resources

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

- Bx and the ELF metadata
  - [Returning from ELF to Libc by Bx](https://archive.org/details/Pocorgtfo00/page/n9/mode/1up?view=theater)
  - [“Weird Machines” in ELF by Bx](https://www.usenix.org/system/files/conference/woot13/woot13-shapiro.pdf)

- Orlando Padilla and binary parsers
  - [Analyzing Common Binary Parser Mistakes](http://www.uninformed.org/?v=all&a=12&t=txt)

- David Smith and Handmade ELFs
  - [Handmade Linux x86 executables](https://youtube.com/playlist?list=PLZCIHSjpQ12woLj0sjsnqDH8yVuXwTy3p)

- Ignacio Sanmillan and ELF 101
  - [Executable and Linkable Format 101 - Part 1 Sections and Segments](https://www.intezer.com/blog/research/executable-linkable-format-101-part1-sections-segments/)
  - [Executable and Linkable Format 101. Part 2: Symbols](https://www.intezer.com/blog/malware-analysis/executable-linkable-format-101-part-2-symbols/)
  - [Executable and Linkable Format 101 Part 3: Relocations](https://www.intezer.com/blog/malware-analysis/executable-and-linkable-format-101-part-3-relocations/)
  - [Executable and Linkable Format 101 Part 4: Dynamic Linking](https://www.intezer.com/blog/malware-analysis/executable-linkable-format-101-part-4-dynamic-linking/)

- netspooky and ELF Binary Mangling
  - [ELF Binary Mangling Part 1: Concepts](https://n0.lol/ebm/1.html)
  - [Elf Binary Mangling Pt. 2: Golfin'](https://n0.lol/ebm/2.html)
  - [Elf Binary Mangling Pt. 3: Weaponization](https://n0.lol/ebm/3.html)
  - [Elf Binary Mangling Pt. 4: Limit Break](https://n0.lol/ebm/4.html)

- Ignat Korchagin and object files
  - [How to execute an object file: Part 1](https://blog.cloudflare.com/how-to-execute-an-object-file-part-1/)
  - [How to execute an object file: Part 2](https://blog.cloudflare.com/how-to-execute-an-object-file-part-2/)
  - [How to execute an object file: Part 3](https://blog.cloudflare.com/how-to-execute-an-object-file-part-3/)

- Tools
  - [clodl: self-contained dynamic libraries](https://github.com/tweag/clodl)
  - [StaticX ](https://github.com/JonathonReinhart/staticx)
  - [PatchELF - a simple utility for modifying existing ELF executables and libraries](https://github.com/NixOS/patchelf)
  - [Macaw - binary analysis framework(ELF/DWARF/more)](https://github.com/GaloisInc/macaw)
  - [The Backdoor Factory](https://github.com/Binject/backdoorfactory)
  - [elfcat - ELF visualizer](https://github.com/ruslashev/elfcat)
  - [xELFViewer - ELF file viewer](https://github.com/horsicq/XELFViewer)


### ELF VX technology

- Peter Ferrie and Flibi
  - [FLIBI: EVOLUTION](http://pferrie.epizy.com/papers/flibi2.pdf?i=1)
  - [FLIBI: RELOADED](http://pferrie.epizy.com/papers/flibi3.pdf)

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

- [Reflections on Trusting Trust](https://www.cs.cmu.edu/~rdriley/487/papers/Thompson_1984_ReflectionsonTrustingTrust.pdf)
- [Static linked ELF infecting](https://packetstormsecurity.com/files/34013/0x4553-Static_Infecting.html.html)
- [Becoming a rat in your system](https://devilinside.me/blogs/becoming-rat-your-system)
- [Last Digital Common Ancestor (LDCA)](https://github.com/mertyildiran/ldca/blob/master/linux_x86/dev.asm)
- [(nearly) Complete Linux Loadable Kernel Modules](http://www.ouah.org/LKM_HACKING.html)
- [Kernel mode hooking [EN]](https://is.muni.cz/el/fi/jaro2011/PV204/um/LinuxRootkits/sys_call_table_complete.htm)

### ELF header hacks

### DWARF stuff

### MISC

- [vx-underground heaven](https://www.vx-underground.org/archive/VxHeaven/lib/vsp44.html)
- [PageBuster](https://rev.ng/blog/pagebuster/post.html)
- [ANSIWAVE BBS](https://ansiwave.net/)
- [WIZARD BIBLE (in Japanese)](https://wizardbible.github.io/)

### Polyglots

- [αcτµαlly pδrταblε εxεcµταblε](https://justine.lol/ape.html)
- [tweetable-polyglot-png](https://github.com/DavidBuchanan314/tweetable-polyglot-png)
- [Architecture Spanning Shellcode](http://phrack.org/issues/57/14.html#article)
- [Doublethink – 8-Architecture Assembly Polyglot](https://www.robertxiao.ca/hacking/defcon2018-assembly-polyglot/)
