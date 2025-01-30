# ACB Version 4.0

# Supported files (Macros)
[Echo](https://discord.gg/7yEHbBVswh) `(.echo)` (Quite an old version of echo, not the latest.)

[TASBot](https://discord.gg/RbWPSYPyrS) `(.json)`

# Clickpack guide

 

    This is how to add your own clicks.
    Example folder: clicks-example.
    First up, add a "player1" folder inside it.
    You can optionally create a folder called "player2" if you want different clicks for the second player.
    
    In the folder, create the following folders:
    clicks (necessary)
    releases (optional)
    softClicks (optional)
    softReleases (optional)
    
    clicks will be used when you click the mouse (in the macro.)
    releases will be used when you release the mouse. (if you don't specify it, it will use clicks instead of releases.)
    softClicks are optional, but highly recommended. (They make the clicks realistic in spams.)
    softReleases are optional, they're played after softclicks. (if you dont specify it, it will use normal releases.)
    
    In the folders, create sounds like this:
    1.wav
    2.wav
    3.wav
    4.wav
    and so on...
    
    Clickpack directory example:
    
    .
    └── Any Folder Name Which You Will Select/
        ├── player1/
        │   ├── clicks/
        │   │   ├── 1.wav
        │   │   ├── 2.wav
        │   │   ├── 3.wav
        │   │   └── 4.wav
        │   ├── releases/
        │   │   ├── 1.wav
        │   │   ├── 2.wav
        │   │   └── 3.wav
        │   ├── softClicks/
        │   │   ├── 1.wav
        │   │   └── 2.wav
        │   └── softReleases/
        │       ├── 1.wav
        │       ├── 2.wav
        │       ├── 3.wav
        │       └── 4.wav
        └── player2/
            ├── clicks/
            │   ├── 1.wav
            │   ├── 2.wav
            │   └── 3.wav
            ├── releases/
            │   └── 1.wav
            ├── softClicks/
            │   ├── 1.wav
            │   ├── 2.wav
            │   ├── 3.wav
            │   └── 4.wav
            └── softCeleases/
                ├── 1.wav
                ├── 2.wav
                ├── 3.wav
                └── 4.wav

