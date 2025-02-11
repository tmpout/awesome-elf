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
  - [Modern Day ELF Runtime infection via GOT poisoning](https://web.archive.org/web/20130814193623/http://vxheaven.org/lib/vrn00.html)

- Ignacio Sanmillan / Paul Litvak and ELF 101
  - [Executable and Linkable Format 101 - Part 1 Sections and Segments](https://www.intezer.com/blog/research/executable-linkable-format-101-part1-sections-segments/)
  - [Executable and Linkable Format 101 - Part 2: Symbols](https://www.intezer.com/blog/malware-analysis/executable-linkable-format-101-part-2-symbols/)
  - [Executable and Linkable Format 101 - Part 3: Relocations](https://www.intezer.com/blog/malware-analysis/executable-and-linkable-format-101-part-3-relocations/)
  - [Executable and Linkable Format 101 - Part 4: Dynamic Linking](https://www.intezer.com/blog/malware-analysis/executable-linkable-format-101-part-4-dynamic-linking/)

- Ignat Korchagin and object files
  - [How to execute an object file: Part 1](https://blog.cloudflare.com/how-to-execute-an-object-file-part-1/)
  - [How to execute an object file: Part 2](https://blog.cloudflare.com/how-to-execute-an-object-file-part-2/)
  - [How to execute an object file: Part 3](https://blog.cloudflare.com/how-to-execute-an-object-file-part-3/)

- Keith Makan ELF Format Series
  - [Introduction to the ELF Format (Part I): The ELF Header](https://blog.k3170makan.com/2018/09/introduction-to-elf-format-elf-header.html)
  - [Introduction to the ELF Format (Part II): Understanding Program Headers](https://blog.k3170makan.com/2018/09/introduction-to-elf-format-part-ii.html)
  - [Introduction to the ELF Format (Part III): The Section Headers](https://blog.k3170makan.com/2018/09/introduction-to-elf-file-format-part.html)
  - [Introduction to the ELF Format (Part IV): Exploring Section Types and Special Sections](https://blog.k3170makan.com/2018/10/introduction-to-elf-format-part-iv.html)
  - [Introduction to the ELF Format (Part V): Understanding C start up .init_array and .fini_array sections](https://blog.k3170makan.com/2018/10/introduction-to-elf-format-part-v.html)
  - [Introduction to the ELF Format (Part VI): The Symbol Table and Relocations (1)](https://blog.k3170makan.com/2018/10/introduction-to-elf-format-part-vi.html)
  - [Introduction to the ELF Format (Part VI): The Symbol Table and Relocations (2)](https://blog.k3170makan.com/2018/10/introduction-to-elf-format-part-vi_18.html)
  - [Introduction to the ELF Format (Part VI): More Relocation tricks - r_addend execution (3)](https://blog.k3170makan.com/2018/10/introduction-to-elf-format-part-vi-more.html)
  - [Introduction to the ELF Format (Part VII): Dynamic Linking / Loading and the .dynamic section](https://blog.k3170makan.com/2018/11/introduction-to-elf-format-part-vii.html)

- [charngda ELF Format reference (mirror)](https://stevens.netmeister.org/631/elf.html)

- [Linux Foundation Referenced Specifications](https://refspecs.linuxbase.org)

- Manu Garg and ELF Auxiliary Vectors
  - [About ELF Auxiliary Vectors](https://articles.manugarg.com/aboutelfauxiliaryvectors.html)

- MaskRay and ELF interposition
  - [ELF interposition and -Bsymbolic](https://maskray.me/blog/2021-05-16-elf-interposition-and-bsymbolic)

- netspooky and ELF Binary Mangling
  - [ELF Binary Mangling Part 1: Concepts](https://n0.lol/ebm/1.html)
  - [Elf Binary Mangling Part 2: Golfin'](https://n0.lol/ebm/2.html)
  - [Elf Binary Mangling Part 3: Weaponization](https://n0.lol/ebm/3.html)
  - [Elf Binary Mangling Part 4: Limit Break](https://n0.lol/ebm/4.html)

- Orlando Padilla and binary parsers
  - [Analyzing Common Binary Parser Mistakes](http://www.uninformed.org/?v=all&a=12&t=txt)

- Patrick Horgan and main()
  - [How the heck do we get to main()?](http://dbp-consulting.com/tutorials/debugging/linuxProgramStartup.html)

- Robin Hoksbergen and Manually Creating An ELF
  - [Manually Creating An ELF Executable](https://web.archive.org/web/20140130143820/http://www.robinhoksbergen.com/papers/howto_elf.html)

- Samuel A. Falvo II and ELF
  - [On ELF, Part 1](https://kestrelcomputer.github.io/kestrel/2018/01/29/on-elf)
  - [On ELF, Part 2](https://kestrelcomputer.github.io/kestrel/2018/02/01/on-elf-2)

- [richinseattle - Hooking the Linux ELF Loader](https://fuzzing.io/Presentations/200409%20Toorcon%20-%20Hooking%20the%20Linux%20ELF%20Loader/hooking_the_linux_ELF_loader.pdf)


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
  - [pyelftools - Parsing ELF and DWARF in Python](https://github.com/eliben/pyelftools)
  - [GNU poke - an interactive, extensible editor for binary data](https://jemarch.net/poke)
  - [fq - jq for binary formats](https://github.com/wader/fq)
  - [ImHex - a hex editor for reverse engineers](https://github.com/WerWolv/ImHex)
  - [Binsider](https://github.com/orhun/binsider)
    - Binsider is a TUI tool written in Rust that can perform static and dynamic analysis, inspect strings,
      examine linked libraries, and perform hexdumps.

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
  - [ELF Virus infection techniques that work with SCOP](https://github.com/elfmaster/scop_virus_paper)
  - [Saruman - ELF anti-forensics exec](https://github.com/elfmaster/saruman)
  - [AV prototype - 32bit](https://github.com/elfmaster/avu32)
  - [LK rootkit](https://github.com/elfmaster/kprobe_rootkit)
  - Shiva micropatching system
    - [About Shiva](https://arcana-research.io/shiva/)
    - [Source](https://github.com/advanced-microcode-patching/shiva)
    - DEFCON 31 Talk
      - [Video](https://www.youtube.com/watch?v=cWf3fpkJyFo)
      - [Slides](https://media.defcon.org/DEF%20CON%2031/DEF%20CON%2031%20presentations/ElfMaster%20-%20Revolutionizing%20ELF%20binary%20patching%20with%20Shiva%20A%20JIT%20binary%20patching%20system%20for%20Linux.pdf)

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
- PoC executable packer that does not use any custom code to unpack binaries at execution time
  - [Locreate: An Anagram for Relocate](http://uninformed.org/?v=all&a=30&t=txt)
- perljam.pl: A Perl x64 ELF virus by isra
  - [Writeup](https://hckng.org/articles/perljam-elf64-virus.html)
  - [Source code](https://github.com/ilv/vx/blob/main/perljam.pl)
- [stelf-loader: stealthy ELF loader - no files, no execve, no RWX](https://github.com/DavidBuchanan314/stelf-loader)
- [DDexec: run binaries filelessly and stealthily on Linux by overwriting the shell's process with another](https://github.com/arget13/DDexec)
- [Griffiths - Binary Protection Schemes](https://bitlackeys.org/papers/BinaryProtectionSchemes59.pdf)
- [KoviD kernel rootkit](https://github.com/carloslack/KoviD)
- [Offensive capabilities of eBPF and implementation of a rootkit](https://raw.githubusercontent.com/h3xduck/TripleCross/master/docs/ebpf_offensive_rootkit_tfg.pdf)
- [debugoff - linux anti-debugging and anti-analysis rust library](https://github.com/0xor0ne/debugoff)
- [ELF Binaries: One Algorithm to Infect Them All (VXUG Black Mass Volume II)](https://samples.vx-underground.org/Papers/Other/VXUG%20Zines/2023-09-19%20-%20Black%20Mass%20Volume%20II.pdf)
- [grugq & scut: Armouring the ELF: Binary encryption on the UNIX platform](https://grugq.github.io/docs/phrack-58-05.txt)
- [sblip & elfmaster: Secure Code Partitioning With ELF binaries, aka. SCOP](https://bitlackeys.org/papers/secure_code_partitioning_2018.txt) ([mirror](txt/sblip_elfmaster_scop.txt))

### ELF header hacks

### Debugging Formats

- DWARF
  - [dwarf-writer](https://github.com/immunant/dwarf-writer)
  - [gimli - a library for reading and writing the DWARF debugging format](https://docs.rs/gimli/latest/gimli/)
  - [The Almighty DWARF: A Trojan Horse for Program Analysis, Verification, and Recompilation](https://www.philipzucker.com/dwarf-patching/)

- Compact C Type Format
  - [The Compact C Type Format in the GNU toolchain](https://lwn.net/Articles/795384/)
  - [The CTF File Format](https://raw.githubusercontent.com/wiki/oracle/binutils-gdb/files/ctf-spec.pdf)

- Oops Rewind Capability (ORC)
  - [The ORCs are coming!](https://lwn.net/Articles/728339/)
  - [ORC unwinder](https://www.kernel.org/doc/html/next/x86/orc-unwinder.html)

### Programming

- [The Art of Assembly Programming Language](https://www.phatcode.net/res/223/files/html/toc.html)
- [Bit twiddling hacks](https://graphics.stanford.edu/~seander/bithacks.html)
- [Intel® 64 and IA-32 Instruction Set Reference](https://namazso.github.io/x86/)
- [Process name stomping](https://doubleagent.net/process-name-stomping/)
- [System call reference tables for x86, x64, arm and arm64](https://syscall.sh)
- [API for system call references for x86, x64, arm and arm64](https://api.syscall.sh/swagger/index.html)
- [Writing C software without the standard library \[Linux Edition\] - Franc\[e\]sco's Gopherspace](https://gist.github.com/tcoppex/443d1dd45f873d96260195d6431b0989)

### Reverse Engineering and Detection

- Intezer Labs and malware analysis
  - [ELF Malware Analysis 101 Part 1: Linux Threats No Longer an Afterthought](https://www.intezer.com/blog/malware-analysis/elf-malware-analysis-101-linux-threats-no-longer-an-afterthought/)
  - [ELF Malware Analysis 101 Part 2: Initial Analysis](https://www.intezer.com/blog/malware-analysis/elf-malware-analysis-101-initial-analysis/)
  - [ELF Malware Analysis 101 Part 3: Advanced Analysis](https://www.intezer.com/blog/malware-analysis/elf-malware-analysis-101-part-3-advanced-analysis/)
- Lucas Galante + Marcus Botacin and (malware/goodware) binary classification
  - [Forseti](https://github.com/marcusbotacin/ELF.Classifier)
  - [Machine Learning for Malware Detection](https://github.com/marcusbotacin/ELF.Classifier/blob/master/paper/classifier.pdf)
- [Ghidra Patch Diffing](https://cve-north-stars.github.io/docs/Ghidra-Patch-Diffing)
- [drgn - a powerful and flexible debugger](https://blogs.oracle.com/linux/post/enter-the-drgn)
- [Towards Optimal Use of Exception Handling Information for Function Detection](https://arxiv.org/pdf/2104.03168.pdf)
- [Reverse Engineering Ebpfkit Rootkit With BlackBerry's Enhanced IDA Processor
  Tool](https://blogs.blackberry.com/en/2021/12/reverse-engineering-ebpfkit-rootkit-with-blackberrys-free-ida-processor-tool)
- [UPX Recovery Tool](https://github.com/NozomiNetworks/upx-recovery-tool)
- [Userland rootkits are lame](https://grugq.substack.com/p/userland-rootkits-are-lame)
- [OrBit: New Undetected Linux Threat Uses Unique Hijack of Execution Flow](https://intezer.com/blog/incident-response/orbit-new-undetected-linux-threat/)
- elfmaster: Arcana ElfScan
  - [The philosophy of Elves in Linux threat detection](https://arcana-technologies.io/blog/the-philosophy-of-elves-in-linux-threat-detection/)
  - [Source](https://github.com/arcana-technologies/arcana.elfscan)
- [ESET: Ebury is alive but unseen](https://web-assets.esetstatic.com/wls/en/papers/white-papers/ebury-is-alive-but-unseen.pdf)


### ELF Challs and CTFs

- [Crack The ELF!](https://cracktheelf.github.io/) by s0lden

### Misc

- [vxer.io (vxheaven successor)](https://vxer.io/)
- [ANSIWAVE BBS](https://ansiwave.net/)
- [PageBuster](https://rev.ng/blog/pagebuster/post.html)
- [vx-underground heaven](https://www.vx-underground.org/archive/VxHeaven/lib/vsp44.html)
- [WIZARD BIBLE (in Japanese)](https://wizardbible.github.io/)
- [Second Part To Hell](https://github.com/SPTHvx/SPTH)
- [Lotus 1-2-3 for Linux](https://lock.cmpxchg8b.com/linux123.html)
- [The Decompilation wiki](https://decompilation.wiki/)

### Polyglots

- [αcτµαlly pδrταblε εxεcµταblε](https://justine.lol/ape.html)
- [Architecture Spanning Shellcode](http://phrack.org/issues/57/14.html#article)
- [Doublethink – 8-Architecture Assembly Polyglot](https://www.robertxiao.ca/hacking/defcon2018-assembly-polyglot/)
- [Polyglottar, an ISO+TAR+ELF polyglot](https://sysfatal.github.io/polyglottar-en.html)
- [tweetable-polyglot-png](https://github.com/DavidBuchanan314/tweetable-polyglot-png)

### Linker Script Tutorials

- [Everything You Never Wanted To Know About Linker Script](https://mcyoung.xyz/2021/06/01/linker-script/)
- [Linker Script Guide](https://www.phaedsys.com/principals/emprog/emprogdata/thunderbench-Linker-Script-guide.pdf)
- [Most Commented Linker Script in the World](https://blog.thea.codes/the-most-thoroughly-commented-linker-script/)

### macOS - General

- [Papers, Slides and Thesis Archive](https://papers.put.as/macosx/macosx/)

### macOS - Mach-O binary format

- [Mach-O architecture](https://developer.apple.com/documentation/foundation/bundle/1495005-mach-o_architecture/)
- [Mach-O file builders](https://alexdremov.me/mystery-of-mach-o-object-file-builders/)
- [Exploring the Mach-O (4 part series of blogposts)](https://gpanders.com/blog/exploring-mach-o-part-1/)
- [Understanding the Mach-O file format](https://medium.com/@travmath/understanding-the-mach-o-file-format-66cf0354e3f4)
- [Mach-O file format reference](https://github.com/aidansteele/osx-abi-macho-file-format-reference)

### macOS - APFS

- [APFS Reference](https://developer.apple.com/support/downloads/Apple-File-System-Reference.pdf)
- [APFS Structure](https://www.ntfs.com/apfs-structure.htm)
- [APFS Forensics](https://static.ernw.de/whitepaper/ERNW_Whitepaper65_APFS-forensics_signed.pdf)

### macOS - Official Apple resources

- [Apple's docs archive](https://developer.apple.com/library/archive/navigation/)
- [Apple Open Source](https://opensource.apple.com/)
- [XNU](https://github.com/apple-oss-distributions/xnu)
- [Distribution macOS](https://github.com/apple-oss-distributions/distribution-macOS)

### macOS - Mac-related blogs

- [Patrick Wardle Objective-See Blog](https://www.objective-see.com/)
- [Pedro Vilaca Reverse Engineering](https://reverse.put.as/)
- [Howard Oakley (@howardnoakley) - The Eclectic Light Company – Macs, paintings and more](https://eclecticlight.co/)
- [Jeff Johnson (@lapcatsoftware) - The Desolation of Blog](https://lapcatsoftware.com/articles/)
- [Wojciech Reguła (@_r3ggi) Blog](https://wojciechregula.blog/)
- [Scott Knight (@sdotknight) - Reverse engineering and debugging](https://knight.sc/)
- [Zhi Zhou (@CodeColorist) Blog](https://blog.chichou.me/)
- [Kai Lu (@K3vinLuSec) - Fortinet’s macOS posts](https://www.fortinet.com/blog/tags-search?tag=mac-os)
- [Jaron Bradley (@jbradley89) - The Mitten Mac – Mac Incident Response and Threat Hunting](https://themittenmac.com/)
- [Cody Thomas (@itsa_feature) – Medium](https://medium.com/@its_a_feature_)
- [Adam Chester (@xpn) Blog](https://blog.xpnsec.com/)
- [Alex Plaskett (@alexjplaskett) - Blog](https://alexplaskett.github.io/)
- [George Johnson (@GeoSn0w) – Blog](https://geosn0w.github.io/)
- [Harry Moulton (@h3adsh0tzz) - Blog](https://h3adsh0tzz.com/)
- [Sarah Edwards (@iamevltwin) - Blog](https://www.mac4n6.com/)
- [Saagar Jha - Blog](https://saagarjha.com/blog/)
- [LockBoxx (@1njection) - macOS Post Collection](https://lockboxx.blogspot.com/2020/06/macos-post-summary.html)
- [Brandon Azad (@_bazad) - Blog](https://bazad.github.io/)
- [Google Project Zero Bug Tracker - Apple](https://bugs.chromium.org/p/project-zero/issues/list?q=vendor%3DApple&can=1)
- [Cedric Owens (@cedowens) – Medium](https://medium.com/@clowens0716)
- [Christopher Ross (@xorrior) – Medium](https://medium.com/@xorrior)
- [Richie Cyrus (@rrcyrus) – Medium](https://medium.com/@rrcyrus)
- [Phil Stokes (@philofishal) - SentinelOne](https://www.sentinelone.com/blog/tag/macos-security-sentinelone/)
- [Jakob Rieck (0xdead10cc) - Blog](https://ubrigens.com/)
- [Csaba Fitzl (@theevilbit) - Blog](https://theevilbit.github.io/)

### Misc Apple-related resources

- [Apple Knowledge repo](https://github.com/hack-different/apple-knowledge)
- [AppleDB - list of software versions and released hardware](https://appledb.dev/)
- [iOS development wiki (also covers a lot on the *OS internals)](https://iphonedev.wiki/Welcome)
- [macOS Security and Privilege Escalation from HackTricks](https://book.hacktricks.xyz/macos-hardening/macos-security-and-privilege-escalation)
