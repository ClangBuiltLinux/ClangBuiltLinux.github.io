## Useful links

[![Build Status next](https://github.com/clangbuiltlinux/continuous-integration2/workflows/next/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3A"next")
[![Build Status mainline](https://github.com/clangbuiltlinux/continuous-integration2/workflows/mainline/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3A"mainline")
[![Build Status 5.15](https://github.com/clangbuiltlinux/continuous-integration2/workflows/5.15/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3A5.15)
[![Build Status 5.10](https://github.com/clangbuiltlinux/continuous-integration2/workflows/5.10/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3A5.10)
[![Build Status 5.4](https://github.com/clangbuiltlinux/continuous-integration2/workflows/5.4/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3A5.4)
[![Build Status 4.19](https://github.com/clangbuiltlinux/continuous-integration2/workflows/4.19/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3A4.19)
[![Build Status 4.14](https://github.com/clangbuiltlinux/continuous-integration2/workflows/4.14/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3A4.14)
[![Build Status 4.9](https://github.com/clangbuiltlinux/continuous-integration2/workflows/4.9/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3A4.9)
[![Build Status 4.4](https://github.com/clangbuiltlinux/continuous-integration2/workflows/4.4/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3A4.4)
[![Build Status android-mainline](https://github.com/clangbuiltlinux/continuous-integration2/workflows/android-mainline/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Aandroid-mainline)
[![Build Status android13-5.10](https://github.com/clangbuiltlinux/continuous-integration2/workflows/android13-5.10/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Aandroid13-5.10)
[![Build Status android12-5.10](https://github.com/clangbuiltlinux/continuous-integration2/workflows/android12-5.10/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Aandroid12-5.10)
[![Build Status android12-5.4](https://github.com/clangbuiltlinux/continuous-integration2/workflows/android12-5.4/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Aandroid12-5.4)
[![Build Status android-4.19](https://github.com/clangbuiltlinux/continuous-integration2/workflows/android-4.19/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Aandroid-4.19)
[![Build Status android-4.14](https://github.com/clangbuiltlinux/continuous-integration2/workflows/android-4.14/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Aandroid-4.14)
[![Build Status android-4.9](https://github.com/clangbuiltlinux/continuous-integration2/workflows/android-4.9/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Aandroid-4.9)
[![Build Status lto-cfi](https://github.com/clangbuiltlinux/continuous-integration2/workflows/lto-cfi/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Alto-cfi)
[![Build Status lto-cfi-tip](https://github.com/clangbuiltlinux/continuous-integration2/workflows/lto-cfi-tip/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Alto-cfi-tip)
[![Build Status tip](https://github.com/clangbuiltlinux/continuous-integration2/workflows/tip/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Atip)
[![Build Status arm64](https://github.com/clangbuiltlinux/continuous-integration2/workflows/arm64/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Aarm64)
[![Build Status arm64-fixes](https://github.com/clangbuiltlinux/continuous-integration2/workflows/arm64-fixes/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Aarm64-fixes)

- [Official Kernel Docs](https://www.kernel.org/doc/html/latest/kbuild/llvm.html)
- [Issue tracker](https://github.com/ClangBuiltLinux/linux/issues)
- [Wiki](https://github.com/ClangBuiltLinux/linux/wiki)
- [Repos](https://github.com/ClangBuiltLinux)
- Mailing List: `llvm@lists.linux.dev` ([current archive](https://lore.kernel.org/llvm/), [old archive](https://groups.google.com/g/clang-built-linux))
- IRC: `#clangbuiltlinux` on [irc.libera.chat](https://libera.chat/guides/connect) ([web client](https://web.libera.chat/?channel=#clangbuiltlinux))
- Telegram: [@ClangBuiltLinux](https://t.me/ClangBuiltLinux)
- Discord: `#clang-built-linux` in the [LLVM server](https://discord.gg/xS7Z362)
- Bi-weekly video meeting
  - [Calendar](https://calendar.google.com/calendar/embed?src=google.com_bbf8m6m4n8nq5p2bfjpele0n5s%40group.calendar.google.com)
  - [Hangouts Meet](https://meet.google.com/yjf-jyqk-iaz)

The following architectures are targetable from both LLVM and the Linux kernel
and are relatively well supported and tested:
* arm
* arm64
* hexagon
* s390
* x86

The following architectures are targetable from both LLVM and the Linux kernel
and are known to work in specific/limited configurations and supported on a
best-effort basis:
* mips
* powerpc
* riscv

The following architectures are targetable from both LLVM and the Linux kernel
but are untested or currently broken:
* arc
* csky
* m68k
* sparc

The following architectures are targetable from the Linux kernel but not LLVM:
* alpha
* c6x
* h8300
* ia64
* microblaze
* nds32
* nios2
* openrisc
* parisc
* sh
* xtensa

The following architectures are targetable from LLVM but not the Linux kernel:
* amdgpu
* avr
* bpf
* lanai
* msp430
* nvptx
* ve
* webassembly
* xcore
