# Motorola 68000 Assembly Language Extension for VS Code

This is a Language Extension for [Visual Studio Code][vsc]. It adds syntax highlighting for the [Motorola 68000][mot] and its variants.

## Supported Assemblers 

Currently, this extension supports the following assemblers:
- [vasm][vsm]

Planned support for:
- vasm standard syntax
- m68k-elf-as 
- SNASM2
- Sierra 68000 Assembler 

This is not a complete list. If you have a wish or suggestion, please use the issue function of this repository to submit an assembler. If you provide a link to its documentation, that will speed things up.


## Planned Features

- Some kind of linter that will check for errors for the chosen assembler
- Customization options 
- Code snippets 
- 

## Known Issues / Bugs

If you find a bug or error, please submit an issue to this repository. A screenshot and informations about your system (OS, VS code version) will help a lot.

## Release Notes

### 0.1.0

Initial release. Only supports [vasm][vsm].


[vsm]: http://sun.hasenbraten.de/vasm/
[vsc]: https://code.visualstudio.com
[mot]: https://en.wikipedia.org/wiki/Motorola_68000
