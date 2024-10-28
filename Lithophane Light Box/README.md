# Overview
This is a lithophane light box that I have designed myself as a side project. To light up the lithophane from the back, an LED strip is attached at the back, with a USB-C connector to power the LED. Assembly instructions are written in the [Usage](#usage) section.

<img src="./images/kanagawa.png" height="300"/> 
<img src="./images/kanagawa back.png" height="300"/>

# Usage

Bill of materials:
1. 5V LED light strip 3528 (I got mine [here](https://a.aliexpress.com/_oE7EGl1)) 

    <img src="./images/light strips.png" width="300"/>

1. USB-C female plug (I got mine [here](https://a.aliexpress.com/_okP0abd))

    <img src="./images/usbc%20connector.png" width="300"/>

To be printed:
1. 1x main body.stl
1. 1x back panel.stl
1. 1x lithophane (generate this for yourself, instructions below)

## 1. Generating a lithophane
Go to the [ItsLitho](https://tool.itslitho.com/UploadImg) website to generate a lithophane from an image. Ensure that your image is cropped to a 4:3 aspect ratio for compatibility with this Light Box. Upload your image on the site.
![image](./images/itslitho.png)

Click on the "model" tab to generate your lithophane.
![image](./images/model.png)

On the left panel, ensure the settings correspond accordingly:
1. height x width = 105 x 140 mm
1. min thick = 1.2mm

![image](./images/settings.png)

Download the model with the button on the bottom right.
![image](./images/download.png)

## 2. Printing the lithophanes
Load the generated stl into your slicer (I'm using Bambu Studio but you may use Cura, PrusaSlicer, OrcaSlicer or other slicers)

Material wise, I use a matte white PLA filament, but any white filament should work. Avoid using white filaments advertised as warm / cool. Surprisingly, I find cheaper filaments work better as they're less opaque.
Slicer settings for lithophanes:
- Layer height: 1.2mm
- Brim type: Outer brims only (basically enable brims)
- Wall loops: 99999999
- Top surface pattern: Concentric
- Bottom surface pattern: Concentric
- Infill: 100% Concentric
- Speed: to your liking, preferably slower

![image](./images/slicer%20settings.png)

For the light box itself, use the following print settings:
- Layer height: 2.0mm
- Brim type: None 
- Wall loops: 2
- Infill: 15% Lightning (avoid using gyroid, the infill might look gross when the light shines from the inside)

## 3. Assembly
1. Solder the USB-C connector to the 5V LED strip and test that it works

    <img src="./images/assembly 1.jpg" width="300"/>
    <img src="./images/assembly 2.jpg" width="300"/>

1. Slot in the USB-C connector and LED strip through the hole of the `back panel` and snap the USB-C plug into place

    <img src="./images/assembly 4.JPG" width="300"/>

1. Stick the LED strip around the sides of `back panel`

    <img src="./images/assembly 3.JPG" width="300"/>

1. Insert the `lithophane` into the `main body`

    <img src="./images/assembly 5.JPG" width="300"/>
    <img src="./images/assembly 6.JPG" width="300"/>

1. Fit the `back panel` and `main body` together

    <img src="./images/assembly 7.JPG" width="300"/>
    <img src="./images/assembly 8.JPG" width="300"/>

1. Light up the light box with a USB-C charging cable (for some reason apple chargers don't work. try using a power bank)

    <img src="./images/assembly 9.JPG" width="300"/>
    <img src="./images/assembly 10.JPG" width="300"/>


# Future Ideas
- Create a battery-powered version instead

# More
- Printables: https://printables.com/@SiahYeeLong_2539073
- Thingiverse: https://thingiverse.com/syeelong/
- Makerworld: https://makerworld.com/en/@yeelong
- GitHub: https://github.com/siahyeelong/3D-Printing-Projects
- LinkedIn: https://linkedin.com/in/siahyeelong/
