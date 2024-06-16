### C64 Cheevos

##### Reading memory from the C64 Debugger
- global methods available in github builds (ie the itch.io bundles)
- global: `c64_cpuReadNS(0xdd00);` 
- g_app methods only available in the c64Debugger enabled (ie lvllvl.com builds)
- from g_app: `g_app.c64Debugger.readByte(0xdd00)`
- ``` Format: ReadByte: 56576 = 151 returns: 151```
