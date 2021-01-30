## 3D Maze

### Inspiration

[3D Monster Maze][1]

> A computer game developed from an idea by J.K.Greye and programmed by Malcolm Evans in 1981 for the Sinclair ZX81 platform with the 16 KB memory expansion. The game was initially released by J. K. Greye Software in early 1982 and re-released later the same year by Evans' own startup, New Generation Software. Rendered using low-resolution character block "graphics", it was [one of the first 3D games for a home computer][2], and the first game incorporating typical elements of the genre that would later be termed survival horror. -- Wikipedia

Video demo: [3D Monster Maze on the Sinclair ZX81][3]

### Book

* Book: [Graphic Adventures for the Spectrum 48K][4] (Chapter 4, pg 105)
* Errata in decimal loader program:
    * Missing line: `216 LET D = D + Z`
    * Line 110: `DATA 60000, 60531, 66148` i.e. checksum is 66148, not 66240

### Files

* [decimal-loader.tap](https://github.com/floehopper/3d-maze/blob/master/decimal-loader.tap) - used to enter and "poke" machine code into memory
* [basic.tap](https://github.com/floehopper/3d-maze/blob/master/basic.tap) - BASIC program to load machine code and run game
* [code.tap](https://github.com/floehopper/3d-maze/blob/master/code.tap) - machine code saved in 4 chunks
* [3d-maze.tap](https://github.com/floehopper/3d-maze/blob/master/3d-maze.tap) - combines basic.tap & code.tap (this is all you need to be able to play the game)

### Misc

* [Video playing, reviewing and modding the game by James O'Grady](https://www.youtube.com/watch?v=Q656CqMIXLY)
* [Article about the the game on my blog](https://jamesmead.org/blog/2021-01-23-youtube-video-of-my-3d-maze-game-for-the-zx-spectrum)

[1]: https://en.wikipedia.org/wiki/3D_Monster_Maze
[2]: http://h2g2.com/edited_entry/A821648
[3]: https://www.youtube.com/watch?v=nKvd0zPfBE4
[4]: https://github.com/floehopper/3d-maze/blob/master/graphic-adventures-for-the-spectrum-48k-portuguese-edition-chapter4.pdf
