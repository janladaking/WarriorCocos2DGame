FantasyWarrior3D
================

FantasyWarrior is a showcase project using Cocos2d-x 3.4

Cocos2d-x Features used in this project
* Sprite3D
* Animation3D
* Mesh
* Billboard
* Camera
* Light
* New audio engine

The code of this project and Cocos2d-x are all licensed under MIT

BGMs are copyrighted by Matthew Pablo, and licensed under CC-BY 3.0

You may not use any art including 2d and 3d from this project for commercial purpose

##Git user attention

1.Clone the repo from Github

```
$ git clone https://github.com/janladaking/WarriorCocos2DGame.git
```

2.Update the submodule of FantasyWarrior3D

```
$ git submodule update --init
```
3.Update the submodule of Cocos2d-x

```
$ cd frameworks/cocos2d-x
$ git submodule update --init
```

4.After cloning the repo, please execute `download-deps.py` to download and install dependencies

```
$ cd frameworks/cocos2d-x
$ python download-deps.py
```


##Platform support
This projetc supports 3 platforms: win32, ios_mac and Android.

###ios_mac runtime
Path:
`WarriorCocos2DGame/frameworks/runtime-src/proj.ios_mac/FantasyWarrior3D.xcodeproj`.

###win32 runtime
Path: `WarriorCocos2DGame/frameworks/runtime-src/proj.win32/FantasyWarrior3D.sln`.
>Requires Visual Studio 2012 and above.

###android runtime
Path: `WarriorCocos2DGame/frameworks/runtime-src/proj.android`.

##Credits
* Game Effects: Jan Lada(jan.lada415@hotmail.com)
* Game Logic: Urosevich Bob(topurosevich@gmail.com)
* Game Logic: Laszlo Mados(laszlo.mados@gmail.com)
* Game Logic: Jaroslava Mucha(jaroslava.m21@hotmail.com)
