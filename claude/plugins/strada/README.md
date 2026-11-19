# Strada plugin for Claude Code

This plugin adds one skill, `strada`, which teaches Claude to write, compile,
run, test and debug programs in Strada, the strongly typed Perl-inspired
language that compiles to C and native executables. It covers the compile/check
loop, the places where Perl habits go wrong, OOP, tests, and C interop, and it
ships the full language and builtin references for Claude to consult.

## Install

    /plugin install strada --marketplace strada-lang/strada-lang.github.io

or, on older Claude Code:

    /plugin marketplace add strada-lang/strada-lang.github.io
    /plugin install strada@strada-lang

The skill needs a Strada toolchain on the machine (`strada` on PATH, or a
strada-lang checkout) and a C compiler. Details:
https://strada-lang.github.io/docs/claude.html
