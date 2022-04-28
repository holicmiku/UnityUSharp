# UnityUSharp
This is UdonSharp(U#) projects that I did.</br></br>

# What is UdonSharp?
## A compiler for compiling C# to Udon assembly
UdonSharp is a compiler that compiles C# to Udon assembly. UdonSharp is not currently conformant to any version of the C# language specification, so there are many things that are not implemented or will not work.</br>
if you want to know about more UdonSharp, https://github.com/vrchat-community/UdonSharp </br>  </br> 

## Setup</br>
Unity   
Current support latest unity version is 2019.4.31f1.</br>
Check again when you start this. As you can, download latest unity version.</br>
https://docs.vrchat.com/docs/current-unity-version</br>

[VRCSDK3-WORLD]</br>
Login VRChat and Download SDK3-WORLD 

[UdonSharp]</br>
Download latest release version of UdonSharp.

(Optional)[CyanEmu]
Download latest release version of CyanEmu

## Getting started

Make Unity project and follow this order.

1. Import VRCSDK3-WORLD-2022.02.16.19.13_Public.unity.package (Latest)

2. Import UdonSharp_v0.20.3.unitypackage (Latest)

3. (Optional) Import CyanEmu.v0.3.10.unitypackage (Latest)

4. Import packages which you want to play in my repository.

5. Feel free to play unity scene.

## Notice
When you want to test global environment, follow this order</br>
*World Upload that your VRChat account(steam or vrchat both)'s level needs at least New User level.
1. Getting Started at 1~4</br>
2. VRChat SDK->Login->Builder-> Build & Publish for Windows</br>
If you can't Build & Publish for Windows, make sure click Setup Layers for VRChat button and Set Collision Matrix button. 

Global Test needs people at least 2 person for check sync working.

e.g. Play_Particle_Global Local_Global_Owner
     ViaOwner_CountUp
     ChangeOwner_CountUp 
	..

[VRCSDK3-WORLD]:https://vrchat.com/home/download
[UdonSharp]:https://github.com/vrchat-community/UdonSharp/releases/tag/v0.20.3
[CyanEmu]:https://github.com/CyanLaser/CyanEmu/releases/tag/v0.3.10