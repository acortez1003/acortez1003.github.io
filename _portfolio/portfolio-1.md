---
title: "Ascend: Path of No Return"
excerpt: "Metroidvania created in Godot, written in GDScript (Group Project)<br/><img src='/images/ascend.PNG'>"
collection: portfolio
---

Over the course of a semester, my team and I developed a 2D Metroidvania in Godot using GDScript. My primary contributions focused on **level design, interactive environments, managing dialogue, and story progression.**

## Level Design

I designed and implemented the templates for all three in-game maps, utilizing Godot's TileMap to construct tile-based environments. I used parallax backgrounds to create dynamic effects and configured collision layers to ensure accurate player interaction.

![Level design](/images/level_design.png)

## Interactive Environments

I developed a resuable Interact Area node that can be applied to any item using the `interact()` function, which allows child nodes to override and define specific behavior. The system uses collision detection to trigger an indicator (`[E]`) when the player enters the designated Interact Area. Upon pressing the interact button, the `interact()` function is called, executing the specific action for that object.

![Interact area](/images/interact_area.png)

## Dialogue Management and Story Progression

I also implemented dialogue management by integrating the [DialogueManager](https://github.com/nathanhoad/godot_dialogue_manager) plugin created by Nathan Hoad. Most interactions triggered by the `interact()` function are linked to the DialogueManageer, which I configured to handle context-specific dialogue flows and events. These interactions were crucial in story progression, which is where I created side-quests where the player would have to complete a certain task in order to proceed.

![Dialogue manager](/images/dialogue_manager.PNG)

Additionally, I setup the transition logic by creating door nodes that allowed players to transition between scenes. Using exported variables, I set up each door to point to specific target scenes. In the image below, our "Door_3" points to "Door_4" and transitions to "Area_3" and will point the player left upon spawn.

![Door](/images/door.PNG)
