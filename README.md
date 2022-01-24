# Back_to_Hell
![title]

### Concept

***Back to Hell*** is a school project produced during one month in a team of 10 students. The objective was to create a 2D mobile game.
The game is a 2D platformer endless runner, it is played alone on mobile (only Android) in horizontal position with the thumbs.

### Rules

As the world scrolls faster and faster, the running player have to dodge the ground holes and the enemies or kill them. The goal is to reach the farthest distance as a best score.
There are three types of enemies : an archer lizard shooting arrow that create mud puddle slowing you while you walk in, a small elf running fast towards you (the only non-static enemy) and a soldier pig raising a shield wall to block you while the camera continue to move forward until you are out of its field of view and instantly lose. Every enemy has an hit box damaging you once when you collide with it, making you lose one out of three health points. 
You can touch the rigt side of the screen to kill them with your sword in one shot. You can dodge them as well as the holes by touching the left side of the screen to jump, and you even have the ability to dash forward by sliding a finger on the screen's right side towards the right, it allows you to avoid colliding any enemy hitbox and quickly move forward.
The game provides a mini shop to unlock a double jump ability and upgrade the dash's cooldown and travel distance for money from coinq you can collect across the world. You can also meet sometimes a special flying coin that will give you a short powerful boost that makes you travel a certain distance very quickly without heigh fall-off.

### Programming

Made with C# on Unity3D. Built for Android with the Android SDK, NDK and openJDK.

### Overview
[![thumbnail_overview]](https://www.youtube.com/watch?v=rFTgVmh7c4g)


## My contribution

It was the third project I made in a team but the first one we tried to make on the mobile platform, like for everyone too in the team. We were 5 programmers and 5 graphic artists. As a team of only programmers and graphic artists, none of us were sound designer. So I chose to take on the SFX work, using audacity to edit and mix already existing sounds. I came up with different sounds for the actions and skills of the player and enemies, interactions and UI audio feedbacks. That was an interesting experience, but not my favourite though.

Some exemples :
| Description                | Sound (click)                                                                         |
| :------------------------- | :-----------------------------------------------------------------------------------: |
| pig enemy deploying shield | [![sound]](https://mega.nz/file/EfA3jCyQ#vShNj7ocOngT-bYNi4JGowSxk7cZKNRZm8_wmcCYPIM) |
| player attacking           | [![sound]](https://mega.nz/file/NTRAiBrI#kOdRmTiRudt2O8rMePxS4BPNrf-wenHBC_v2RiZDnSI) |
| travel boost               | [![sound]](https://mega.nz/file/NfJi2Jgb#z1fJ3xJ9Xeopavx0k6Ru7rFEN1dYKhCYWSXNqDH-DdI) |
| item collecting            | [![sound]](https://mega.nz/file/xXQRgQhQ#j2IP8ngniwJ8Aq-zW5dvCo5Mv1QUD3Rp1kg_vYpwx-s) |


As a very first mobile developement experience, it was thus also the first I had with touch screen inputs. I learnt and use the Unity API's part for touch inputs for the first time. I implemented the input system for the touch controls to detect different touch movements on the same touch area. The two touch areas are the left and right side of the screen, where you use the thumbs.

[![thumbnail_touchcontrols]](https://www.youtube.com)


## Credits

Thanks to the school [Creajeux](https://www.creajeux.fr/) (Nîmes, France) where this poject was carried out with my 9 other coworkers :

#### Graphic artists
- Alex WISSLER
- Aude VERQUIN
- Killian GARNIER
- Matthieu LAUDE
- Yonathân PADOT

#### Programmers
- Ivan MEGARD
- Renald DURET (me)
- Xan-Meng YANG
- Edouard SUKRIEH
- Quentin LADOIRE ZAGUET


<!-- MEDIA FILES -------------------------------------------------------------------------------------------->
[title]: Back_to_Hell_title.jpg
[thumbnail_overview]: Back_to_Hell_thumbnail_01.jpg
[thumbnail_touchcontrols]: Back_to_Hell_thumbnail_02.jpg
[sound]: sound_icon.png
