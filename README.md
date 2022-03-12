# artosis-balance-update
implements the starcraft: brood war balance ideas that artosis detailed in https://www.youtube.com/watch?v=_37jDgnkak8

used Firegraft and PyMS to edit the .dat files, package them into an mpq, and turn that into an executable

posting the .dat & .mpq so people can verify this software is safe.

i do not know how to implement artosis' ideas about zerg. i will figure it out some other time.

the list of changes ('I' prefix for implemented, 'N' for not):

---TERRAN---
I turret damage type to normal, +25 to mineral cost
I optical flare research time 75s -> 30s
I optical flare energy cost 75 -> 50
I restoration energy cost 50 -> 25
I ghost damage type from concussive to normal
I ocular implant research time 104s -> 50s
N scv range to 1 (artosis was unsure)
N emp projectile faster (dunno how yet, artosis unsure)

---PROTOSS---

I assimilator -150 shields

I assimilator, nexus, probe -1 vision (implemented -1, did not bring them into line with other buildings, probe is consistent)

I scout -50 minerals, -25 gas

I plasma shields -100 minerals, -100 gas

---ZERG---

N infested terran deal damage upon death (dunno how yet)

N consuming unit brings defiler energy regen 200% (dunno how yet)

N dark swarm reduces ranged damage by 99% or to 1 (dunno how yet)

I defiler -1 armor


N super late game +2 armor zealot upgrade (artosis is dumb sometimes)
