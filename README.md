# Awesome-AFL
Welcome to Awesome AFL 
========================================================
A curated list of different AFL forks and AFL inspired fuzzers with detailed equivalent academic papers with AFL-fuzzing tutorials

### Projects
- [AFL](http://lcamtuf.coredump.cx/afl/) by [Michal Zalewski](http://lcamtuf.coredump.cx/)
  + Original & first versions of AFL fuzzer, american fuzzy lop is a free security-oriented fuzzer that employs genetic algorithms in order to efficiently increase code coverage of the test cases. So far it helped in detection of significant software bugs in dozens of major free software projects, including X.Org Server, PHP, OpenSSL, pngcrush, bash, Firefox, BIND, Qt, and SQLite. 

- [AFL++](https://github.com/vanhauser-thc/AFLplusplus) by [van Hauser](https://github.com/vanhauser-thc) 
  + afl++ is afl 2.56b with community patches, AFLfast power schedules, qemu 3.1 upgrade + laf-intel support, MOpt mutators, InsTrim instrumentation, unicorn_mode and a lot more!
  
- [WinAFL](https://github.com/googleprojectzero/winafl) by [Ivan Fratric](https://github.com/ifratric)
  + A fork of AFL for fuzzing Windows binaries
  
- [afl-dyninst](https://github.com/talos-vulndev/afl-dyninst) by [Cisco Talos Lab](https://talosintelligence.com/)
  + American Fuzzy Lop + Dyninst == AFL Fuzzing blackbox binaries
  
- [TriforceAFL](https://github.com/nccgroup/TriforceAFL) by [Jesse Hertz and Tim Newsham of nccgroup](https://github.com/nccgroup)
  + This is a patched version of AFL that supports full-system fuzzing using QEMU. The included QEMU has been updated to allow tracing of branches when running a system emulator for x86_64. Extra instructions have been added to start AFL's forkserver, make fuzz settings, and mark the start and stop of test cases.

- [AFL-abiondo](https://github.com/abiondo/afl) by [Abiondo](https://github.com/abiondo)
  + Improved version of AFL-Qemu mode (https://abiondo.me/2018/09/21/improving-afl-qemu-mode/)

- [aflsmart](https://github.com/aflsmart/aflsmart) by [Marcel Böhme](https://github.com/mboehme)
  + Smart Greybox Fuzzing (https://thuanpv.github.io/publications/TSE19_aflsmart.pdf)
  
- [aflfast](https://github.com/mboehme/aflfast) by [Marcel Böhme](https://github.com/mboehme)
  + Coverage-based Greybox Fuzzing as Markov Chain (https://mboehme.github.io/paper/CCS16.pdf)

- [WineAFLplusplusDEMO](https://github.com/andreafioraldi/WineAFLplusplusDEMO) by [Andrea Fioraldi](https://github.com/andreafioraldi)
  + A set of helpers and examples to fuzz Win32 binaries with AFL++ QEMU

- [afl-sensitive](https://github.com/bitsecurerlab/afl-sensitive/tree/cgc) by [Heng Yin](https://www.cs.ucr.edu/~heng/)
  + Be Sensitive and Collaborative: Analyzing Impact of Coverage Metrics in Greybox Fuzzing (https://www.cs.ucr.edu/~heng/pubs/afl-sensitive.pdf)

- [Redqueen](https://github.com/RUB-SysSec/redqueen) by [Syssec lab of Ruhr university of germany](https://www.syssec.ruhr-uni-bochum.de/chair/)
  + REDQUEEN: Fuzzing with Input-to-State Correspondence (http://synthesis.to/papers/NDSS19-Redqueen.pdf)

- [afl-pin](https://github.com/vanhauser-thc/afl-pin) by [van Hauser](https://github.com/vanhauser-thc)
  + run AFL with pintool

- [Driller](https://github.com/shellphish/driller) by [Shellphish team of University of Santa Barbara](https://github.com/shellphish)
  + Augmenting AFL with Symbolic execution, a powerful symbolic execution engine aims at hybrid fuzzing
  
- [AngoraFuzzer](https://github.com/AngoraFuzzer/Angora)
  + Angora is a mutation-based fuzzer. The main goal of Angora is to increase branch coverage by solving path constraints without symbolic execution. Angora: Efficient Fuzzing by Principled Search (https://arxiv.org/abs/1803.01307)
  
- [VUzzer](https://github.com/vusec/vuzzer) by [Systems and Network Security Group at VU Amsterdam](https://www.vusec.net/)
  + VUzzer: Application-aware Evolutionary Fuzzing (https://www.cs.vu.nl/~giuffrida/papers/vuzzer-ndss-2017.pdf)

- [Manul](https://github.com/mxmssh/manul) by [Maksim Shudrak](https://github.com/mxmssh)
  + Manul is a coverage-guided parallel fuzzer for open-source and blackbox binaries on Windows, Linux and MacOS (https://www.slideshare.net/MaximShudrak/shudrak-zero-bugs-found-hold-my-beer-afl-how-to-improve-coverageguided-fuzzing-and-find-new-zerodays-in-tough-targets)
  
- [QSym](https://github.com/sslab-gatech/qsym) by [SSLab of Georgia Tech University](https://gts3.org/)
  + QSYM: A Practical Concolic Execution Engine Tailored for Hybrid Fuzzing

- [netafl](https://gitlab.com/gavz/netafl) by [gavz](https://gitlab.com/gavz)
  + winAFL patch to enable network-based apps fuzzing

- [Unicorefuzz](https://github.com/fgsect/unicorefuzz) by [The Computer Security Group at Berlin University of Technology](https://github.com/fgsect)
  + Fuzzing the Kernel using AFL Unicorn. For details, skim through the WOOT paper or watch this talk at CCCamp19 (https://www.usenix.org/system/files/woot19-paper_maier.pdf)

- [SharpFuzz: AFL-based fuzz testing for .NET](https://github.com/Metalnem/sharpfuzz) by [Nemanja Mijailovic](https://github.com/Metalnem)
  + SharpFuzz is a tool that brings the power of afl-fuzz to .NET platform (https://mijailovic.net/2019/01/03/sharpfuzz/)
  
- [Nautilus - a grammar based feedback fuzzer](https://github.com/RUB-SysSec/nautilus) by [Syssec lab of Ruhr university of germany](https://github.com/RUB-SysSec/nautilus) 
  + https://www.syssec.ruhr-uni-bochum.de/media/emma/veroeffentlichungen/2018/12/17/NDSS19-Nautilus.pdf
  
- [frida-js-afl-instr](https://github.com/andreafioraldi/frida-js-afl-instr) by [Andrea Fioraldi](https://github.com/andreafioraldi)  

- [UnTracer-AFL](https://github.com/FoRTE-Research/UnTracer-AFL) by Stefan Nagy (snagy2@vt.edu) and Matthew Hicks (mdhicks2@vt.edu)
  + [Full-speed Fuzzing: Reducing Fuzzing Overhead through Coverage-guided Tracing](https://arxiv.org/abs/1812.11875)
  
- [kleefl](https://github.com/julieeen/kleefl) by [julieeen](https://github.com/julieeen/kleefl)
  + Seeding fuzzers with symbolic execution



### Tutorials
- [AFL-Workshop](https://github.com/mykter/afl-training)
  + Materials of the "Fuzzing with AFL" workshop by Michael Macnair (@michael_macnair)
  
- [Fuzzing with AFL is an Art](https://moyix.blogspot.com/2016/07/fuzzing-with-afl-is-an-art.html#:~:targetText=American%20Fuzzy%20Lop%2C%20or%20AFL,vulnerabilities%20in%20high%2Dprofile%20software.)
  + an awesome AFL coverage improvement idea by [Brendan Dolan-Gavitt aka moyix](https://twitter.com/moyix) of Computer Science and Engineering Department at NYU-Poly
  
- [Software Exploit Development – Fuzzing with AFL](http://thecyberrecce.net/2017/03/20/software-exploit-development-fuzzing-with-afl/)

- [Basic usage of American Fuzzy Lop with real world examples](https://volatileminds.net/2015/06/29/basic-afl-usage.html)

- [Advanced usage of American Fuzzy Lop with real world examples](https://volatileminds.net/2015/07/01/advanced-afl-usage.html)

- [Advanced AFL usage with real-world examples -- preeny and dictionaries](https://volatileminds.net/2015/08/20/advanced-afl-usage-preeny.html)

- [Advanced AFL usage with real-world examples -- Persistent mode](https://volatileminds.net/2015/08/20/advanced-afl-usage-peristent-mode.html)

- [More advanced usage of AFL with real world examples -- Fuzzing libraries](https://volatileminds.net/2015/08/05/advanced-afl-usage-fuzzing-libraries.html)

- [Fuzzing – how to find bugs automagically using AFL](http://9livesdata.com/fuzzing-how-to-find-bugs-automagically-using-afl)

- [Effective AFL Fuzzing 1: Better Harness](https://oxhat.blogspot.com/2018/09/effective-afl-fuzzing-1-better-harness.html)

- [AFL / WinAFL Tips and Tricks](https://blog.fadyothman.com/afl-tips-tricks/)

- [Hunting For Bugs With AFL 101 - A PRIMER](https://research.aurainfosec.io/hunting-for-bugs-101/)

- [Fuzzing capstone using AFL persistent mode](https://toastedcornflakes.github.io/articles/fuzzing_capstone_with_afl.html)

- [afl-unicorn: Fuzzing Arbitrary Binary Code](https://hackernoon.com/afl-unicorn-fuzzing-arbitrary-binary-code-563ca28936bf)

- [INTRO TO AMERICAN FUZZY LOP – FUZZING WITH ASAN AND BEYOND](https://countuponsecurity.com/2018/04/24/intro-to-american-fuzzy-lop-fuzzing-with-asan-and-beyond/)

- [Guided Fuzzing with Driller](https://blog.grimm-co.com/post/guided-fuzzing-with-driller/)

- [Super Awesome Fuzzing, Part One](https://blog.f-secure.com/super-awesome-fuzzing-part-one/)

- [INTRO TO AMERICAN FUZZY LOP – FUZZING IN 5 STEPS](https://countuponsecurity.com/2018/03/07/intro-to-american-fuzzy-lop-fuzzing-in-5-steps/)

- [How to Use Fuzzing in Security Research](https://www.ixiacom.com/company/blog/how-use-fuzzing-security-research)

- [Investigating Windows Graphics Vulnerabilities: A Reverse Engineering and Fuzzing Story](https://www.ixiacom.com/company/blog/investigating-windows-graphics-vulnerabilities-reverse-engineering-and-fuzzing-story)

- [Hunting For Bugs With AFL 101 - A PRIMER](https://research.aurainfosec.io/hunting-for-bugs-101/)

- [Fuzzing arbitrary functions in ELF binaries](https://blahcat.github.io/2018/03/11/fuzzing-arbitrary-functions-in-elf-binaries/)

- [Filesystem Fuzzing with American Fuzzy Lop](https://events.static.linuxfound.org/sites/events/files/slides/AFL%20filesystem%20fuzzing%2C%20Vault%202016_0.pdf)

- [Fuzzing workflows; a fuzz job from start to finish](https://foxglovesecurity.com/2016/03/15/fuzzing-workflows-a-fuzz-job-from-start-to-finish/)

- [Finding pearls; fuzzing ClamAV](https://foxglovesecurity.com/2016/06/13/finding-pearls-fuzzing-clamav/)

- [Tutorial: Fuzzing GIMP](https://flimp.fuzzing-project.org/tutorial-fuzzing-gimp.html)

- [Fuzzing projects with american fuzzy lop (AFL)](https://0x00sec.org/t/fuzzing-projects-with-american-fuzzy-lop-afl/6498)

- [Fuzzing with AFL](https://breaking-bits.gitbook.io/breaking-bits/vulnerability-discovery/fuzzing-with-afl)

- [Starting fuzz with AFL](https://www.w0lfzhang.com/2017/11/30/Starting-fuzz-with-AFL/)
