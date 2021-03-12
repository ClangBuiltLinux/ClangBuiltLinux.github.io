## Useful links

[![Build Status next](https://github.com/clangbuiltlinux/continuous-integration2/workflows/next/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3A"next")
[![Build Status mainline](https://github.com/clangbuiltlinux/continuous-integration2/workflows/mainline/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3A"mainline")
[![Build Status 5.10](https://github.com/clangbuiltlinux/continuous-integration2/workflows/5.10/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3A5.10)
[![Build Status 5.4](https://github.com/clangbuiltlinux/continuous-integration2/workflows/5.4/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3A5.4)
[![Build Status 4.19](https://github.com/clangbuiltlinux/continuous-integration2/workflows/4.19/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3A4.19)
[![Build Status 4.14](https://github.com/clangbuiltlinux/continuous-integration2/workflows/4.14/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3A4.14)
[![Build Status 4.9](https://github.com/clangbuiltlinux/continuous-integration2/workflows/4.9/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3A4.9)
[![Build Status 4.4](https://github.com/clangbuiltlinux/continuous-integration2/workflows/4.4/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3A4.4)
[![Build Status android-mainline](https://github.com/clangbuiltlinux/continuous-integration2/workflows/android-mainline/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Aandroid-mainline)
[![Build Status android-5.10](https://github.com/clangbuiltlinux/continuous-integration2/workflows/android-5.10/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Aandroid-5.10)
[![Build Status android-5.4](https://github.com/clangbuiltlinux/continuous-integration2/workflows/android-5.4/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Aandroid-5.4)
[![Build Status android-4.19](https://github.com/clangbuiltlinux/continuous-integration2/workflows/android-4.19/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Aandroid-4.19)
[![Build Status android-4.14](https://github.com/clangbuiltlinux/continuous-integration2/workflows/android-4.14/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Aandroid-4.14)
[![Build Status android-4.9](https://github.com/clangbuiltlinux/continuous-integration2/workflows/android-4.9/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Aandroid-4.9)
[![Build Status lto-cfi](https://github.com/clangbuiltlinux/continuous-integration2/workflows/lto-cfi/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Alto-cfi)
[![Build Status lto-cfi-tip](https://github.com/clangbuiltlinux/continuous-integration2/workflows/lto-cfi-tip/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Alto-cfi-tip)
[![Build Status tip](https://github.com/clangbuiltlinux/continuous-integration2/workflows/tip/badge.svg)](https://github.com/clangbuiltlinux/continuous-integration2/actions?query=workflow%3Atip)

- [Official Kernel Docs](https://www.kernel.org/doc/html/latest/kbuild/llvm.html)
- [Issue tracker](https://github.com/ClangBuiltLinux/linux/issues)
- [Wiki](https://github.com/ClangBuiltLinux/linux/wiki)
- [Repos](https://github.com/ClangBuiltLinux)
- Mailing List: `clang-built-linux@googlegroups.com` ([archive](https://groups.google.com/forum/#!forum/clang-built-linux))
- IRC: `#clangbuiltlinux` on chat.freenode.net ([webchat](http://webchat.freenode.net/?channels=clangbuiltlinux))
- Telegram: [@ClangBuiltLinux](https://t.me/ClangBuiltLinux)
- Bi-weekly video meeting
  - [Calendar](https://calendar.google.com/calendar/embed?src=google.com_bbf8m6m4n8nq5p2bfjpele0n5s%40group.calendar.google.com)
  - [Hangouts Meet](https://meet.google.com/yjf-jyqk-iaz)

The following architectures are targetable from both LLVM and the Linux kernel
and are relatively well supported and tested:
* arm
* arm64
* x86

The following architectures are targetable from both LLVM and the Linux kernel
and are supported and tested in limited configurations:
* mips
* powerpc
* riscv
* s390

The following architectures are targetable from both LLVM and the Linux kernel
but are untested or currently broken:
* arc
* hexagon
* sparc

The following architectures are targetable from the Linux kernel but not LLVM:
* alpha
* c6x
* csky ([WIP](https://reviews.llvm.org/D93798))
* h8300
* ia64
* m68k ([WIP](https://reviews.llvm.org/D95315))
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
