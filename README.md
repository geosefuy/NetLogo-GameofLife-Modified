# [NetLogo] Modified Game of Life

*Developed by: Anjelo Antioquia, Gabriel Minamedez, and Geosef Uy.*

The modified Game of Life model composes of three states for the patches: Alive, Infected, and Dead. Each person in the group created their own rendition of the Game of Life with some base rules, and added their own rules for their own models.

## Run this on your local machine 👨‍💻
1. Download or clone this repository: `git clone https://github.com/geosefuy/NetLogo-GameofLife-Modified.git`.
2. `LifeHacksFinal.nlogo` is the main file. If you have NetLogo installed, you can double click on the file to open and the interface should display.

## Base Rules (Gabriel, Geosef, Anjelo):
1. If 2 to 4 neighbors are infected and cell in normal, then the cell is infected.
2. If 6 or more neighbors are normal and cell is normal, then cell is infected.
3. If odd number of neighbors are infected and cell is infected, then cell is dead.
4. If even number of neighbors are normal and cell is dead, then cell is normal.

## Anjelo's Added Rules:
1. Modified Rule 1: If more than 2 neighbors are infected and cell in normal, then the cell is infected.
2. Modified Rule 3: If 3 of more neighbors are infected and cell is infected, then cell is dead.

## Geosef's Added Rules:
1. If there are no (0) number of neighbors and cell is infected, then cell is dead.
2. Modified Rule 4: If even number of neighbors are normal, neighbors exist (!= 0), and cell is dead, then cell is normal.