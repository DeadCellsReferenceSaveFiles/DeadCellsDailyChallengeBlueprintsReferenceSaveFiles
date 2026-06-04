# Dead Cells Daily Challenge Blueprints Reference Save Files

## About

Reference save files for Dead Cells containing the three blueprints only obtainable by completing the Daily Challenge enough times:

- Swift Sword (`SpeedBlade`)
- Lacerating Aura (`DamageAura`)
- Meat Skewer (`DashSword`)

These blueprints are currently unobtainable on older Dead Cells versions because the Daily Challenge requires the most recent version of the game. They could become unavailable on the most recent version of the game too if the Daily Challenge servers are ever shut down. The save files were created for version 0.3 of the game, which is the version in which Daily Challenge mode and the above three blueprints were added.

The "minimal" file is the smallest save file that I was able to create which Dead Cells version 0.3 will successfully load. It omits class and schema definitions from the `S_User` chunk and could therefore be read incorrectly by later versions of the game. For normal gameplay, use the larger save file. I have also successfully loaded the larger save file from version 2.9 of the game.

Neither save grants the corresponding items. They still need to be purchased from the Collector using cells.

## Usage

To use one of the save files (I recommend using `deadCells_0.3_dailyChallengeUnlocks.dat`), copy it into the game's save files directory and name it `user_<N>.dat` where `<N>` is the save slot you want it to occupy. For Dead Cells on Steam on 64-bit Windows, that directory is `%programfiles(x86)%\Steam\userdata\<steam-user-id>\588650\remote` where `<steam-user-id>` is your Steam user ID. Ensure it is newer than any file it replaced in order to avoid the Steam Cloud copy of the save overwriting it.

If you're reading this on the GitHub website, then you can download a save file by clicking on it in the file list, then clicking the download button which has a "Download raw file" tooltip.

## Thanks

The following resources were invaluable while creating these reference save files:

- https://n3rdl0rd.github.io/ModDocCE/files/hxbit
- https://github.com/N3rdL0rd/alivecells