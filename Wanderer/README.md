# W.A.N.D.E.R.E.R.
## Very simple build

![Eye of newt and hair of Shelob, now everyone can see your bad wiring job](../img/wanderer.png)

---

> [!IMPORTANT]
> This is a WIP ! It's not yet quite ready to be actually brought into the physical world.  
> *Hic sunt dracones.*

This case is intended for a (relatively) compact build with all the features you'd normally expect in a modern fightstick, except art support. It can have a magnetic bottom plate though !

## Parts list

Must be exactly matched:

- 8x M3S Ruthex heat-set inserts (all for the top side)
- 4x M3S Ruthex heat-set inserts to mount the board
- 1x Neutrik NA-USB
- For the bottom plate, either:
    - 8x 4x5mm cylindrical magnets **and** 8x 3x3mm disc magnets
    - Or 8x additional M3S Ruthex heat-set inserts

Exact match not needed except for dimensions:

- 4x ISO 7380 M3x8 hex socket button head screws
- 8x DIN 7991/ISO 10642 M3x8 hex socket countersunk screws (and 4 more if you aren't using magnets for the bottom plate)
- 2x DIN 912/ISO 4672 M3x35 hex socket head cap screws for the Neutrik
- 2x DIN 934/ISO 4032 M3 hex nuts
- 2x DIN 912/ISO 4672 M3 hex socket head cap screws to mount the board (adapt the length to your standoffs, you need at least 4mm)

It's Whatever (tm):

- 3mm thick material for the sides (acrylic, 3D printed plastic, wood, metal, cardboard, marble, dry ice...)

Tools && auxiliaries:

- Soldering iron
- (Optional but recommended) Medium strength threadlocker, aka blue Loctite(tm)
- M3 standoffs if you wish to route wires under the board/do some actual cable management

## Build guide

Print the two center joints (`centerfront` and `centerbottom`) upside down to minimize support usage.

Print the four corner posts (`post`) and add the magnets at the bottom, checking that they have the same polarity.

Print the bottom pieces, add the magnets while being careful that the polarity matches with those on the posts (in case this needs to be said outright, the posts should all attract the bottom plates).

At this point you have two (not mutually exclusive) choices:

### The Laser Way

Congratulations, you found a couple of nice sheets of 3mm thick material !  
Bring the laser cut files to your favorite shop and laser away. It's kind of that simple.

### The Printer Way

Actually it's mostly the same thing, except you just upload the STL files to your printer and wait the requisite amount of hours. (Specifically: one `left`, one `right`, and four `bridge` for the sides; and both halves of whichever top you pick)

### Moving on

Assemble the frame pieces together, without the corner posts. Slot in your top panels, and then screw the posts in. Optionally, weld the top panel halves together from the inside. Add the heat-set inserts if your top panel material allows it. They will protrude a bit; **this is perfectly normal**.

Add your electronics (I know, this is a vague step, but that's as general as I need it to be)

Snap in your bottom panel (you can also weld it from the inside).

Boom, fightstick !

## TODO:

- HitBox
- WASD

## Acknowledgements

- [Buttercade](https://www.etsy.com/shop/BUTTERCADE) for the Surround and Support project
- [Arcade Shock](https://arcadeshock.com/products/fs-traveler-acrylic-controller-case-choose-type) for the Traveler which largely inspired this project
