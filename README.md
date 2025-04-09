# BumpX

BumpX takes normalmap + optional gloss and height maps and outputs bump and bump# textures for Stalker and Metro 2033 build 375 games

Also can do the opposite - take bump + bump# textures from Stalker/Metro 2033 build 375  and output heightmap + glossmap + normalmap as TGA images

# UPDATE

No longer throws an error if bumps are of different size.
Output height and gloss maps as PNG instead of TGA. For some reason Unreal 5 didn't like those TGA formats yet normal maps functioned as expected. Dirty fix I guess but it works.
