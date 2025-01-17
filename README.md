[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MjLLqDcN)
# HW1
## W1L2 In-Class Activity
Objects:
- UI
    - Seeds remaining
        - Starts at 5
        - Decreases by 1 when space is pressed
        - Does not decrease past 0
    - Seeds planted
        - Starts at 0
        - Increases by 1 when space is pressed
        - Does not increase past 5
- Player
    - Bunny sprite
    - WASD to move
    - Moves at a constant speed (no acceleration)
    - No boundary around the world, player can walk off screen
    - Space to plant 1 seed
        - Cannot plant seeds after 5 are placed
        - Is always layered behind seeds
- Seeds
    - Is spawned exactly where the player is when space is pressed
    - No seeds exist in the scene at the start
    - Seeds are able to overlap
        - Recently placed seeds are layered in front of previously placed seeds
- Camera is in a fixed position


## Devlog
Having the notes from the in-class activity helped a lot for this project. Most of the main notes I took like the player moving, pressing space to spawn one seed if the number of seeds left is >0, and the UI elements changing were about the same as Prof. Reid had in class. The main differences I found was that Prof. Reid's answers went into specifics of how the sprite was a visual attribute of the player, separately from the gameplay mechanics of the player. On my answers, I simply put them all under the same section of "player", rather than be more specific in making the visual versus gameplay aspects distinct in my notes.
The break-down activity let me put everything that needed to happen in the code in a more digestible way that was written in my own words, which made it easy to look back on and understand. For me, having the way that the UI should work written down especially helped me put it into code, as it let me approach writing the UI code by making each text of "seeds remaining" and "seeds planted" as individual numbers that go down and up respectively. Additionally, the break-down helped me in having a sort of checklist that is organized by the scripts in the code. I had UI and Player sections in my break-down that had nearly all of the code features that I ended up having to put into each respective script in the code, like having "cannot plant seeds after 5 are placed" translated into an if statement checking if the number of seeds left was greater than 0 in order to let the player plant seeds. I also noticed that I ended checking the Canvas directions less often for this assignment compared to in GDIM 31, I think both because I have more experience so I know more of the basic coding stuff from memory, but also because the break-down activity helped a lot in organizing the code in a way for me specifically to understand. 

## Open-Source Assets
If you added any other outside assets, list them here!
- [Sprout Lands sprite asset pack](https://cupnooble.itch.io/sprout-lands-asset-pack) - character and item sprites
  
## Prof comments
Please consider formatting your break-down activities with the hyphen '-' symbol as suggested above, and reomve the prompts. This will make it a lot easier for me to read. See the [README formatting guide here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax). Also, I'm really glad that this exercise helped you understand how to code the assignment! I think you will find the breakdown for HW2 helpful too; I look forward to reading your feedback on it.
