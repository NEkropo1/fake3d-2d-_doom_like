# fake3d-2d-_doom_like

Trying to make game same as in repo name, to understand if I can implement different alghs(raycasting for example)

In SETTINGS you can type your RESOLUTION, for example, as for me it's same as in file:
RES = WIDTH, HEIGHT = 1920, 1080

If u want to change count of enemies:
in object_handler(lane 19): # spawn npc
                            self.enemies = 20  # npc count

If u wanna see, how it looks before render, uncomment in main.py map and player 2d draw(lanes 52-53) 
As for enemies - lane 31 in npc.py (self.draw_ray_cast())

Feel free to edit map in map.py

Controls - wasd + mouse/arrows(if u don't wanna use mouse).
left shift + f, for unstoppable fire(testing purpose)

HUGE MENTION : most coding from https://github.com/StanislavPetrovV/DOOM-style-Game
