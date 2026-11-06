# BLUE HORIZON

An early 3D ocean-survival game prototype. The current build is a small first-person test featuring an animated ocean and one floating piece of driftwood.

## Download

1. Open the [BLUE HORIZON repository](https://github.com/hexagonalslantpizza/BLUE-HORIZON).
2. Click the green **Code** button.
3. Select **Download ZIP**.
4. Extract the ZIP file somewhere on your computer.

## Run the game locally

The easiest way to run the prototype is with **Visual Studio Code** and the **Live Server** extension.

1. Install [Visual Studio Code](https://code.visualstudio.com/) if you do not already have it.
2. Open VS Code and choose **File → Open Folder**.
3. Select the extracted `BLUE-HORIZON` project folder.
4. Install the **Live Server** extension from the VS Code Extensions panel.
5. In the Explorer panel, right-click `index.html`.
6. Choose **Open with Live Server**. Your browser should open the prototype.

> You need an internet connection when running the prototype because it currently loads the Three.js library from a CDN.

## Controls

| Input | Action |
| --- | --- |
| W A S D | Move on driftwood / swim |
| Mouse | Look around |
| Space | Rise while held underwater / jump at the surface (tap) |
| Left or Right Ctrl | Dive downward (hold) |
| E | Climb onto the driftwood when close to it |
| ESC | Release the mouse cursor |

Click **ENTER OCEAN** to begin and capture the mouse.

## Current prototype

- Animated ocean surface with small waves
- A floating piece of driftwood that tilts with the waves
- Basic first-person camera and movement
- Swimming with momentum and water resistance
- Neutral buoyancy underwater when no vertical input is held
- Held Space to swim upward while underwater
- A small one-press jump at the surface
- Gentle driftwood movement while the player stays supported on board
- Diving underwater and swimming back toward the surface
- Underwater color and fog effect
- Climbing back onto the driftwood when close to it

This is an early prototype. Multiplayer, saving, crafting, resource gathering, and the larger survival systems are not implemented yet.

## Project status

BLUE HORIZON is being developed one system at a time. Features will be added and tested as the prototype grows.
