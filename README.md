## 3D Maze

### Provenance

Book: [Graphic Adventures for the Spectrum 48K][1] (Chapter 4)

### Files

* decimal-loader.tap - used to enter and "poke" machine code into memory
* basic.tap - BASIC program to load machine code and run game
* code.tap - machine code saved in 4 chunks
* 3d-maze.tap - combines basic.tap & code.tap

### Errata

* Decimal loader program
  * Missing line: `216 LET D = D + Z`
  * Line 110: `DATA 60000, 60531, 66148` i.e. checksum is 66148, not 66240

[1]: http://www.worldofspectrum.org/infoseekid.cgi?id=2000168
