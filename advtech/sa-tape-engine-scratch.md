---
layout: page
title: "The Scott Adams Cassette Tape Based Text Adventure Engine"
---

# Introduction
I've been fascinated by text adventures since I was a youngster in the 80s. Or, more correctly, by text adventure *engines*.

This is the history of Scott Adams' text adventure engine, and of its descendants and derivatives. 


# The Colossal Cave

PDP 10 around 300 kbytes of memory

database

ligth and darkness, special object

all would be games for nerds with access to mainframes connected to the proto-internet if it were not for the home computer revolution.

# The home computer revolution 

1977 triad Commodore PET, Apple II, TRS 80 Model I
then vic 20 5 kb RAM, commodore 64

ibm pc 1981 16kb ram, no disk, basic in rom

zx 80, zx 81, zx spectrum 48 kb (7 kb video RAM, so 41 kb), amstrad CPC 464, CPC 6128 1985

1980 16 kb tape, disk in US

1982 48-64 kb tape, disk in US

1985 128 kb tape, us 512 kb disk

disk in US but very expensive, about the same price as the computer
no disk in europe, microdrive failure, until CPC 6128 1985, spectrum +3 1987

16 bit systems from 1985 disk based atari st 512kb, amiga 1000 256 kb 1985, amiga 500 1987 512 kb 
512 kb standard

# Scott Adams

small memory, tape, many different systems -> engine

1978 adventureland in basic

In 1979 (SA) publishes in Creative Computing "An Adventure in Small Computer Game Simulation"
 game engine + game database + game editor
 2 word verb noun parser
 rooms table (description)
 directions table (map)
 objects table (description) + associated word
 objects position table <- only table that is modified
 messages table
 vocabulary table verbs and nouns, synonyms, some are fixed like get drop, n, s, e, w, .
 auto commands table, verb auto, noun %, at the beginning of the command table
 player commands table, "any" accepts any noun, up to 5 conditions like a rule in prolog or an expert system 
 auto get drop feature

 15 flags for user, dark flag, light counter, special light object


Scott Adams, "An Adventure in Small Computer Game Simulation", Creative Computing Magazine, Vol. 5, Num. 8 (August 1979).

1979 SA ... simulation in creative computing

1980 jul SA pub adventureland in softside
1980 dec SA pub pirate adventure in byte
1981 jan captain 80 book contains adventureland

1980 jan allan molluf bruce hanson pass among buddies an spec
1981 dec molluf and hanson publish the adventure system

# Infocom

zork

infocom

zil compile to z-machine, disk based systems

# In the UK

1980 aug ken reed practical computing
1981 jun artic computing
1981 jul trevor toms zx81 book refs ken reed

1982 mysterious adventure howarth byte magazine wikipedia

graeme yeandle looks at those things

# The UK Text Adventure engines

The Quill + The Illustrator
grame yeandle refs ken reed

The GAC 
sean refs trevor toms that refs ken reed

The PAW

The DAAD spain

# Others

level 9 1979 a-code complete adventure + 70 locations endgame in zx spectrum 48 kb

melbourne house the hobbit

magnetic scrolls 16 bits like infocom mainframe dev env, disk.

# The End

1986 ai goes bankrupt

even infocom 

hobbyist inform zmachine

# timeline

## The Casette Game Engines

* 1976
    * Will Crowther releases the Colossal Cave Adventure on the PDP-10, the first text adventure, written in Fortran.
* 1977
    * Don Woods releases his extended version of the Colossal Cave Adventure text adventure on the PDP-10.
* 1978
    * Scott Adams writes Adventureland and its engine in Basic (later rewritten in machine code).
* 1979
    * Scott Adams publishes An Adventure In Small Computer Game Simulation about the internals of his text adventure game engine. Adams, S. Creative Computing, pages 90 to 97, August, 1979.
    * Pete and Mike Austin Level 9 write A-Code
* 1980
    * Jan. Allan Moluf and Bruce Hanson publish, among buddies, an specification of the Scott Adams database format. https://www.filfre.net/2013/07/the-quill/
    * Jul. Scott Adams publishes Adventureland, the data and interpreter for his game. Adams, Scott (July 1980). "Adventureland". SoftSide. p. 36.
    * Aug. Ken Reed publishes Adventure II - an epic game for non-disc systems, an analysis an specification for a Scott Adams style text adventure engine. Reed, K., 1980: Adventure II - an epic game for non-disc systems. Practical Computing, August 68-75
    * Dec. Scott Adams publishes pirate adventure in Byte
* 1981
    * Jun. Richard Turner and Chris Thornton, found Artic Computing and publish Planet of Death, REFERENCE Ken Reed article.
    * Jul. Trevor Toms publishes The ZX81 Pocket Book with a chapter "ZX81 Adventure" that contains a BASIC text adventure writing system. REFERENCES Ken Reed, Practical Computing, Vol 3 Issue 8 Aug 1980
    * Dec. Allan Moluf and Bruce Hanson release The Adventure System, a text adventure writing system that uses Scott Adams database format
* 1983
    * Dec. Gilsoft releases The Quill text adventure writing system for the ZX Spectrum, later ported to many other home computers. REFERENCE Graeme Yeandle was inspired by Ken Reed's article and rev. eng. Artic Computing. 
    * Level 9 publishes Colossal
* 1985
    * Incentive releases its GAC text adventure writing system for the Amstrad CPC. Author Sean Ellis https://prism.ucalgary.ca/handle/1880/51523 REFERENCES Trevor Toms Zx81 pocket book.
* 1986 Gilsoft releases PAWS

# comparative

SA TAS QUILL GAC PAW