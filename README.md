# steam deck info
information about steam deck setup I struggled to find, open a PR to add extra info if you have more information


## Lutris

To setup Lutris for installation of some of the launchers (some may crash during install, manually install them then):

1. launch desktop mode by pressing the steam button, pressing power, and choose reboot to desktop
2. go to Discover
3. Search for Lutris
4. Press install
5. login to eg gog (gog is easiest to setup games for, as it doesn't require an external launcher)
5a. install the launcher for origin or other storefronts by selecting the person icon and following the steps
5b. login to the storefront
6. install the game you want to install

### Lutris troubleshooting

1. if you get error 256, manually install the storefront for eg Ubisoft and use it to install games manually


## Install Ubisoft Connect

1. launch desktop mode by pressing the steam button, pressing power, and choose reboot to desktop
2. download ubisoft connect from here https://ubisoftconnect.com/en-GB/
3. add a non steam game, browse to downloads, and select the executable
4. right click, compatibility, proton 7
5. run the app
6. install to Z:/home/deck/Games/Ubisoft-Connect
7. add UbisoftConnect by adding a non steam game and selecting the UbisoftConnect executable (don't launch)
8. add `STEAM_COMPAT_MOUNTS=/run/media/mmcblk0p1/ %command%` to the launch options
9. install the games you want by adding the following to the launch options `uplay://launch/${game_id}/0` where game_id is found [here](https://github.com/Haoose/UPLAY_GAME_ID)


more will be added in the future
