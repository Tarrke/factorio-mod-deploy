# Factorio Mod Deployer

A simple python scritp that can deploy a mod from its sources

## Install

Simply clone the repository and put the script into a accessible path (ie in your PATH variable somewhere)

## Mod structure

Your mod should have the following structure:
```bash
.
├─── info.json
├─── locale
│   ├─── en
│   └─── locale.cfg
└───src
    ├─── control.lua
    ├─── data.lua
    ├─── settings.lua
    └─── mod
        ├─── mod.lua
        └─── other.lua
```
## Usage

* Go to your factorio mod source folder
* fire the script
