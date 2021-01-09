![Image of Cups](https://github.com/t8rn8r/parameterized-component-storage/blob/main/pictures/stack%20(2).jpg)

# Parameterized Component Storage
Cups for storing small components within a larger box. Designed to be 3D printed and totally parameterized to fit any (rectangular) situation.
The cups can be stacked in an arbitrary number of layers within the box.

## Goal
- Provide a universal solution for storing arbitrarily sized components in arbitrarily sized boxes

## Background
I have a lot of tools, electronic components, and mechanical parts to store, but I don't want to buy a bunch of dedicated containers when I'm already drowing in boxes from 3D printer filament and Amazon packages. In the spirit of reducing, reusing, and recycling, made these little cups to store my things more efficiently without generating more waste. 

## Instructions

### Print from .f3d file
1. Download the .f3d file.
1. Open the .f3d file in Fusion 360.
1. Open the parameter editor (Modify > Change Parameters).
1. Modify the parameters to your needs (see below).
1. Export as .sdl file.
1. Open in Cura.
1. Download the Cura profile.
1. Import the Cura profile, make adjustments as you see fit. 
1. Print!

### Print from .stl files
1. Download desired .stl file.
1. Opn in Cura.
1. Download the Cura profile.
1. Import the Cura profile, make adjustments as you see fit.
1. Print!

## Modifying parameters
### Starred Parameter Values
The starred parameters are the most relevant for most applications. 
- `boxiw`, `boxil`, and `boxih` are the larger container's internal width, length, and height respectively.
  - Note that the width is the dimension along which the handles will be made.
  - The default values fit my 3D printer filament boxes very well.
- `cumnumw`, `cupnuml`, and `cupnumh` are the number of cups to make along the width, length, and heigh respectively.
  - In principle, the internal dimensions of the box will be divided evenly amongst all the cups in each direction (although this is not entirely true).
  - By dividing in this manner, one can ensure that cups of varying dimensions all fit within the same box. 
- `thick` is the thickness of all the walls and the handle of the cups. 

### Other parameters
Just play with them until you get the result you want. I don't guarantee they will actually work. 

## Examples
![Image of Cups](https://github.com/t8rn8r/parameterized-component-storage/blob/main/pictures/8x8x6%20(2).jpg)
![Image of Cups](https://github.com/t8rn8r/parameterized-component-storage/blob/main/pictures/8x8x6%20(3).jpg)
![Image of Cups](https://github.com/t8rn8r/parameterized-component-storage/blob/main/pictures/8x8x6%20(4).jpg)
![Image of Cups](https://github.com/t8rn8r/parameterized-component-storage/blob/main/pictures/8x8x6.jpg)
![Image of Cups](https://github.com/t8rn8r/parameterized-component-storage/blob/main/pictures/stack.jpg)
