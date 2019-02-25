# Summary for kernel fuzzing 


## 1. Open Source Tools 
Syzkaller for \*nix, best of best. from Google    
https://github.com/google/syzkaller   

Bochspwn/Bochspwn Reloaded/Bochspwn Revolution/   
https://github.com/googleprojectzero/bochspwn  
Jurczyk M. Detecting Kernel Memory Disclosure with x86 Emulation and Taint Tracking[R]. 2018.  

Trinity for Linux, fuzzing syscalls.   
https://github.com/kernelslacker/trinity  
https://github.com/zined/kfuzz  

Triforce for Kernel fuzzing   
https://github.com/nccgroup/TriforceLinuxSyscallFuzzer  
https://github.com/timnewsham/TriforceFreeBSDSyscallFuzzer  
https://github.com/timnewsham/TriforceMagenta 


https://github.com/Nicholas1126/MHA_Kernel  
https://github.com/hafgham/Linux_Fuzzing_Project  
https://github.com/gracesrm/LKM-system-call-fuzzing   
https://github.com/oracle/kernel-fuzzing   
https://github.com/riboseinc/fuzzbsd   
https://github.com/mwrlabs/ViridianFuzzer   
https://github.com/sk911215/Fuzzing-Test-of-Linux-Kernel-System-Call   
https://github.com/MatthewTingum/XForceAFL  

KernelFuzzer for Windows 7 / 10, OS X and QNX   
https://github.com/mwrlabs/KernelFuzzer  
https://github.com/jinb-park/kfuzz  

#### For XUN (Mac OS/iOS):  
IMF(CCS'17)   https://github.com/SoftSec-KAIST/IMF   
https://github.com/UKERN-Developers/xnu-kernel-fuzzer   
https://github.com/mwrlabs/OSXFuzz   
https://github.com/MTJailed/XNU-Kernel-Fuzzer   
https://github.com/bringhurst/xnufuzz   
https://github.com/block8437/xnufuzz2   
https://github.com/nnamon/grapevine   
 
For fuzzing OSX kernel vulnerability based on passive inline hook mechanism in kernel mode.   
https://github.com/SilverMoonSecurity/PassiveFuzzFrameworkOSX (chinese introduction: https://zhuanlan.zhihu.com/p/24580787) 

### For Android  
https://github.com/gamozolabs/slime_tree  

https://github.com/datadancer/HIAFuzz   

https://github.com/Digits88/Android-Kernel-debugs   


### Driver fuzzing
https://github.com/k0keoyo/kDriver-Fuzzer  
(An Introduction in chinese: https://www.anquanke.com/post/id/97245 )  
https://github.com/debasishm89/iofuzz   

https://github.com/Cr4sh/ioctlfuzzer   

https://github.com/shjalayeri/ktest   

https://github.com/koutto/ioctlbf   

https://github.com/ucsb-seclab/difuze   
https://www.blackhat.com/docs/eu-17/materials/eu-17-Corina-Difuzzing-Android-Kernel-Drivers.pdf

## 2.Papers 

RedQueen,Checksum/MagicValue Bypass   
https://www.syssec.ruhr-uni-bochum.de/media/emma/veroeffentlichungen/2018/12/17/NDSS19-Redqueen.pdf   

https://lifeasageek.github.io/papers/jeong-razzer.pdf

https://people.cs.kuleuven.be/~stijn.volckaert/papers/2019_NDSS_PeriScope.pdf

#### KAFL  
https://github.com/RUB-SysSec/kAFL   
Schumilo S, Aschermann C, Gawlik R, et al. kafl: Hardware-assisted feedback fuzzing for OS kernels[C]//Adresse: https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-schumilo.pdf  

Pan J, Yan G, Fan X. Digtool: A virtualization-based framework for detecting kernel vulnerabilities[C]//26th {USENIX} Security Symposium ({USENIX} Security 17). USENIX} Association}, 2017: 149-165.  

### Paper in chinese  
  YAO Hong-bo, YIN Liang, WEN Wei-ping. Based on the fuzzing lead to a new mining method based on windows kernel vulnerability.[J]. Netinfo Security. 2011(12).   
  
  ZHAO Yue-hua, DEN Yue-hao. Research and Implementation on Monitoring Race‐condition Vulnerablity in Kernel based on Virtual Machine Monitor[J]. Software Guide. 2015(5):161-164.  
  
  HE Yuan, ZHANG Yu-Qing, ZHANG Guang-Hua. Android driver vulnerability discovery based on black-box genetic algorithm[J]. Chinese Journal of Computers. 2017, 40(5):1031-1043.   
  
  NI Tao. Research on key technologies for detection and exploitation of windows kernel vulnerabilities[D]. Information Engineering University. 2013.   

  DEN Yue-hao. Design and Implementation on monitoring kernel-vulnerability system based on virtual machine monitor[D]. Jiangsu University. 2015   
  
  XU Yong-jian. Research on detecting vulnerabilities in linux driver[D]. Beijing University of Technology. 2015   

## 3.Slides 
https://github.com/richinseattle/EvolutionaryKernelFuzzing/blob/master/slides/Evolutionary%20Kernel%20Fuzzing-BH2017-rjohnson-FINAL.pdf  

Kernel fuzzing with Symbolic Information
https://www.cerias.purdue.edu/assets/symposium/2018-posters/829-D1B.pdf . 

http://archive.hack.lu/2018/Slides_Fuzzing_Workshop_Hack.lu_v1.0.pdf  

https://www.openbsd.org/papers/fuzz-slides.pdf   

https://fuzzinginfo.files.wordpress.com/2012/11/nagy-kernel.pdf   

https://labs.mwrinfosecurity.com/assets/BlogFiles/mwri-fuzzing-the-windows-kernel.pdf   
https://labs.mwrinfosecurity.com/assets/BlogFiles/mwri-Platform-Agnostic-Kernel-Fuzzing-FINAL.pdf  
https://labs.mwrinfosecurity.com/assets/BlogFiles/bg-Windows-Kernel-Fuzzing.pdf

https://conference.hitb.org/hitbsecconf2014kul/materials/D2T1%20-%20Ben%20Nagy%20-%20ALPC%20Fuzzing%20Toolkit.pdf   

ALPC Fuzzing Toolkit https://conference.hitb.org/hitbsecconf2014kul/materials/D2T1%20-%20Ben%20Nagy%20-%20ALPC%20Fuzzing%20Toolkit.pdf   

http://www.ragestorm.net/blogs/wp-content/uploads/Kernel-Exploits.ppt  

https://strlen.de/talks/debug-w-syzkaller.pdf   

https://events.static.linuxfound.org/sites/events/files/slides/AFL%20filesystem%20fuzzing,%20Vault%202016_0.pdf    

#### Android 
https://www.blackhat.com/docs/eu-15/materials/eu-15-Blanda-Fuzzing-Android-A-Recipe-For-Uncovering-Vulnerabilities-Inside-System-Components-In-Android-wp.pdf   

http://events17.linuxfoundation.org/sites/events/files/slides/ILP32_syscall_unit_test_linuxcon_europe_v2.pdf   

#### Driver fuzzing  
https://docs.microsoft.com/en-us/windows-hardware/drivers/devtest/iospy-and-ioattack   


## 4.Other  
https://github.com/k0keoyo/Some-Kernel-Fuzzing-Paper   
