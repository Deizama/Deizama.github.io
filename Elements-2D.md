## Elements 2D

![Level Generator](http://image.noelshack.com/fichiers/2021/36/7/1631459177-webp-net-gifmaker.gif)

This project was (and is still) done alone on a personnal project.
This is an ongoing Roguelike Topdown RPG in 2D, with generated level.

For now, there is the graphical aspect and the level generator (and the basic mechanics).
The level generator is composed of rooms (selected randomly in a pool and depending of the level type) :

- The starting room where the character spawn. There is no danger in this room.
- Common rooms where you can encounter simple threat. They are the most common.
- Rare rooms are generated at a ratio of 1:8 common room. There is the bigger prizes but different threats.
- Challenge rooms are on the ends of the level and cannot be near another challenge room or a boss room.
- Boss rooms are unique and placed on any end of the level. If the player kill the boss, he can go to the next level.

The level generator has a lot of moduling aspect, like the width of the level, the height, the rarity of rare rooms, the number of challenger rooms...

**Unity** with C# was used. 

### Project links : 

None.