TINT8
=====
A PDP-8 version of the popular tile-matching puzzle 
video game originally designed and programmed by 
Alexey Pajitnov. This version is very much inspired 
by the original made for the Electronika 60.

Current State
-------------
TINT is certainly playable but I would not call it 
finished. There is no use of a real time clock so the 
speed of the game is governed by a delay loop which 
might be need to be adjusted for your machine.

There is definitely need for polish in several areas. 
Patches are more than welcome and there is a TODO 
list in the code.

Features
--------
TINT8 does not implement all features typically found
in this type of game. Some features are planned and
some intentionally left out:

| Feature | Support |
|---|---|
| Sky Line | :heavy_check_mark: |
| Bag of Seven Randomization | :heavy_check_mark: |
| Soft Drop | :heavy_check_mark: |
| Hard Drop | :heavy_check_mark: |
| Wall Kicks |  Planned |
| Goals and Level Progression | Planned |
| Scoring | Planned |
| Next Queue | Planned |
| Hold Queue | :x: |
| Buffer Zone | :x: |
| Ghost Piece | :x: |
| Lock Down Timer | :x: |
| Back-to-Back Bonus | :x: |
| T-Spins | :x: |

(This is table is not exhaustive)

Building 
-------- 
I have buildt tint.pal with palbart 
version 2.11. Palbart should be compatible with PAL8 
but I have not tried it.
