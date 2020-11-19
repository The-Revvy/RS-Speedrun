# RS-Speedrun
An e-Reader dotcode that instantly beats the game

I made a mistake while working on [e-Writer](https://github.com/The-Revvy/e-writer) that ended up warping me to a blank map upon scanning the dotcode. I knew what I had to do.
## How to build

* Download [nedcmake](https://www.caitsith2.com/ereader/tools/nedcmake.rar) from [caitsith2.com E-Reader Development Tools](https://www.caitsith2.com/ereader/devtools.htm)

To run in an emulator: generate `RAW`:
```
nedcmake.exe -i card.z80 -o us -type 1 -region 1 -raw
```

To run on real hardware: generate `BMP`:
```
nedcmake.exe -i card.z80 -o us -type 1 -region 1 -bmp
```
