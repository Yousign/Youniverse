# Youniverse
*The Yousign virtual offices using [WorkAdventure](https://workadventu.re)*

## Informations
On the [Workadventu.re map starter kit](https://github.com/thecodingmachine/workadventure-map-starter-kit)

## Get Started

In order to custom the Youniverse maps, you need to :
- Have the [Tiled editor](https://www.mapeditor.org/) software installed
- Have the maps on your computer 
  - Clone this repository or download it staticly using the `Download Zip` into the `green Code button`

### Cloning the map

Start by cloning the map. If you are used to Git and GitHub, simply clone the map
to your computer using your preferred tool and [jump to the next chapter](#loading-the-map-in-tiled).

If you are new to Git, cloning the map means downloading the map to your computer.
To do this, you will need Git, or a Git compatible tool. Our advice is to use
[GitHub Desktop](https://desktop.github.com/).


### Loading the map in Tiled

The default office map is in the file `map.json`.
You can load this file in [Tiled](https://www.mapeditor.org/).

Some resources regarding Tiled:

- [Tiled documentation](https://doc.mapeditor.org/en/stable/manual/introduction/)
- [Tiled video tutorials](https://www.gamefromscratch.com/post/2015/10/14/Tiled-Map-Editor-Tutorial-Series.aspx)

### About WorkAdventu.re maps

In order to design a map that will be readable by WorkAdventure, you will have to respect some constraints.

In particular, you will need to:

- set a start position for the players
- configure the "floor layer" (so that WorkAdventure can correctly display characters above the floor, but under the ceiling)
- eventually, you can place exits that link to other maps

All this is described in the [WorkAdventure documentation](https://github.com/thecodingmachine/workadventure/#designing-a-map).
Please be sure to check it out. 

### Pushing the map

When your changes are ready, you need to "commit" and "push" the changes back to GitHub.
Just wait a few minutes, and your map will be propagated automatically to the GitHub pages web-server.
