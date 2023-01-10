A resource that allows for easy biome detection in Minecraft using predicates.
The goal of this project was to not only make a list of predicates for each individual biome, but also allows for multiple combinations of biomes.

For example, if you wanted the deep_cold_ocean biome, you could get it by just going through `biomes:list/deep_cold_ocean`, but you could also find it by going through `biomes:ocean/deep_ocean/deep_cold_ocean` or `biomes:ocean/cold_ocean/deep_cold_ocean`!
Not only that, if you don't specify whether the cold ocean is deep or shallow, it will check both! `biomes:ocean` will just check to see if you are in an ocean. Doesn't matter if it is warm or frozen, deep or shallow.

additionally, the folder `biomes:list/` literally has a list of every individual biome.

If you have any suggestions for custom folders that this could benefit from DM me on discord at `Jack the GEAT#6949`