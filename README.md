EL Injector v1.0.0

Windows DLL injector. One executable handles both x86 and x64 targets — you do not pick an architecture build.

Download
- EL injector.exe

Requirements
- Windows 10/11 (64-bit)
- .NET Framework (included with Windows)
- Run as administrator (the app requests elevation)

What's included
- Process list with filter, refresh, and auto-refresh
- Multi-DLL inject, drag-and-drop, delay between DLLs
- Auto-inject when a process starts
- Settings:
  - Methods: Standard, LdrLoadDll Stub, LdrpLoadDll Stub, Thread Hijacking, Manual Map
  - Scramble presets: None, Basic, Standard, Extreme (plus advanced flags)
  - Post-inject: Erase PE headers, Hide module
  - Close on inject, Stealth inject, Start in Secure Mode
- Settings saved next to the exe as el-injector.settings.ini

Notes
- The DLL architecture must match the target process (x86 DLL → x86 process, x64 DLL → x64 process).
- LdrpLoadDll is unreliable on Windows 11+. Prefer Standard, LdrLoadDll, Thread Hijacking, or Manual Map.
- This build is the exe only. Source is not in this release.
