# Night-Shift (name subject to change)

## Repository
https://github.com/Erodplayer/night-shift.git

## Description
A FNAF-style survival game made with python's pygame where the player watches security cameras managing a limited power to survive until the time reaches 6:00 AM while creatures roam the building.

## Features
- Security camera system
	- Each camera location being a stored image of a room, clicking a specific button switches the current image drawn using pygame image loading & mouse events
- Roaming creatures
	- Using an Enemy class, they'll move between rooms on a timer, with a dictionary mapping each room to the room it connects to and at random picks the next movement
- Room doors an lights
	- Toggleable doors and lights with the mouse, each being true/false variables that changes the draw image and how fast the power is draining
- Power Meter
	- Finite resource value that drops over time, drains faster when more of the doors, lights, and cameras are in active use, game over if power reaches 0
- Night timer, win/lose
	- Timer going from 12-6 AM, game state variable switiching between title playing, win and, game over screens
- Sounds and Atmosphere
	- Ambient sound, door sounds, potentially with pygame mixer, and if time allows it drawn backgrounds and characters by me
 
## Challenges
- Learning how to manage game states, title, playing, game over, in pygame
- Learning how to organize a larger program into multiple classes and files for pygame
- Learning how to assemble the code for enemy movement into rooms, and map dictionary

## Outcomes
Ideal Outcome:
- A polished one night game with 3 (or more) enemies that behave differently, with drawn assets, 9 cameras, and a title

Minimal Viable Outcome:
- One night game with 2 enemies, 7 cameras, working doors, power meter, and win/lose screen, using stock/placeholder images

## Milestones

- Week 1
  1. Create GitHub repo, set up pygame window, draw office, and camera screens with placeholders
  2. Switchable cameras with mouse clicks

- Week 2
  1. Make enemy class with the room movement using dictionary and random
  2. Create Door toggle, power meter, night timer

- Week 3
  1. Win loss screens, title screen (hopefully)
  2. Sound effects and replace placeholder art with my own art
 
- Week 4 (Final)
  1. Playtest, fix bugs, balance gameplay difficulty
  2. Write the README, record demo, submit
  3. If there's extra time add additional night(s)
