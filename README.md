# C++ Console Project

# About
A simple C++ console project from early 2024.  
It utilizes the Standard Template Library like I/O or chrono for Gameplay Mechanics like receiving Input and controlling framerate.  
<div align="center">
<img src="https://github.com/user-attachments/assets/fce8fa0f-6194-4426-9aad-ab7a43cd66a7" alt="SK_Titlescreen" width = "400"/>  
 </div>

## Framerate Control
The framerate is controlled by using the chrono library. On each loop iteration the current time is saved in a time point of the high_resolution_clock class.  
At the end of the iteration the current time is saved in another time point which gehts compared to the desired frameTime. It continues as soon the desired frameTime  
is reached and increments the frameCounter.
<div align="center">
<img src="https://github.com/user-attachments/assets/42f9c5ec-d9a5-486c-af8d-897e00139d45" alt="SK_Titlescreen" width = "400"/>  
 </div>


## Turnbased Combat
A simple turnbased combat system with Attack and Flee Option. Attak deals damage equal to player strength minus Target defense.  
Flee gets the player out of combat and sets his position to the rooms entry,.
 <div align="center">
<img src="https://github.com/user-attachments/assets/d6eec9e6-8f8f-4557-a41f-23b091fe98da" alt="Combat" width = "400"/>  
 </div>

 ## RPG Mechanics
 Rest at the bonfire to spend your EXP and level up your health, damage or defense. That respawns all defeated enemies.  
  <div align="center">
<img src="https://github.com/user-attachments/assets/72362f5d-b27b-49be-af21-da97c9f022be" alt="RPG_Mechanics width = "400"/>  
 </div>

