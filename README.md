# fake3d 2d_doom_like, based on 'Wolfenstein 3d'

Simple game to implement different alghorithms(raycasting for example).

Features:

  -Simple WASD + mouse/arrows controls  
  -Simple bots pathing(enemies following you and dont stuck)  
  -Simple bots view(enemies attack you only when they see you)  
  -Health regeneration(limited)  
  -Customizing configurations(see below)  
  -NPC's have missing rate and attack range distance  


Installation:  
python version 3.8 or above should already be installed

```
git clone git@github.com:NEkropo1/fake3d-2d-_doom_like.git
python -m venv venv
venv\Scripts\activate (on Linux/mac: source venv/bin/activate)
pip install -r requirements.txt
python main.py
```
Press `Escape` to end the game 

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

![image](https://user-images.githubusercontent.com/107141441/235917159-c8368ed6-ed7f-4e86-8aa9-d8fcd9840e5a.png)
![image](https://user-images.githubusercontent.com/107141441/235917205-b6fc6a62-5802-4d05-876c-33b62ad7ccd6.png)
![image](https://user-images.githubusercontent.com/107141441/235917260-51f969b8-0f2b-463b-aa4c-28de81db1bbb.png)
![image](https://user-images.githubusercontent.com/107141441/235917472-0a59b808-d067-44ef-8187-9fbb1e4e1e88.png)
![image](https://user-images.githubusercontent.com/107141441/235920334-42aac022-7ef1-4917-844a-7818ec81b865.png)
![image](https://user-images.githubusercontent.com/107141441/235920476-84c37594-7224-46a9-815b-b39a81921286.png)
![image](https://user-images.githubusercontent.com/107141441/235920581-f0e78c6c-fc50-446b-a8c4-f39cbafccc7a.png)
