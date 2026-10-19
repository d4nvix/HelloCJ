<img width="1919" height="1079" alt="Снимок экрана 2026-10-19 195109" src="https://github.com/user-attachments/assets/c79433b1-5541-4edc-b51f-d106728de06c" />
HelloCJ — GTA: San Andreas inside Hello Neighbor
Ah shit, here we go again... but in the Neighbor's house.

HelloCJ brings GTA: San Andreas into Hello Neighbor. It runs the two games together using a bridge, so you can experience the Neighbor's world with a GTA-style player. It's an unofficial fan project and still a work in progress.
What is in the mod?
- A launcher that starts the GTA: San Andreas side and then Hello Neighbor.
- A bridge between the two games, including player-state syncing and rendering components.
- A GTA SA-side setup with CLEO and Mod Loader files.
- Scripts for installation, launching, and stopping both games.
Some features may not work perfectly yet. This release has not been gameplay-tested for this README.
Requirements
- Windows PC with PowerShell.
- GTA: San Andreas (classic PC edition), with gta_sa.exe in its game folder.
- Hello Neighbor (PC), with HelloNeighbor/Binaries/Win64/HelloNeighbor-Win64-Shipping.exe in its game folder.
- The required Essential Pack for GTA SA mentioned in the original packaged README. The package doesn't identify its exact version or contents, so use the one specified by the project author rather than guessing.
- Administrator permission for the included installation and launch scripts.
Important: This is intended for the classic GTA SA executable; GTA: The Definitive Edition is not confirmed to work. You need your own copies of both games; they are not included.

Download the release asset named HelloCJ.zip, not GitHub's automatic Source code (zip) archive. The source archive does not contain the released mod package.
Installation
1. Install GTA: San Andreas and Hello Neighbor on your PC.
2. Install the GTA SA Essential Pack required by this mod into your GTA SA game folder, as instructed by its provider.
3. Close both games.
4. Download HelloCJ.zip and extract the whole archive to a folder of your choice. Do not run the scripts directly from inside the ZIP.
5. Open the extracted HelloCJ folder. Make sure install.bat, play.bat, stop.bat, HelloCJ.ps1, config.json, .tools, and files are present.
6. Right-click install.bat → Run as administrator. Windows will ask for permission because the installer copies files into the game directories.
7. When prompted, enter the full path to your GTA SA folder and Hello Neighbor folder. The installer checks for gta_sa.exe and HelloNeighbor-Win64-Shipping.exe.
How to play
1. Run play.bat in the extracted HelloCJ folder.
2. Approve the Windows administrator prompt if it appears.
3. The launcher starts the GTA SA side, waits for the game to be ready, and then starts Hello Neighbor.
4. Once Hello Neighbor opens, load a level and play.
The startup check can wait up to 180 seconds for GTA SA to become ready. If Hello Neighbor doesn't launch, check the error messages rather than opening the games independently.

To close the configured game processes, use stop.bat. Save your progress first: the stop script warns that unsaved progress may be lost.
Troubleshooting
Installer can't find the game folders? Make sure you're giving the folder containing gta_sa.exe for GTA SA and the folder containing HelloNeighbor/Binaries/Win64/HelloNeighbor-Win64-Shipping.exe for Hello Neighbor.

Missing package files? Extract the entire ZIP, including the hidden-looking .tools folder. Don't move the batch files away from the rest of the mod.

Hello Neighbor doesn't start? First check whether GTA SA started correctly. Then look in logs/last-error.txt and logs/guest-launch-error.txt inside the extracted HelloCJ folder.

Installation failed? Read the error in the installer window. The script stores copies of replaced files in backups.

Credits
- Rockstar Games — Grand Theft Auto: San Andreas.
- tinyBuild / Dynamic Pixels — Hello Neighbor.
- UE4SS and other third-party components — see the included licenses folder.
- d4nvix - Creator mod HelloCJ
Unofficial fan project. Not affiliated with Rockstar Games, tinyBuild, or Dynamic Pixels. No base game copies are included.
