Amazing chessboard project
==================================================

## Our project goals/objectives
- chessboard which can recognize the position and movement of the pieces
- can be used with lichess api [Lichess API](https://python-lichess.readthedocs.io/en/latest/)
- running [Stockfish](https://github.com/official-stockfish/Stockfish) natively
- visualization of the current game analysis by Stockfish in bar placed side of the chessboard
- visualization of particular good/bad moves with Led's under the chessboard
- recommendation of move done by Stockfish
- cool animations easy to write




## Hardware question/disscusions


#### Main PC
- What kind of PC? (raspberry? old Laptop?)
- What power supply?


#### PCB
- how many PCB's? A PCB for every field? One PCB for 4 fields
- which technology should be utilized for detecting the pieces?
- How to do the connection between PCB's? soldering? connectors?
- Which micro controller to use?

#### Chess board mechanical assembly
- how big should the board be?
- which material should cover the board
- how to place the reed switches under the board
- how to avoid elimination of adjacent fields


#### Chess pieces
- Which material?
- how to place the magnets inside?
- how strong the magnets should be?


## Software question/disscusions

#### High level Code
- How the communication between the PC and IC should be done?
- Which operating system?



#### Embedded Code
- C / C++ / circuit python?
- multiplexing of the reed switches?
- How to control the LED chips?
- How to control the LED strip?

## Build of material
- [Reed switch 1](https://www.mouser.de/ProductDetail/MEDER-electronic-Standex/MK17-B-3?qs=k5V78Jg%2Feq4ak%2FF9BjmKdg%3D%3D)
- [Reed switch 2](https://www.aliexpress.com/item/32424362231.html)
- [Fabric black](https://www.ebay.de/itm/263420772903?hash=item3d551a0227:g:0zsAAOSwwm5h8mHo)
- [Fabric white](https://www.ebay.de/itm/263420772903?hash=item3d551a0227:g:0zsAAOSwwm5h8mHo)
- [plexiglas](https://www.ebay.de/itm/264805134763)
- [Magnets](https://www.ebay.de/itm/402944351188?hash=item5dd15adbd4:g:JsgAAOSwavRieRuh&amdata=enc%3AAQAHAAAA4JxYri5%2FUTQ0i%2BnelTa7UxFwl040JJQbRucmGHdeM5z0cEHLZrc2b5sx7ulcMvtQ6ZxjOhFKN8u5hsBcx%2FeLEXwOXI3FoOdRMIoousUeex4ajh7ZpRSQhkUnDRyAG6nY5Ski3hwvlcRa%2BSKqGZu0lwv3XE1ZeHcH8rWYASRNbUlZz3QfFazRHag7J2sOXllKWcnzi6ou%2FEqsHKbPVnlZAcbUnJEMuslGEgJBgP0Fxf0zsywxECPuq3lbUzyYRDtkc0%2F3Nanh0LgWrAWU16eQ3IbTKtNq%2F%2FwMLt5%2FouNVTDhZ%7Ctkp%3ABFBMutT6grpg)
- [RGB smd LED ](https://www.ebay.de/itm/253340723896), [Datasheet](https://cdn-shop.adafruit.com/datasheets/WS2812B.pdf)
- [LED stripe](https://www.aliexpress.com/item/1005002636898685.html)
