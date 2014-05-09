# Radius

A Complete Unity Reference Project 

# Features
 - Full complete game
 - Multiplayer (Online, [MasterServer](https://docs.unity3d.com/Documentation/ScriptReference/MasterServer.html)): Semi-Authoratitive
 - Full Menu UI and HUD: Utilizing the awesome power of [Coherent UI](http://coherent-labs.com/); HTML, CSS, JS web stack
 	 - Server Browser
 	 - Match Lobby
 	 - Player Customization
	 - Options menu
	 - In-game HUD
 - Procedurally generated objects
 - Multiple Levels
 - Sound Effects and Music + Volume


# Details:
 - Developed in Unity 4.3.1f1
 - Tested with Coherent UI 1.8.1
 - [Requires Unity Pro(because Coherent UI uses native code)](http://docs.unity3d.com/Documentation/Manual/Plugins.html) to work in the editor. You can build with Unity Free and add the dlls manually. See the [guide I made on using unmanaged Dlls with Unity to get a hint on how to get Coherent UI working](http://ericeastwood.com/blog/17/unity-and-dlls-c-managed-and-c-unmanaged)

# How to use
 - Clone/Download the repo
 - Open in Unity
 - Import the Coherent UI package
 	 - You can [get a free evaluation version(only limitation is a watermark) of Coherent on their website](http://coherent-labs.com/)
 - Goto `Edit->Project Settings->Coherent UI->Select UI Folder` and select the `UIResources` folder in the Unity project root
 - You should be able to play it in the editor if you have Unity Pro
	 - If you have Unity Free, it will only work if you build the project and use [this guide](http://ericeastwood.com/blog/17/unity-and-dlls-c-managed-and-c-unmanaged) to manually copy over Coherent's Dlls



## Less notable features:

 - Character Controller/Driver: `CharacterDriver.cs`
 - Camera Controller (Conic): `ConicCameraController.cs`
 - Master Volume for Music and Soundeffects: `AudioManager.cs`, `AudioBase.cs`