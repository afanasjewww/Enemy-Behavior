# Enemies Asset Pack

This package includes two unique and engaging enemies, the Moss Goon and the Lizard, designed to add excitement and challenge to your game. The enemies come with detailed animations, distinct abilities, and customizable features to enhance player experience.

## Table of Contents
1. [Features](#features)
2. [Installation and Usage](#installation)
3. [Customization](#customization)
4. [License](#license)
5. [Contacts](#contacts)

## Features
- [ ] **Moss Goon:**
  - Jump attack.
  - Resurrection mechanic with scattered goop.

- [ ] **Lizard:**
  - Fire breath attack.
  - Tongue pulling.
  - Tailspin attack.

- [ ] **Navigation:**
  - Precise movement using Unity NavMesh.
  - 2 types of patroling points.
  - Adaptive pursuit behavior with distance consideration that can be changed.

- [ ] **Additional Functionality:**
  - Goop generation upon enemy death.
  - Resource collectibles drop (Health or Stamina).
  - Fire mechanic for Moss Goon.
  - Enemy Health system

## Installation and Usage
Ensure that Unity NavMesh and Unity RP are in your project.
1. Drag and drop the Moss Goon and Lizard prefabs into your game scene.
2. Make sure that your ground has the proper layer, the **NavMesh Surface** component is also added to it and you click **bake** button.
3. Customize enemy properties using the provided scripts and components. All variables are well-named, shouldn't be a problem.
4. Integrate enemy interactions into your game logic, check the IHittable class.
5. Lizzard.cs and MossGoon.cs are the main examples of enemy behaviors and skill usage.
6. Pathfinder.cs contains pathfinding, patroling, and chasing logic.

## Customization
Feel free to customize the enemies to fit the theme and requirements of your game. Adjust parameters, such as enemy health, attack damage, or visual appearance, to align with your game design.

## License
This asset pack is released under the [MIT License](LICENSE). You are free to use, modify, and distribute the assets in your projects.

## Contacts
[Viktors Afanasjevs](https://linktr.ee/afanasjewww) 

