<div align="center">

---

[![GitHub stars](https://img.shields.io/github/stars/LaurieWired/REverseKeynote2026)](https://github.com/LaurieWired/REverseKeynote2026/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/LaurieWired/REverseKeynote2026)](https://github.com/LaurieWired/REverseKeynote2026/network/members)
[![GitHub contributors](https://img.shields.io/github/contributors/LaurieWired/REverseKeynote2026)](https://github.com/LaurieWired/REverseKeynote2026/graphs/contributors)
[![Follow @lauriewired](https://img.shields.io/twitter/follow/lauriewired?style=social)](https://twitter.com/lauriewired)

</div>

---

# Thinking Like a Compiler: Obfuscation from the Other Side

Originally presented at [RE//verse 2026](https://re-verse.io)

Slides Available Here: [Slides](https://github.com/LaurieWired/REverseKeynote2026/blob/main/ThinkingLikeACompiler.pdf).

## Abstract

Reverse Engineers have it backwards. You're fighting the compiler without understanding how it fights. The most skilled obfuscation engineers (and programmers!) comprehend compiled applications at the input level. They write LLVM passes that insert control flow flattening and opaque predicates directly into the build. They adopt Rust before the RE community has the tooling for it. They design custom VM bytecode that no decompiler will ever support.

It's tempting to leap directly into a compiled binary, but the best way to defeat a transformation is to write it yourself. In this talk, we will stop treating the binary as a black box and start treating the compiler as a surgical tool. We'll build obfuscation techniques, hostile optimizations, and LLVM customizations from scratch. Using Compiler Explorer, C++ Insights, and BinDiff, we'll map each technique from source, to assembly, to decompiled binary.

Stop guessing at the output. Master the input.
