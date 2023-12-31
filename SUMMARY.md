# Table of contents

* [Cyber Training Guide](README.md)
* [0x0: Introduction](intro.md)
  * [git-good](00-introduction/git-good.md)
  * [root-1](00-introduction/root-1.md)
  * [root-2](00-introduction/root-2.md)
  * [intro](00-introduction/intro.md)

## Binary Exploitation (pwn) <a href="#binex" id="binex"></a>

* [What is Binary Exploitation?](binex/what-is-binary-exploitation.md)
* [0x1: ret2win](binex/01-ret2win/README.md)
  * [win32](binex/01-ret2win/win32.md)
  * [win64](binex/01-ret2win/win64.md)
  * [args](binex/01-ret2win/args.md)
* [0x2: shellcodes](binex/02-shellcodes/README.md)
  * [location](binex/02-shellcodes/location.md)
  * [shell](binex/02-shellcodes/shell.md)
  * [constrained](binex/02-shellcodes/constrained.md)
* [0x3: format strings](binex/03-formats/README.md)
  * [format](binex/03-formats/format.md)
  * [chase](binex/03-formats/chase.md)
  * [bbpwn](binex/03-formats/bbpwn.md)
* [0x4: stack canaries](binex/04-canaries/README.md)
  * [canary](binex/04-canaries/canary.md)
  * [findme](binex/04-canaries/findme.md)
* [0x5: ROP](binex/05-rop/README.md)
  * [rop2win](binex/05-rop/rop2win.md)
  * [split](binex/05-rop/split.md)
  * [callme](binex/05-rop/callme.md)
  * [write4](binex/05-rop/write4.md)
  * [badchars](binex/05-rop/badchars.md)
* [0x6: PIE](binex/06-pie/README.md)
  * [gimme](binex/06-pie/gimme.md)
  * [leak32](binex/06-pie/leak32.md)
  * [leak64](binex/06-pie/leak64.md)
* [0x7: ASLR](binex/07-aslr/README.md)
  * [groundzero](binex/07-aslr/groundzero.md)
  * [stepup](binex/07-aslr/stepup.md)
  * [ret2plt](binex/07-aslr/ret2plt.md)
* [0x8: GOT overwrites](binex/08-got/README.md)
  * [gotem](binex/08-got/gotem.md)
  * [gotem64](binex/08-got/gotem64.md)

## Programming

* [What is the Programming Section?](programming/what-is-the-programming-section.md)
* [0x9: Data Serialization](programming/09-serialization/README.md)
  * [LinkedOps](programming/09-serialization/LinkedOps.md)
  * [Tree](programming/09-serialization/Tree.md)
  * [TeLeVision](programming/09-serialization/TeLeVision.md)
* [0xA: Programming](programming/10-programming/README.md)
  * [Calorie Counting](programming/10-programming/CalorieCounting.md)
  * [Hash](programming/10-programming/Hash.md)
  * [Rock Paper Scissors](programming/10-programming/RockPaperScissors.md)
  * [Watch the Register](programming/10-programming/WatchTheRegister.md)
  * [Supply Stacks](programming/10-programming/SupplyStacks.md)
  * [Rope Bridge](programming/10-programming/RopeBridge.md)
  * [Mountain Climbers](programming/10-programming/MountainClimbers.md)

## Reverse Engineering (RE) <a href="#reverse-engineering" id="reverse-engineering"></a>

* [What is Reverse Engineering?](reverse-engineering/what-is-reverse-engineering.md)
* [0xB: Ghidra](reverse-engineering/11-ghidra/README.md)
  * [hardcode](reverse-engineering/11-ghidra/hardcode.md)
  * [undo](reverse-engineering/11-ghidra/undo.md)
  * [snake](reverse-engineering/11-ghidra/snake.md)

## Toolkit

* [Using Pwntools](toolkit/pwntools/README.md)
  * [Establishing Connection](toolkit/pwntools/connection.md)
  * [Context](toolkit/pwntools/context.md)
  * [Sending/Receiving Data](toolkit/pwntools/data-transfer.md)
  * [The ELF Class](toolkit/pwntools/elf.md)
* [My Workflow](toolkit/workflow/README.md)
  * [Tmux](toolkit/workflow/tmux.md)
  * [Vim](toolkit/workflow/vim.md)
