# windows sysinternals
```
官方網站

https://docs.microsoft.com/en-us/sysinternals/
https://technet.microsoft.com/網站搜尋與下載coreinfo.exe程式!

```
## 學習資源
```
https://live.sysinternals.com/

下載 Coreinfo.exe
```
## coreinfo.exe指令
```
coreinfo [-c][-f][-g][-l][-n][-s][-m][-v]

USING COREINFO
Parameter	Description
-c	Dump information on cores.
-f	Dump core feature information.
-g	Dump information on groups.
-l	Dump information on caches.
-n	Dump information on NUMA nodes.
-s	Dump information on sockets.
-m	Dump NUMA access cost.
-v	Dump only virtualization-related features 
    including support for second level address translation.
```
## 電腦管理

```
在Windows搜尋欄輸入[電腦管理]①，然後點選[以系統管理員身分執行]
```
## 環境變數管理
```
dir env:
```
## dir env: 執行畫面
```
PS C:\Users\I5302> dir env:

Name                           Value
----                           -----
ALLUSERSPROFILE                C:\ProgramData
APPDATA                        C:\Users\I5302\AppData\Roaming
CommonProgramFiles             C:\Program Files\Common Files
CommonProgramFiles(x86)        C:\Program Files (x86)\Common Files
CommonProgramW6432             C:\Program Files\Common Files
COMPUTERNAME                   2-2
ComSpec                        C:\Windows\system32\cmd.exe
FP_NO_HOST_CHECK               NO
HOMEDRIVE                      C:
HOMEPATH                       \Users\I5302
KICAD_SYMBOL_DIR               C:\Program Files\KiCad\share\kicad\library
KICAD_TEMPLATE_DIR             C:\Program Files\KiCad\share\kicad\template
KISYS3DMOD                     C:\Program Files\KiCad\share\kicad\modules\packages3d
KISYSMOD                       C:\Program Files\KiCad\share\kicad\modules
LOCALAPPDATA                   C:\Users\I5302\AppData\Local
LOGONSERVER                    \\2-2
MpConfig_ProductAppDataPath    C:\ProgramData\Microsoft\Windows Defender
MpConfig_ProductCodeName       AntiSpyware
MpConfig_ProductPath           C:\Program Files\Windows Defender
MpConfig_ProductUserAppData... C:\Users\I5302\AppData\Local\Microsoft\Windows Defender
MpConfig_ReportingGUID         A70CD637-0107-463D-A603-01D796B8CB90
NUMBER_OF_PROCESSORS           8
OS                             Windows_NT
Path                           %SystemRoot%\system32\WindowsPowerShell\v1.0\;C:\Program Files (x86)\Common Files\Ora...
PATHEXT                        .COM;.EXE;.BAT;.CMD;.VBS;.VBE;.JS;.JSE;.WSF;.WSH;.MSC
PROCESSOR_ARCHITECTURE         AMD64
PROCESSOR_IDENTIFIER           Intel64 Family 6 Model 60 Stepping 3, GenuineIntel
PROCESSOR_LEVEL                6
PROCESSOR_REVISION             3c03
ProgramData                    C:\ProgramData
ProgramFiles                   C:\Program Files
ProgramFiles(x86)              C:\Program Files (x86)
ProgramW6432                   C:\Program Files
PSModulePath                   C:\Users\I5302\Documents\WindowsPowerShell\Modules;C:\Windows\system32\WindowsPowerSh...
PUBLIC                         C:\Users\Public
RTOOLS40_HOME                  C:\rtools40
SESSIONNAME                    Console
SystemDrive                    C:
SystemRoot                     C:\Windows
TEMP                           C:\Users\I5302\AppData\Local\Temp
TMP                            C:\Users\I5302\AppData\Local\Temp
USERDOMAIN                     2-2
USERNAME                       I5302
USERPROFILE                    C:\Users\I5302
VBOX_MSI_INSTALL_PATH          C:\Program Files\Oracle\VirtualBox\
VS120COMNTOOLS                 C:\Program Files (x86)\Microsoft Visual Studio 12.0\Common7\Tools\
WEBOTS_HOME                    C:\Program Files\Webots
windir                         C:\Windows
windows_tracing_flags          3
windows_tracing_logfile        C:\BVTBin\Tests\installpackage\csilogfile.log
```
