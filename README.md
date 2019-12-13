# Motorola 68000 Assembly Language Extension for VS Code

This is a Language Extension for [Visual Studio Code][vsc]. It adds syntax highlighting for the [Motorola 68000][mot] and its variants.

## Supported Assemblers 

Currently, this extension supports the following assemblers. In general, the grammar's name takes the form of "68k Assembly (assembler name)":
- [vasm][vsm]
    - `vasmm68k_mot`: [Mot Syntax Module][vasmmot], the grammar is called "68k Assembly (vasmm68k_mot)"
    - `vasmm68k_std`: [Standard Syntax Module][vasmstd], the grammar is called "68k Assembly (vasmm68k_std)"

Planned support for:
- m68k-elf-as 
- SNASM2
- Sierra 68000 Assembler 

This is not a complete list. If you have a wish or suggestion, please use the [issue function][iss] of the GitHub repository to submit an assembler. If you provide a link to its documentation, that will speed things up.


## Planned Features

- Some kind of linter that will check for errors for the chosen assembler
- Customization options for comments (think, `;` vs `*` vs `#`)
- Common snippets/macros for faster coding
- A Z80 assembly injection for Sega Genesis/Mega Drive programming

Please feel free to submit an [issue][iss] to make a suggestion. They're greatly appreciated.

## Known Issues / Bugs

- None at the moment 

If you find a bug or error, please submit an [issue][iss] to this repository. A screenshot and informations about your system (OS, VS code version) will help a lot.

## Release Notes

For more detailed changes, see `CHANGELOG.md`.

### 0.2.1 

Add m68k module directives to vasm grammars. Fix strings and escape command hightlighting in same grammars.

### 0.2.0

Add support for [vasmm68k_std assembler][vasmstd].

### 0.1.0

Initial release. Only supports [vasm][vsm].


[vsm]: http://sun.hasenbraten.de/vasm/
[vasmmot]: http://sun.hasenbraten.de/vasm/release/vasm.html
[vasmstd]: http://sun.hasenbraten.de/vasm/release/vasm.html
[vsc]: https://code.visualstudio.com
[mot]: https://en.wikipedia.org/wiki/Motorola_68000
[iss]: https://github.com/georgjz/motorola-68k-assembly/issues