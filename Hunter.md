# Hunter Macros

##### Pet Control
```
/petattack

/petpassive
```

##### Feign & trap
```
#showtooltip
/petpassive
/cast [combat] Feign Death
/cast Freezing Trap
```

##### Lazy engage
```
/cast Hunter's Mark
/petattack
/cast !Auto Shot
```

##### Lazy farm
```
/cleartarget
/targetenemy [noharm]
/petattack
/cast !Auto Shot
/castsequence reset=8 Hunter's Mark, Serpent Sting, Arcane Shot, Multi-Shot
```

##### Revive & Feed Pet
```
#showtooltip
/cast [@pet,nodead] Feed Pet; Revive Pet;
/use [@pet,nodead] Wild Hog Shank
```

##### Call & Heal Pet
```
#showtooltip
/cast [nopet] Call Pet; Mend Pet
```

##### Auto Shot
```
#showtooltip
/stopcast
/cast !Auto Shot
```

##### DPS Burst
```
/cast Berserking(Racial)
/cast Rapid Fire
```

##### Trap out of combat, Melee in combat
```
#showtooltip
/cast Immolation Trap
/cast Mongoose Bite
/cast Raptor Strike
```

##### Clickable Track Spells
```
#showtooltip
/cast [mod:shift] Track Beasts
/cast [mod:ctrl] Track Hidden
/cast [mod:alt] Track Undead
/cast Track Humanoids
```

##### Clickable Beast Spells
```
#showtooltip
/cast [mod:shift] Eagle Eye
/cast [mod:ctrl] Eyes of the Beast
/cast [mod:alt] Beast Lore
/cast Dismiss Pet
```
