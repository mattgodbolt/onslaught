Onslaught
---------

![Image showing a rather retro BBC Micro game](/onslaught.png)

An unreleased, unfinished BBC Micro game from 1993. Written by
 [Rich Talbot-Watkins](https://github.com/richtw1) and [Matt Godbolt](https://github.com/mattgodbolt)
 while they were both still at secondary school, it was due to be published as
 a series of articles in Acorn User until they (understandably) dropped support
 for the BBC Micro.

Short version: the source is in [AllSource](AllSource), in all its early-90s 6502 assembly glory.

The game can be played [in your browser](https://bbc.godbolt.org/?&disc1=sth%3AUnreleased%2FOnslaught-demo.zip&autoboot) (via [jsbeeb](https://github.com/mattgodbolt/jsbeeb)),
 or the SSD can be loaded into your favourite emulator.

### Long version

It is presented here as the original SSD image available also on the
 [Stairway To Hell](https://www.stairwaytohell.com/) archive, [original-disc.ssd](/original-disc.ssd),
 the disc unpacked, and as the source in decoded files. BBC BASIC programs are tokenised, and their
 detokenised equivalents are in the top level. The original code used `*LOAD` (in [Core](/Core)) 
 to load in three parts of the codebase. For convenience the combined code is in [AllSource](/AllSource),
 which is the best place to start reading code.

Charmingly, the [!Help](/unpacked-disc/$.!Help) is written to the Acorn User team, so you can see what
 two teenagers thought were the most important things to get across.

> We believe we are giving the 6502 a good run for its money - printing the whole screen every frame
  at a frame rate of 25 Hz, with up to 16 monsters, 32 bullets/tokens and 128 dots on screen at once!
  As the Beeb falls foul to the technological progress that created the ARM chip, we think that this
  game could be said to be a parting shot, given that things have pretty much dried up these days.
