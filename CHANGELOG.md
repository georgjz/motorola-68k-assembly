# Change Log

## [Unreleased]

## [0.4.2] - 2020-Oct-01
### Fixed 
- Issue #14: Add highlighting for address size modifiers

## [0.4.1] - 2020-Oct-01
### Fixed 
- Issue #15: Add a few missing instructions to all syntaxes 
- Issue #16: `exitm` now highlighted correctly
- Issue #18: `:=` now highlighted correctly
- Issue #10: Branch instructions ending with `.s` now highlighted correctly
- Issue #11: Decimal numbers now highlighted

## [0.4.0] - 2020-Oct-01
### Added
- The Macroassembler AS now supported
### Fixed
- Small inconsistency with file naming

- Issue #3; hexadecimal numbers parsed correctly now
## [0.3.0] - 2020-Aug-25
### Added
- NXP ColdFire/CodeWarrior now supported
### Fixed
- Issue #3; hexadecimal numbers parsed correctly now
- Issue #4; local labels prefixed `@` work now
- Issue #5; fixed scope issues with the vasm grammars
- Issue #6; binary numbers prefixed with `-` are no longer a thing

## [0.2.8] - 2020-Jan-07
### Fixed
- Issue #1; register names in the vasm grammars are now highlighted case-insensitively

## [0.2.7] - 2020-Jan-07 
### Fixed
- CHANGELOG versioning error 

## [0.2.6] - 2020-Jan-07 
### Fixed 
- Minus signs before binary numbers are no longer highlighted 

## [0.2.4] - 2019-Dec-16
### Fixed 
- All registers are now highlighted correctly

## [0.2.3] - 2019-Dec-13
### Fixed 
- Test decrement opcodes now highlighted correctly 

## [0.2.3] - 2019-Dec-13
### Fixed 
- Small error where `dc` directives weren't highlighted correctly

## [0.2.1] - 2019-Dec-13
### Added 
- m68k directives added to vasm grammars
### Fixed 
- Strings and escape sequences in the vasm grammars are now highlighted correctly 

## [0.2.0] - 2019-Dec-11
### Added 
- Support for standard syntax in vasm

## [0.1.1] - 2019-Dec-11
### Fixed
- `package.json` Package name corrected

## [0.1.0] - 2019-Dec-11
### Added
- Support for Motorola syntax with vasm assembler 
