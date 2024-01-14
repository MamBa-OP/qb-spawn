# qb-spawn
Spawn Selector for QB-Core Framework :eagle:

# Edited By
!                         MamBa#4107

# Main Author
MoneSuper#0001


# License

    QBCore Framework
    Copyright (C) 2021 Joshua Eger

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>


## Dependencies
- [qb-core](https://github.com/qbcore-framework/qb-core)
- [qb-houses](https://github.com/qbcore-framework/qb-houses) - Lets player select the house
- [qb-apartment](https://github.com/qbcore-framework/qb-apartment) - Lets player select the apartment
- [rbrp-garages](https://github.com/qbcore-framework/rbrp-garages) - For house garages

## PREVIEW YT
!Preview: https://youtu.be/7oxBR_5IzXU

## Features
- Ability to select spawn after selecting the character

## Installation
### Manual
- Download the script and put it in the `[qb]` directory.
- Add the following code to your server.cfg/resouces.cfg
```
ensure qb-core
ensure qb-spawn
ensure qb-apartments
ensure rbrp-garages
```

## Configuration
An example to add spawn option
```
QB.Spawns = {
    ["spawn1"] = { -- Needs to be unique
        coords = vector4(1.1, -1.1, 1.1, 180.0), -- Coords player will be spawned
        location = "spawn1", -- Needs to be unique
        label = "Spawn 1 Name", -- This is the label which will show up in selection menu.
    },
    ["spawn2"] = { -- Needs to be unique
        coords = vector4(1.1, -1.1, 1.1, 180.0), -- Coords player will be spawned
        location = "spawn2", -- Needs to be unique
        label = "Spawn 2 Name", -- This is the label which will show up in selection menu.
    },
}
```


<p>Visitor count</p>
  <img src="https://profile-counter.glitch.me/qb-spawn-replace/count.svg" />
