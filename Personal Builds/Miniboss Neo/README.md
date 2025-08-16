# Miniboss NEO

![I don't actually have a joke about minibosses](../../img/personal/miniboss.png)

---

A variation on the Goblin build, adding two extra thumb buttons to a WASD layout alongside a Nunchuk port.

Originally I wanted it to have a standard acrylic plate && art (a 4K render of CTF-Face if you want to know), but at the time I completed this build, both my local printer and fablab were on vacation. Cue improvisation sequence.

## The Stats

**Printability**: 5/5 (very few supports, as long as you have a good bed level it should be a breeze)  
**Buildability**: 4/5 (it's basically identical to the Goblin, with four extra wires to deal with)  
**Extra hardware**: 4/5 (all of it can be easily bought online)  
**Price**: 4/5 (it's the Goblin with like five Euros more because of the Nunchuk breakout)

## Materials needed

- 6x M4 x 25mm "Chicago bolts"
- 17x MX-style switches
- (Optional) 23x MX-style hotswap sockets (way easier to solder to than bare pins)
- 14x round caps (see below)
- 3x square keyboard caps
- 4x 200 by 3mm metal rods (either brass or steel to taste)
- (Technically optional) 1x Adafruit Nunchuk breakout

## Printing

Print the chassis halves. Print the bottom pieces. Print the top pieces if that's what you want, or go get some acrylic laser cut.

I swear it's *that* straightforward.

## Building

Assemble the two top halves, using the rods for alignment and support. Plastic weld or glue if you feel like it. Do the same for the bottom halves.

Insert all your switches in the square holes; they're friction fit. Save the caps for later.

Use the solid core wire to wrap hooks (or loops if you're really dextrous) around the pins of the switches. If you use hotswap sockets, you might need to strip some extra. Solder those hooks and go from pin to pin until you have grounded all your switches. (You don't need to ground them all on the same rail, it just helps if you have a limited number of ground pins)

At this point you have a couple of options, all valid:  
- Leave a length of solid core wire after you're done hooking everything up, connect it directly to a ground pin on whatever board you use
- Do the same but a shorter length, use a Wago or screw terminal, and continue your ground path to the board with a stranded core wire
- Directly wrap stranded core wire above/around the last ground pin in the chain and connect *that* to the board

Switch to stranded core from this point onwards.

Measure lengths of wire and strip one end (don't be afraid of overdrawing at the wire bank so to speak - it's best to measure twice and cut once than it is to try to splice bits of wire together afterwards). Solder that end into your board.Measure how long you need to go to a given switch pin, add a couple centimeters, strip the wire, and wrap it around the switch pin to solder it.

Now how you make the board communicate with the outside world (and hopefully with a host type device such as a PC or a game console) is up to you; there are a lot of boards and even more cables, panel mounted cables, breakout cables and so on, and I realistically can't cover every case.

I encourage you to closely inspect your wiring job at this point, and most importantly test it !

Once you're done, set the caps onto your switches. Support them from the back while doing so to avoid damaging your wires.

Bask in the Ikea Effect before realizing you forgot to wire the Nunchuk breakout. For that matter, you haven't even printed its holding bracket. At this point I don't think I need to tell you how to proceed, do I ?

## Caps

You pretty much have two ways of going about this:

- Obtain a set of 14 SiTong 24mm caps; those are 20.6mm across and will fit perfectly, **OR**
- Print them yourself (PLA is not recommended although that depends on your particular brand; PETG is much better). [Rana-sylvatica's keycaps](https://github.com/rana-sylvatica/circle-keycaps/tree/main) are a good bet, but anything with a MX compatible stem that is less than 21mm across should be okay

## Acknowledgements

- [jfedor's Flatbox](https://github.com/jfedor2/flatbox) for being the OG inspiration
- [The GP2040-CE project](https://gp2040-ce.info) for being an awesome firmware and for their Discord server re-teaching me how to solder
