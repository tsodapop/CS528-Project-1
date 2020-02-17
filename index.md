# Project: UIC SEO Grove

[Project available on Github](https://github.com/tsodapop/CS528-Project-1)

This project is an interpretation of what the UIC SEO Grove can be utilized for. In this instance, the grove has been turned into a public space that promotes free play. The emphasis of the grove is a food-court style area, where people are able to order myriad food and drinks. Additionally, there is music and video games for entertainment. 

## How to Install and Set Up

The project is run on Unity with emphasis on VR. The project can be run inside the CAVE2, located at UIC, or on the VIVE. The files needed to run this project are available above. The folder containing all of the files is named "Chicago-UIC." Additionally, the version of Unity will need to be 2019.2.11f1. [Visit Unity's webpage to look for older versions](https://unity3d.com/get-unity/download/archive).

- CAVE2: To run on the CAVE2, follow the directions provided by the wiki page on [uic-evl's github page on how to run in CAVE2](https://github.com/uic-evl/omicron-unity/wiki/Guide-for-running-Unity-in-CAVE2#building-on-cave2). 

- VIVE: To run on the VIVE, make sure that your VIVE is properly connected and set up. Open the project in Unity. Under Omicron in the top bar, click "Configure for Vive." After it is done updating, you can click the Play button and it should now be visible inside the VIVE. 
![Configure for vive](https://raw.githubusercontent.com/tsodapop/CS528-Project-1/master/Conf_for_vive.png)

## How to Use

Inside Unity, execute the .exe file if you are running in the CAVE2, or click Play if you are running in the VIVE. The following is a list of things that you are able to do:
- Open the menu to interact differently with the scene. 
  - If you go into System > and click Walk, you can freely walk around the grove instead of flying around.
  - If you go into Time of Day > and click Night or Day, you can manipulate the scene to be bright or dark with different effects.
  - If you go into Teleport > and click on any of the buttons, you can instantly teleport to that object.
- Approach different NPC (non-player character) objects
  - If you approach the benches, you will hear the NPCs chatter. This effect changes with night.
  - If you approach the stalls, you can hover over the NPCs at the stall for a sound effect. This effect changes with night.
  - If you approach the stalls, you can hear the NPCs waiting in line chatter. This applies to both lines.
  - If you click on the person right in front of the Default position, they will jump and make a sound.
  - If you approach the stalls, you can click on each purple register for a sound effect. Each will make a different sound.
  - If you grab the money, you will hear a sound effect. 
  - If you click on the jukebox, you will start playing music. This can be paused. This effect changes with night.
  - If you click on the game controllers near the main lamp, you can grab these objects.
  - If you click on the game image in front of the CRT near the main lamp, you will start playing music. This can be paused. 
  - As you walk around, certain other NPCs will walk through the grove.
  - The default soundtrack at Default location will change as you change from day to night.

## Models and Data

### The following items were generated through Blender:
![Ice Cubes, Drinks, Cooler](https://raw.githubusercontent.com/tsodapop/CS528-Project-1/master/cooler_drinks_ice_cubes.png)
```
Items:
  Cooler
  Drinks (Differing colors in scene)
  Ice Cubes
```
![Backpack](https://raw.githubusercontent.com/tsodapop/CS528-Project-1/master/backpack.png)
```
Items:
  Backpack
```  
![Controller](https://raw.githubusercontent.com/tsodapop/CS528-Project-1/master/controller.png)
```
Items:
  Controller (Differing colors in scene)
```
![CRT](https://raw.githubusercontent.com/tsodapop/CS528-Project-1/master/crt.png)
```
Items:
  CRT
  Image of Super Smash Brothers Melee (Image taken from source below and adapted into a solid plane)
```  
![Lamp](https://raw.githubusercontent.com/tsodapop/CS528-Project-1/master/lamp.png)
```
Items:
  Lamp  
```
![Main Lamp](https://raw.githubusercontent.com/tsodapop/CS528-Project-1/master/main_lamp.png)
```
Items:
  Main Lamp
```
![Money](https://raw.githubusercontent.com/tsodapop/CS528-Project-1/master/money%20indicator.png)
```
Items:
  Money indicator
  Money
```
![Stall](https://raw.githubusercontent.com/tsodapop/CS528-Project-1/master/stall.png)
```
Items:
  Stall
  Cash Register
```
### The following items were obtained online:
- [UIC Grove](http://www.evl.uic.edu/aej/528/Chicago-UIC.zip)
  - Uses:
    - The given base code was provided for interaction with Unity and the CAVE2. 
- [Chicken Piece](https://assetstore.unity.com/packages/3d/props/food/chicken-piece-free-160801) 
  - Uses: 
    - The Chicken Piece was used at the benches to show food consumption. 
    - The Chicken Piece was used above a stall to promote that stall sells the product.
- [Sushi](https://assetstore.unity.com/packages/3d/props/food/japanese-food-sushi-free-158209)
  - Uses:
    - The Sushi was used at the benches to show food consumption.
    - The Sushi was used above a stall to promote that stall sells the product.
    - The Sushi plate was used at the benches for plating purposes.    
- [Coffee Shop](https://assetstore.unity.com/packages/3d/props/coffeeshop-starter-pack-160914)
  - Uses:
    - The Coffee Shop drink was used at the benches to show drink consumption.
    - The Coffee Shop dessert was used at the benches to show food consumption.
- [Pizza](https://assetstore.unity.com/packages/3d/props/food/pbr-pizza-108425)
  - Uses:
    - The Pizza was used at the benches to show food consumption.
    - The Pizza was used above to a stall to promote that stall sells the product. 
- [Jukebox](https://assetstore.unity.com/packages/3d/props/electronics/jukebox-music-player-152930)
  - Uses:
    - The Jukebox was placed near the main lamp to play music.
- [NPC Still](https://assetstore.unity.com/packages/3d/characters/humanoids/npc-character-proto-series-132051)
  - Uses:
    - The NPC Still was placed at the benches to show communication and food consumption. Sound was added that alters in the night scene.
    - The NPC Still was placed near the stalls to create a line for purchasing food. Sound was added.
- [NPC Animate](https://assetstore.unity.com/packages/3d/characters/humanoids/character-pack-free-sample-79870)
  - Uses: 
    - The NPC Animate was placed in front of the Default camera position. This NPC is clickable for sound and jump effect.
    - The NPC Animate was placed in front of each of the stalls with a wave effect. Hovering over each NPC elicits a sound that alters in the night scene.
    - The NPC Animate near the stalls to create a line for purchasing food. Sound was added. 
    - The NPC Animate was placed throughout the grove to promote multiple people walking around. These NPCs will move whenever the player moves. 
    - The NPC Animate was placed in front of the cooler with a pickup effect. 
- [Smash Melee Image](https://en.wikipedia.org/wiki/Super_Smash_Bros._Melee#/media/File:SpecialMelee.jpg)
  - Uses:
    - The Smash Melee Image was appended to the CRT as a plane in Blender to show that is the game that is being played.
- [Crowd Talking](https://www.youtube.com/watch?v=mLld3JVwxew)]
  - Uses:
    - Placed onto NPC to facilitate conversation at benches
- [CS is a lot](https://www.youtube.com/watch?v=NlI360Y9wLA)
  - Uses:
    - Placed onto jukebox 
- [Closing time](https://www.youtube.com/watch?v=zmtOY4Hz6Ks)
  - Uses:
    - Placed onto jukebox
- [I'm hungry](https://www.youtube.com/watch?v=nHeTfagADnc)
  - Uses:
    - Placed onto NPC to facilitate conversation at stalls
- [Kids talking about food](https://www.youtube.com/watch?v=_T0ZiqRdU8Y)
  - Uses:
    - Placed onto NPC to facilitate conversation at stalls
- [Retro Game Sounds](https://assetstore.unity.com/packages/audio/sound-fx/sound-fx-retro-pack-121743)
  - Uses:
    - Added to NPCs where appropriate. Example: Coin sounds added when clicking on Cash Registers
- [Kaching](https://www.youtube.com/watch?v=4kVTqUxJYBA)
  - Uses:
    - Placed onto money when grabbed
- [Action RPG Game Sounds](https://assetstore.unity.com/packages/audio/music/action-rpg-music-free-85434)
  - Uses:
    - Placed as ambient sounds

## Contrast Between CAVE2, VIVE, and Reality

Testest
