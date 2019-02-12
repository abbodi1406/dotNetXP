# .NET AIO for Windows XP SP3 x86

* Repacked All-in-One installer with latest updates integrated for .NET Framework 1.1 SP1 / 2.0 SP2 / 3.0 SP2 / 3.5 SP1 / 4.0

* Credits for the original installer by [@ricktendo64](https://forums.mydigitallife.net/members/28038/)

* For command-line options and examples, run:  
`dotNetFx_AIO_x86.exe /?`

* Available command line switches:  
```
/y  
Passive mode, shows unattended progress. All packages are installed.  
/ai  
Quiet mode, no progress shown. ALL packages are installed.  
/ain  
Quiet mode, without running ngen executequeueditems.  
/ai1  
Quiet mode, only .NET 1.1 package is installed.  
/ai2  
Quiet mode, only .NET 2.0 package is installed.  
/ai3  
Quiet mode, only .NET 3.5/3.0/2.0 packages are installed.  
/ai4  
Quiet mode, only .NET 4.0 package is installed.  
/gm2  
Optional switch to disable extraction dialog for all other switches.  
/sfxlang:  
Set the program display language, if possible. Example: /sfxlang:1031  
/h | /?  
Display this help.  

Examples:  

Automatically install ALL packages, execute ngen and display progress:  
dotNetFx_AIO_x86.exe /y  
Silently install ALL packages, execute ngen and display no progress:  
dotNetFx_AIO_x86.exe /ai  
Silently install .NET 4.0 package, execute ngen and display no progress:  
dotNetFx_AIO_x86.exe /ai4 /gm2
```
