# Limbo by Example

These are programming examples in the spirit of [gobyexample](https://github.com/mmcgrana/gobyexample), but targeted to the Limbo programming language. 

These examples are tested on the [purgatorio](http://code.9front.org/hg/purgatorio/) fork of the Inferno operating system.

Examples will, if they reference lines in source within an explanation, utilize a plumbable string (see: plumb(1)) which indicates the line - or range of lines - which the explanation references.

Examples are composed in acme(1) which allows you to right click these strings to jump to the relevant source lines. 

If you'd like to try Inferno without installing, I recommend trying Pete's on-demand VNC: http://tryinferno.reverso.be/

The `;` rune indicates a command to be run from the Inferno sh(1) shell. 

## Building

If a given example provides a mkfile:

	; mk

Otherwise, there will only be one file, a Limbo source file which can be built with:

	; limbo file.b

You could then run said file with:

	; file

## Index

Core language functionality:

- [Hello World](./HelloWorld)
- [Values](./Values)
- [Constants](./Constants)
- [Loops](./Loops)
- [If Else](./If-Else)
- [Switch Case](./Switch)
- [Arrays](./Arrays)
- [Slices](./Slices)
- [Lists](./Lists)
- [Functions](./Functions)
- [Function References](./Function-Refs)
- [Spawn](./Spawn)
- [Channels](./Channels)
- [Abstract Data Types (ADT's)](./ADTs)
- [Modules](./Modules)
- [Generics, Picks, and Interfaces (kind of)](./Generics)
- [Exceptions](./Exceptions)

Standard library modules:

- [Command-Line Arguments](./Args-M)

## References

- [The Limbo Programming Language](http://doc.cat-v.org/inferno/4th_edition/limbo_language/limbo)
- [Addendum to The Limbo Programming Language](http://www.vitanuova.com/inferno/papers/addendum.pdf)
- [Inferno Programming with Limbo](http://www.gemusehaken.org/ipwl/)
- [A Descent into Limbo](http://doc.cat-v.org/inferno/4th_edition/limbo_language/descent)
- [Limbo Programming](http://www.vitanuova.com/inferno/papers/limbomore.html)
- [Inferno Lab](https://github.com/caerwynj/inferno-lab/)
