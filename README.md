# Nine – a game engine
![Screenshot](http://jason.henault.me/cv/img/nine_demo.png)

 Nine is a personnal project done on many years, during holidays. It's the begining of a game engine that I've started to improve my C++ skills and understood some aspects of video games.
Used libraries :

- SFML : Allow to manage display, sound, events and threads
- Newton Dynamics : A physics engine
- LUA : Nearly all the game works thanks to LUA scripts, allowing to modify a level, a tool, an object or a material, directly in a script file

It's from this basic libraries I've started the engine. Currently, it allows to :

- display a level with lights, events, spatialized sounds and shaders
- move a caracter at first person view with the ability to interact with the world (by raycasting)

Particular emphasis has been placed on resources management. All loaded items are follow in memory and a report of the game run is provided in an HTML page, update on the fly. 
