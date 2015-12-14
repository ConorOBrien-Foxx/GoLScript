# GoLScript
A programming language from the Game of Life

## Style
GoLScript runs in _generations_; this is a step. At the beginning of every step, the code is evaluated. From the top left, to the end of each line, scanning lines downwards, upper-case and certain symbols are evaluated. You can find what each command does in the **Commands** section.

Symbols on the program come in two states: live or dead. A symbol is _live_ if and only if it is an uppercase letter, or one of `@`, `!`, or `<`. A symbol is _dead_ otherwise. A symbol can shift its state from dead to live when it has precisely three neighbours. A cell goes from live to dead when it does not have two or three neighbours.

## Commands
These appear in the form `Live symbol/dead symbol - effect`
 * `A`/`a` - Push `0` to the stack.
 * `B`/`b` - Push `1` to the stack.
 * `C`/`c` - Push `2` to the stack.
 * `D`/`d` - Push `3` to the stack.
 * `E`/`e` - Push `4` to the stack.
 * `F`/`f` - Push `5` to the stack.
 * `G`/`g` - Push `6` to the stack.
 * `H`/`h` - Push `7` to the stack.
 * `I`/`i` - Push `8` to the stack.
 * `J`/`j` - Push `9` to the stack.
 * `K`/`k` - Pops `b`, `a`, and pushes `a+b`.
 * `L`/`l` - Pops `b`, `a`, and pushes `a-b`.
 * `M`/`m` - Pops `b`, `a`, and pushes `a*b`.
 * `N`/`n` - Pops `b`, `a`, and pushes `a/b`.
 * `O`/`o` - Pops `b`, `a`, and pushes `a%b`.
