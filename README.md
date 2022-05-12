# Dungeon-Builder
Dungeon-Crawler Unity Game where each dungeon is automatically generated! 


For this project I will be using the dungeon architect Asset from the asset-store as well as different low poly graphics (Most of them created by Synty). 

The Dungeon Architect itself will simply be creating the dungeon with different items randomly generated. 

The enemies as well as the playable character will be spawned in the scene on runtime.

Every Dungeon must have a start and an end. Speaking of the 'end' it will basically be a portal which leads to a new dungeon.

A challenge in doing all this will be that the AI enemies will need a newly generated navmesh every time a new dungeon is generated. For that reason I have created some scripts which also automatically Bake the terrain on runtime. 
