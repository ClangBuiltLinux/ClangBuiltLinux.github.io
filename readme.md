## Meetups
- Nov 11, 2022 - [4th Annual ClangBuiltLinux Meetup](/meetup.md) - Richmond, VA
- Nov 13-15, 2022 - [Toolchains Track](https://lpc.events/event/17/sessions/156/) @ [Linux Plumbers Conf 2023](https://lpc.events/event/17/) - Richmond, VA

## Useful links

- [Official Kernel Docs](https://www.kernel.org/doc/html/latest/kbuild/llvm.html)
- [Issue tracker](https://github.com/ClangBuiltLinux/linux/issues)
- [Build Status](https://github.com/ClangBuiltLinux/continuous-integration2/#readme)
- [Wiki](https://github.com/ClangBuiltLinux/linux/wiki)
- [Repos](https://github.com/ClangBuiltLinux)
- Mailing List: `llvm@lists.linux.dev`
  - [Subscribe](mailto:llvm+subscribe@lists.linux.dev) (send a blank email to the address and follow the instructions you receive)
  - [Current archive](https://lore.kernel.org/llvm/)
  - [Old archive](https://groups.google.com/g/clang-built-linux)
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
* um (usermode)

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
