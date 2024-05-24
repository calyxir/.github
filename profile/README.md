# The Calyx Infrastructure

[Calyx][] is an open-source infrastructure for compiling high-level programming languages to efficient hardware designs. Calyx provides a modular, pass-based compiler that optimizes and lowers an intermediate language into Verilog.

- [Get started with Calyx][docs]
- [Building a frontend with Calyx][frontend]
- [Using Calyx with LLVM CIRCT][circt-use]

If you're working with Calyx and need help, please [join the Zulip chat][zulip] and say hi! You can also [open an issue][issue] or [start a discussion][disc]!

### FAQs

**Q. Doesn't the [LLVM CIRCT][circt] project do the same thing as Calyx?**<br/>
CIRCT is an umbrella project to build a variety of open-source programming tools for hardware design. CIRCT does provide the ability to compile high-level programs (written in dialects such as `affine`) to hardware but internally uses [Calyx itself][calyx-dialect] to do so.

[circt]: https://circt.llvm.org
[calyx-dialect]: https://circt.llvm.org/docs/Dialects/Calyx/
[docs]: https://docs.calyxir.org/
[frontend]: https://docs.calyxir.org/builder/calyx-py.html
[calyx]: https://calyxir.org
[circt-use]: https://docs.calyxir.org/fud/circt.html
[issue]: https://github.com/calyxir/calyx/issues
[disc]: https://github.com/calyxir/calyx/discussions
[zulip]: https://calyx.zulipchat.com/
