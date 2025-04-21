# BRSUN-EN-Patch-Project
## The Game Already EOS long ago but, The spirit to make English patch still alive!


## Finally, the patch and the previously translated story (before this patch was made) have caught up with each other. From this point on, progress will slow down because the holidays are over and it will take more time to refine the sentences that were translated using MTL (machine translation).

This patch uses ```BepInEx-Unity.IL2CPP-win-x64-6.0.0-be.704```, which has been modified to work with the BRSun game.

**Installed Plugins**
- [XUnity.AutoTranslator-BepInEx-IL2CPP-5.4.5](https://github.com/bbepis/XUnity.AutoTranslator)
- [BepInEx.Utility.IL2CPP EnableFullScreenToggleIL2CPP_net6](https://github.com/BepInEx/BepInEx.Utility.IL2CPP)

**Patch Release Versions**
- Contains only the necessary patch files.
- Contains patch and partially translated content into English.

**Installation**
- Download the desired patch files from the [Releases Section](https://github.com/kokomif/BRSUN-EN-Patch-Project/releases).
- Extract the .zip file in the game folder

**How to Make the Main Character's Name Show Up in the Story**

To make the game story display your main character's name correctly, you need to modify the `_Substitutions.txt` file.

**File Location**
`YourGameFolder\BepInEx\Translation\en\Text\_Substitutions.txt`

Inside the _Substitutions.txt file, you’ll see a placeholder like this:

`Asahina=Asahina`

This placeholder controls how the name appears in the story.

If you want to use a different name for the protagonist, just replace it with your preferred name.
For example, to change the protagonist’s name to Firis, you can write:

`Firis=Firis`

⚠️ Make sure the left and right sides are the same — this tells the game to replace the original name with your chosen name wherever it appears.

**Known Issues**
- The in-game UI of a BepInEx mod (like XUnity's GUI) is completely broken. However, this is not an essential function. The patch works without the GUI, and you can edit its configuration in the plugin's `.cfg` file.

**Change Log**
v0.3

Update Translated Main Story up to CASE04

v0.2

Update Translated Main Story up to CASE02

v0.1 

Initial Release of necessary patch files and partially translated content into English (Home UI, Enhance Menu, Party Menu, Passive Effect, and Partial of CASE00 main story)

**Special Thanks to**
- Solaire of Astora, a member of the Atelier Discord Community, for making BepInEx compatible with the BRSun game.
- The [Atelier Discord Community](https://discord.gg/tNB62xYZ95) for their support and for inspiring the idea to create an English patch.
- The Blue Reflection Discord Community for their support and for providing story transcripts, some of which have been translated.
- And to you, for wanting to read the story in the English language.
