# BGS_WeaponInfo

 An example of how to edit weaponinfo files for RedM.

 THIS PROCESS IS BROKEN, CURRENTLY.

 The game does not load the files correctly. 
 However, I will still demonstrate how it WOULD work if they did load correctly.

This repo contains an fxmanifest.lua file and a weaponinfo file.

The fxmanifest.lua file will load the weaponinfo file. It will load it at the wrong time, because, as I said, the game is broken currently.

However, if you restart the resource after logging in, it should work. Note that it will restart for ALL players, EVERY time.

You can add more weapons from weapons.ymt via CodeX. The more you add, the more likely it is the file will fuck up during the load and not load all/any of the weapon changes correctly.
Some changes don't load no matter what you do. Recoil is always set to some default value no matter what you do. As I said, it is broken.

Just things to keep in mind. Have fun!
