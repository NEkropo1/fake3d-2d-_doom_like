# fake3d 2d_doom_like, based on 'Wolfenstein 3d'

Simple game to implement different alghorithms(raycasting for example).

Features:
  -Simple WASD + mouse/arrows controls
  -Simple bots pathing(enemies following you and dont stuck)
  -Simple bots view(enemies attack you only when they see you)
  -Customizing configurations(see below)

Installation:
python version 3.8 or above should already be installed

```
git clone git@github.com:NEkropo1/fake3d-2d-_doom_like.git
python -m venv venv
venv\Scripts\activate (on Linux/mac: source venv/bin/activate)
pip install -r requirements.txt
python main.py
```


In SETTINGS you can throw your RESOLUTION, for example, as for me it's same as this:
RES = WIDTH, HEIGHT = 1920, 1080
By default it's fullscreen

If you want to change count of enemies:
in object_handler(lane 19): # spawn npc
                            self.enemies = 20  # npc count

If you want to see, how it looks before render, uncomment in main.py map and player 2d draw(lanes 52-53) 
To see enemies - lane 31 in npc.py (self.draw_ray_cast())

Feel free to edit map in map.py

left shift + f, for unstoppable fire(testing purpose)
