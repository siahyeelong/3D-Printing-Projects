# Overview
This is a modular rugged-style (but not really rugged) parametric latching box that I designed on Onshape. Details on how you can customise your own is listed in [Usage](#usage) 

![image](./images/assembly%204.JPG)

## Objective
3D printing has its limitations when it comes to structural integrity and tolerances. When using hardware in 3D prints, the tolerances you create in your model may depend on which printer and filament you're using. 

When 3D printing rugged boxes with hinges, I realise that the hinges tend to break easily, rendering the entire box useless. To solve this issue, I have made the parts interacting with hardware replaceable, making it modular for different hole sizes if you wanted to. This hopefully reduces the amount of filament wasted from failed prints.

The hinges and latches snap into place, allowing you to switch it out if you find the tolerances undesirable, or if the hinges break due to accessive use.

## Features
1. Replaceable hinge (snap in place)
1. Replaceable latch (snap in place)
1. Replaceable handle (optional)
1. Customised configurations in CAD Model
## CAD Model
My model can be found on [Onshape](https://cad.onshape.com/documents/bd7db400960aa689bd6e2ede/w/8cfd940abfba4c5b97c73ec7/e/d102f4b55f71ee6b03289167?configuration=Bottom_Internal_Height%3D0.08%2Bmeter%3BBox_Internal_Breadth%3D0.112%2Bmeter%3BBox_Internal_Length%3D0.16%2Bmeter%3BHandle%3Dtrue%3BHandle_Length%3D0.1%2Bmeter%3BHandle_Thickness%3D0.015%2Bmeter%3BScrew_Length__stalk_only_%3D0.03%2Bmeter%3BScrew_Size__Diameter_%3D0.004%2Bmeter%3BTop_Internal_Height%3D0.03%2Bmeter%3BWall_Thickness%3D0.003%2Bmeter&renderMode=0&uiState=67186d30c2140f176d8c0c65)
> Feel free to edit and remix the model to your liking
# Usage
## 1. Opening the model on Onshape
Open the public model [here](https://cad.onshape.com/documents/bd7db400960aa689bd6e2ede/w/8cfd940abfba4c5b97c73ec7/e/d102f4b55f71ee6b03289167?configuration=Bottom_Internal_Height%3D0.08%2Bmeter%3BBox_Internal_Breadth%3D0.112%2Bmeter%3BBox_Internal_Length%3D0.16%2Bmeter%3BHandle%3Dtrue%3BHandle_Length%3D0.1%2Bmeter%3BHandle_Thickness%3D0.015%2Bmeter%3BScrew_Length__stalk_only_%3D0.03%2Bmeter%3BScrew_Size__Diameter_%3D0.004%2Bmeter%3BTop_Internal_Height%3D0.03%2Bmeter%3BWall_Thickness%3D0.003%2Bmeter&renderMode=0&uiState=67186d30c2140f176d8c0c65).

![image](./images/open%20model.png)

## 2. Editing the configurations to suit your needs
On the Configurations panel on the left, edit the configurations of the box according to your needs. You may choose to disable the handle if you just want a plain box.

<img src="./images/edit config.png" width="200"/>

## 3. Exporting the model
Once you are satisfied with the model, click on the download button on the bottom
![image](./images/exporting%201.png)

Export your model as a .STEP or .stl file to be sliced
![image](./images/exporting%202.png)

## 4. Assembly

### Step 1
Once you have printed the parts according to the recommended slicer settings, proceed to slide and lock in the hinges and latches part into the main box component. The fit is designed to be firm to maintain some structural strength to the box.

<img src="./images/assembly 1.1.JPG" width="300"/><img src="./images/assembly 1.2.JPG" width="300"/><img src="./images/assembly 1.3.JPG" width="300"/>

### Step 2
Screw in the necessary hardware where required

<img src="./images/assembly 2.1.JPG" width="300"/><img src="./images/assembly 2.2.JPG" width="300"/>

### Step 3
For handles, insert the handle first, then slide the locking piece in. Rotate the locking piece once fully inserted till it touches the end of the track. Pull the locking piece up with a screwdriver to firmly lock it in place.

<img src="./images/assembly 3.1.JPG" width="300"/><img src="./images/assembly 3.2.JPG" width="300"/><img src="./images/assembly 3.3.JPG" width="300"/>

### Step 4
Done! Now, close the box, ensure that the hinge isn't too tight, and ensure that the latch clicks into place.

<img src="./images/assembly 4.JPG" width="400"/>

# Future Ideas
1. Slimmer hinge options
1. Stackable design
1. Compatible with smaller sizes
1. Customisable number of latches and hinges

# Print Settings
- Material: PLA / PETG
- Print settings: 
    - Walls: 2
    - Infill: Gyroid 10%
    - Top Layers: 4
    - Bottom Layers: 4
    - Supports: 
        - Handle and hinges: Yes, on build plate only
        - Every other part: No

# More
- Printables: https://printables.com/@SiahYeeLong_2539073
- Thingiverse: https://thingiverse.com/syeelong/
- Makerworld: https://makerworld.com/en/@yeelong
- GitHub: https://github.com/siahyeelong/3D-Printing-Projects
- LinkedIn: https://linkedin.com/in/siahyeelong/
