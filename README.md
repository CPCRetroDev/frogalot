# Frogalot / CNGSoft

### Second Ranked at [#CPCRetroDev 2015 Game Creation Contest](http://cpcretrodev.byterealms.com/contest-en/cpcretrodev-2015/) and Best Technical Achievement Award

This is the source code for the game Frogalot, by César Nicolás González ([CNGSoft](http://cngsoft.no-ip.org/index.htm))

## Requirements

In order to be able to compile this code, you need:
* [AS80 Assembler](http://www.kingswood-consulting.co.uk/assemblers/) 

## Compilation instructions

Having AS80 Assembler installed or simply copied to `src/` folder, just type:
```
as80 -inzx3 -lNUL FROGALOT.S80
```
Under Windows you may have to change `as80` into `as80.exe`.

This command will produce a Z80 binary file that you will have to include in a DSK or CDT container, if you wanted to execute it in any regular emulator. Alternatively, you could directly load binary directly into memory (most emulators have this feature included).

## Credits
* Code, graphics and music by [César Nicolás González (CNGSoft)](http://cngsoft.no-ip.org/index.htm)
* AS80 Assembler by [Frank A. Kingswood](http://www.kingswood-consulting.co.uk/frank/)
* ZX7 Compressor (used to create the final binary): [Einar Saukas](http://www.ime.usp.br/~einar/)

## Acknowledgements

* To John M. Phillips, original author of "Nebulus", great inspiration to create "Frogalot", and Chris Wood, who converted original "Nebulus" version (Commodore 64) to Amstrad CPC, which also was my first tape game, which I still keep well preserved.

* To Rob Hubbard, legendary musical composer who made so many C64 songs, to whom I try to yield tribute with my own free version of his very famous 4th song from "The Human Race", published by Mastertronic in 1985.

* To Granados brothers (Charlie and Jorge), respected Spanish videogame veterans, whose game "Humphrey" will always take a place in my heart for its own cover visual style and graphics.

* To James Higgins and Simon Butler from Ocean Software for their artistic labour and unmistakable style (specially in 16-bits) which I also tried to mimic in Frogalot's graphics, with much less talent I should say.

* To Stamper brothers, founders of unforgettable Ultimate / A.C.G., to whose game "Knight Lore" I have included a gesture in the visual effects shown when the hero loses a life.

* To Robert Zemeckis for the memorable trilogy "Back to the Future", whose flux condenser appears in Frogalot as a bonus which gives back time and energy to the player.

* To my friends Benjamín R, Daniel, Eddy-Boy, Epi, Javi, Jose, etc. Without them, Frogalot would have never existed.

* To the organizers of the [#CPCRetroDev 2015](http://cpcretrodev.byterealms.com) contest for creating this so interesting contest.
