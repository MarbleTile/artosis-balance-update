# artosis-balance-update
implements the starcraft: brood war balance ideas that artosis detailed in https://www.youtube.com/watch?v=_37jDgnkak8

most agree that the tosis is an idiot but i implemented his ideas anyways...

used Firegraft and PyMS to edit the .dat files, package them into an mpq, and turn that into an executable. posted the .dat & .mpq so people can verify this software is safe. i do not know how to implement artosis' ideas about zerg. i will figure it out some other time.

### online guide by the illustrious pr0nogo: http://pr0nogo.wikidot.com/sc-play

## Requirements:
### for exe
* Starcraft: Brood War v1.16.1 (https://archive.org/details/starcraft-broodwar-1.16.1)
### for building exe from mpq
* Firegraft (https://mega.nz/#F!u4A1gaDa!CheCYfZVxtp64VKHHKYPcw) -- not a virus, although triggers windows defender
### for building mpq from dat
* PyDAT from PyMS (https://github.com/poiuyqwert/PyMS)
* Python 2.7
* pillow xor pil (python imaging libraries)

### changelog legend: 'I' prefix for implemented, 'N' for not

## TERRAN
* I turret damage type to normal, +25 to mineral cost
* I optical flare research time 75s -> 30s
* I optical flare energy cost 75 -> 50
* I restoration energy cost 50 -> 25
* I ghost damage type from concussive to normal
* I ocular implant research time 104s -> 50s
* N scv range to 1 (artosis was unsure)
* N emp projectile faster (dunno how yet, artosis unsure)

## PROTOSS
* I assimilator -150 shields
* I assimilator, nexus, probe -1 vision (implemented -1, did not bring them into line with other buildings, probe is consistent)
* I scout -50 minerals, -25 gas
* I plasma shields -100 minerals, -100 gas

## ZERG
* N infested terran deal damage upon death (dunno how yet)
* N consuming unit brings defiler energy regen 200% (dunno how yet)
* N dark swarm reduces ranged damage by 99% or to 1 (dunno how yet)
* I defiler -1 armor

## ETC
* N super late game +2 armor zealot upgrade (artosis is dumb sometimes)

### credits:
* everyone in this thread: http://www.staredit.net/topic/17400/#1
* Pr0nogo's tutorials https://www.youtube.com/c/Pr0nogo and website http://pr0nogo.wikidot.com
* poiuyqwert for creating PyMS
* DiscipleofAdun for creating Firegraft
