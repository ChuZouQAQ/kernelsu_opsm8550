***Read the README first***  
main branch only support android16  
How to use:

Fork this repo(remember to sync before using)  
Turn to Actions page in ur repo  
Select clang version(clang-r547379 for a16qpr0 r563880/r563880c for a16qpr2)  
Select the kernel source code(PixelOS select OnePlus12R-development)  
Enter ur Kernel Branch(See this in ur kernel source repo,such as lineage-23.2 for los 16.0 for crd, sixteen-qpr2 for pos)  
Select the KernelSU/KernelSU forks that u need(susfs maybe broken, it is controlled by simonpunk)  

Current ReSukiSU options:
`ReSukiSU-with-susfs` = ReSukiSU + susfs, without KPM
`ReSukiSU-with-susfs-KPM` = ReSukiSU + susfs + KPM

Current notice:
`KernelSU-Next-with-susfs` is unstable upstream right now, do not use it until a known-good upstream ref is pinned.

ksu toolkit:
https://github.com/backslashxx/ksu_toolkit

Inferno's build(ksu ksunext sukisu)
https://github.com/inferno0230/kernel_oneplus_sm8550-CI
