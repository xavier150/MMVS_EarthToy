# MMVS - EarthToy

This mod allows you to play [Macro Micro VR Service (MMVS)](https://www.bleuraven.fr/mmvs) in real-world environments using Cesium ion.

![EarthToy Poster](https://github.com/xavier150/MMVS_EarthToy/wiki/images/earth_toy_poster.jpeg)

At the moment, this mod only works with MMVS **v0.4.7**, and each new release of the mod will target the current version of MMVS.

This is because the mod is packaged into game `.pak` files during the game's build process.  
In the future, the [MMVS SDK](https://github.com/xavier150/MMVS/wiki/(Milestone)-MMVS-SDK) will provide better mod support, so the mod will no longer depend on a specific MMVS version.

# How to Install

- Go to the [Releases page](https://github.com/xavier150/MMVS_EarthToy/releases).
- Download `EarthToy_0.0.1-MMVS_0.4.7.zip`.
- Extract the archive and place all pakchunk files in `[GameFolder]\MacroMicroVRService\Content\Paks`.

<img src="https://github.com/xavier150/MMVS_EarthToy/wiki/images/how_to_install/extracted_files.png" alt="Extracted files" width="50%" height="auto">

# How to Play

- Launch MMVS.
- Start a new game (the configuration doesn't matter).
- Once the game has loaded, press "R" to open the debug menu.
- Go to "Misc" and enable the "Game Modding" option.
- A new page will appear below. Navigate to "Custom Levels" and click on "World Play Rug".

<img src="https://github.com/xavier150/MMVS_EarthToy/wiki/images/how_to_use/navigation_to_custom_levels.png" alt="Navigation to Custom Levels" width="50%" height="auto">

- You can now read the in-game panel for more details.
- Enjoy!

![EarthToy Footprint](https://github.com/xavier150/MMVS_EarthToy/wiki/images/earth_toy_footprint.jpeg)

In the future, with the MMVS SDK, it will be possible to load the level directly from the play page.

# Recommendations
- Currently, the lighting is not very stable. I recommend enabling hardware ray tracing in Settings -> Graphics.
- Because Talas is gigantic, the camera shake can be very intense. You can reduce it in Settings -> Ergonomics -> Camera Shake Intensity.

# Additional Notes
- The destruction effects are only visual for now. You cannot fall into the footprints because the collision geometry does not update accordingly.
- To play in multiplayer, type `/Open WorldPlayRug?listen` in the chat to host a session.
- For now, the mod is not compatible with Linux on ARM.
- For now, you can only load preset regions. In the future, you will be able to create your own presets and explore the entire Earth.
- If you want spawn a vehicle, use the `/cheat_wheeeeel` command in the chat.

# Disclaimer
Users are responsible for complying with Cesium ion's Terms of Service.  
The developer is not liable for misuse or violations of Cesium ion policies.