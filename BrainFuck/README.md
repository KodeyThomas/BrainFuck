# BrainFuck

BrainFuck is a increadibly simple language that looks very complicated.

If you break down every step and keep a track of what is in each memory register it's a lot easier.

### Commands

```
[Anything in here will be looped until the Current Register is = 0]
. Prints User Input
, Registers User Input and Saves it to Current Register
> Moves Up One Register
< Moves Down One Register
+ Adds 1 to Current Register
- Subtracts 1 from Current Register
```

### Hello World
This is from my `helloWorld` version 2 project, each line symbolises a printed letter.

```brainfuck
++++++++[>+++++++++<-]>.<          H
++++++++++[>>++++++++++<<-]>>+.    e
+++++++.                           l
.                                  l
+++.<<                             o
++++++++++++++++[>>>++<<<-]>>>.    
---[<<<+++>>>-]<<<.                W
>>.                                o
+++.                               r
------.                            l
--------.                          d
```

### File Structure

In every Project will contain every itteration of my attempts at making something.
In every version folder you will find two files.

`projectName.bf`
and
`projectNameSimplified.bf`

`projectName.bf` contains comments about the values each register contains.
`projectNameSimplified.bf` is the pure brainfuck code.