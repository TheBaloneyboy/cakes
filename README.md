# .cakes
Simple patches for CakesFW, only for O3DS unless someone decides to help me out or buy me a n3DS :P

# How to compile
Run 'armips patch.s' and 'patissier.py recipe.yaml patch.cake'.
Of course, replace 'patch.cake' with your desired name.

# Current patches
UNITINFO patch, which well... patches [UNITINFO](https://3dbrew.org/wiki/Configuration_Memory#UNITINFO)? I guess? Taken from [AuReiNAND and Steveice10](https://github.com/AuroraWright/AuReiNand/blob/master/source/patches.c#L72).

AGB_FIRM signature patch, allows you to run unsigned GBA CIAs, ya dirty pirate. Taken from [here](https://gist.github.com/Steveice10/8a6965c59192ac970832)
