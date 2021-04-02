# cs-cfg

This repository contains common configurations used by TOA on Counter Strike - Global Offensive

# Getting Started

After clonning this repository, all you need to do is create a hard link to each of your cs configs. The Steam / Counter-Strike folder may differ from the folder below.

## On Linux

`ln ./cfg/competitive.cfg ~/.steam/steam/steamapps/common/Counter-Strike\ Global\ Offensive/csgo/cfg/competitive.cfg`

`ln ./cfg/training.cfg ~/.steam/steam/steamapps/common/Counter-Strike\ Global\ Offensive/csgo/cfg/training.cfg`

## On Windows

`mklink /h "./cfg/competitive.cfg" "C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg/competitive.cfg"`

`mklink /h "./cfg/training.cfg" "C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg/training.cfg"`
