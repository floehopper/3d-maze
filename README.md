## 3D Maze

### Inspiration

[3D Monster Maze][1]

From Wikipedia:

> A computer game developed from an idea by J.K.Greye and programmed by Malcolm Evans in 1981 for the Sinclair ZX81 platform with the 16 KB memory expansion. The game was initially released by J. K. Greye Software in early 1982 and re-released later the same year by Evans' own startup, New Generation Software. Rendered using low-resolution character block "graphics", it was [one of the first 3D games for a home computer][2], and the first game incorporating typical elements of the genre that would later be termed survival horror.

Video demo: [3D Monster Maze on the Sinclair ZX81][3]

### Provenance

Book: [Graphic Adventures for the Spectrum 48K][4] (Chapter 4)

### Files

* decimal-loader.tap - used to enter and "poke" machine code into memory
* basic.tap - BASIC program to load machine code and run game
* code.tap - machine code saved in 4 chunks
* 3d-maze.tap - combines basic.tap & code.tap

### Errata

* Decimal loader program
  * Missing line: `216 LET D = D + Z`
  * Line 110: `DATA 60000, 60531, 66148` i.e. checksum is 66148, not 66240

[1]: https://en.wikipedia.org/wiki/3D_Monster_Maze
[2]: http://h2g2.com/edited_entry/A821648
[3]: https://www.youtube.com/watch?v=nKvd0zPfBE4
[4]: http://www.worldofspectrum.org/infoseekid.cgi?id=2000168
