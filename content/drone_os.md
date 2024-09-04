+++
title = "DroneOS Part 1"
date = 2024-08-30

[taxonomies]
tags = ["DroneOS", "Game Dev", "Projects"]
+++

DroneOS is a video game I've been envisioning for some time now. My plan for it is to create a functioning two-dimensional video game with a top-down perspective. This document will outline the plans and game-design goals for me to call the project finished, with further posts illustrating the work that has been completed.

<!-- more -->

DroneOS will feature players battling in a field of asteroids, using remote piloted drones to mine resources, fight other players and NPC drones, and destroy the enemy drone carrier to win the game. The game will have a focus on diegetic UI elements, with a particular element being the command line which is used to control individual components of the drone. The game will have full Newtonian physics, with players using thrusters on their ships to speed up and slow down, and the speed will be conserved until the thrusters are used or they impact another object.

# Game Objective

To start with, it's important to detail out the objective for the players. 



Players will start in a drone carrier, which is the immovable "base" for the players to spawn at. If their carrier is lost then the game is over, and that team loses.



You can lose a carrier through two different methods; physical destruction and hacking. Hacking will be explained in a future section of this document, as I plan for it to contain unique mechanics not seen in other games.

# Gameplay Loop

The players will start the game in a randomly generated asteroid field, where the asteroids are static objects and contain random minerals. These minerals are gathered by non-player-character (NPC) drones and returned to the carrier, where they are stockpiled and allowed to be spent on better weapons and parts for the players. 



Players control drones of different classes, with configurable parts and weapons. These drones are used to map out the environment around them, find the enemy, and ultimately destroy the enemy carrier. 



Players can also engage in electronic warfare, using a variety of jammers, decoys, and other devices to confuse, redirect, and attack the opposing team. 

# Theme

The theme of the game is that two mining companies in a future like the *Alien* franchise are fighting over mineral deposits in space. 



Technology is retro-futuristic which results in the monochromatic and text-focused user interface. Although technology like faster-than-light travel and artificial intelligence has been achieved.



I would like to eventually have two separate factions for each team, but for initial development there will only be one faction for both teams.

# Plan

The plan is to create a prototype by the end of October, where a playable game of DroneOS is possible. The initial goal will be to have flyable drones, randomly generated maps, and the user interface completed. AI Drones, the second faction and hacking will come as future updates to the game, assuming that this first part is successful. 
