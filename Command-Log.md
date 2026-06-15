


sudo kextunload -b com.apple.Dont_Steal_Mac_OS_X -verbose 6  
Kext user-space log filter changed from 0xff2 to 0xfff.
Kext kernel-space log filter changed from 0xff2 to 0xfff.
Executing: /usr/bin/kmutil unload -b com.apple.Dont_Steal_Mac_OS_X
Error Domain=KMErrorDomain Code=71 "Kernel request failed: (libkern/kext) kext is in use or retained (cannot unload) (-603946984)" UserInfo={NSLocalizedDescription=Kernel request failed: (libkern/kext) kext is in use or retained (cannot unload) (-603946984)}
