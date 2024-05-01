# CS2 Sounds List

A complete list of CS2 sounds as of 1/5/2024.

The primary use-case for this list is to be used for a refrence point when creating in-game binds to add additional sounds.

# Export Process

To export an updated list of sound directories, the following process can be followed.
Please note; I will be using [VPKEdit](https://developer.valvesoftware.com/wiki/VPKEdit) to extract the packaged game contents.

1. Launch VPKEdit ![image](https://github.com/redBDGR/CS2SoundList/assets/26995443/f56ed96a-3d2b-481c-94be-1bfc2c8b0bf9)

2. `File -> Open` and locate your CS2 game directory within steamapps folder `C:\ProgramFiles (x86)\Steam\steamapps\common\Counter-Strike Global Offensive`

![image](https://github.com/redBDGR/CS2SoundList/assets/26995443/d8e9ec6b-d692-4c5a-b82b-09d9cae97e38)

3. Locate the .VPK package `game\csgo\pak01_dir.vpk`
4. Find the "sounds" folder after the .vpk package has imported into VPKEdit
5. Right click and select `Extract Folder...`

![image](https://github.com/redBDGR/CS2SoundList/assets/26995443/366bcef5-57ca-4b21-9e85-57ea74aa38c8)

6. This will then create a new folder with all exported sound files within.

I then use a python script to walk through all files in this directory and write the file names to a text file.
