Original file is from this site https://www.printables.com/model/854118-orca-ender-3-s1-thumbnail-generator/files and https://community.ultimaker.com/topic/44667-no-thumbnail-on-creality-3-vs2/#comment-330593

It need to be set up correctly and the script will generate JPG 300x300 thumbnail automaticaly when exporting the G-CODE.

Origin script have set up image size 200x200 but this size is not working for Ender 3 S1 Pro, so i fix it and now its working properly for S1 Pro.

How to install?

1)Download Script

2)Download and install python

3)Download and install Pillow

4)Put script into C:\Users\[your_name]\AppData\Roaming\OrcaSlicer

5)Set up post processing in OcuraSlicer and put path to python.exe and thumbnailgen.py

<img width="404" height="213" alt="image" src="https://github.com/user-attachments/assets/10e97ca3-935e-41a4-8b13-46c862fd9ebd" />

6)Set printer settings with these paramets:

<img width="679" height="173" alt="image" src="https://github.com/user-attachments/assets/a0d1ca91-317b-41dc-95d3-ae91b91c2029" />

Its important to set up this paramets correctly as shown picture:

*Druh G-kódu/G-CODE - Marlin 2 - It works only if you have Marlin 2

*Náhledy G-kódu/Thumbnail G-code - 300x300/JPG

7)Save everything and you can start slicing, thumbnail will be in supported g-code format and will be shown in printers LCD screen with printing time and fillament use.


*Tested on OcuraSlicer 2.3.1

*Be sure you have latest firmware from creality https://www.crealitycloud.com/downloads/firmware/ender-series/ender-3-s1-pro - Tested with Ender-3 S1_Pro_HWv24S1_301_SWV2.0.8.28F4_F401_FDM_LASER

USE AT YOUR OWN RISK
