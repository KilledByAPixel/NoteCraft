# NoteCraft 🎵🔨

# [Live Demo](https://killedbyapixel.github.io/NoteCraft/)
# [JS13k Submission](https://js13kgames.com/entries/notecraft)

NoteCraft is a Cellular Automata Music System

![NoteCraft Image](/screenshotSmall.png)

Features
- Export to ZzFXM and OS13k
- Share compressed links
- Several example songs
- Instruments are customizable
- Undo and Redo
- Cut, copy, and paste
- Turing complete!

Controls
- Draw = Left Mouse
- Erase = Ctrl + Left Mouse or Left + Right Mouse
- Test Cell / Eyedropper = Right Mouse
- Move View = Click & Drag Middle Mouse
- Zoom View = Wheel
- Select Area = Shift + Left Mouse

Cell Types
- Power/Mover - Provides power to neighbor cells and moves
- Power Line - Transfers power
- Rotator - Rotates cells and redirects movement when powered
- Copier - Copies and unpoweres cell when powered
- Push Blocks - Can be pushed or not pushed
- Stop Block - Destroys anything pushed into it when powered
- Note - Plays a note when powered and holds until unpowered
- Note Control - Changes the key or attenuation of conneted notes

Selection Controls
- R/E = Rotate
- Q = Mirror
- T = Spread
- WASD = Move

Play Controls
- Toggle Play/Edit = Space
- 0 = Stop
- 1 = Play
- 2 = Pause
- 3 = Step
- 4 = Fast Forward
