# Affine-Transformation-based-Path-Generation-Method-for-Supportless-Rotary-3D-Printing

## 1. Repository description
 This GitHub repository is the supplementary material for the article "Affine-Transformation-based-Path-Generation-Method-for-Supportless-Rotary-3D-Printing".
 
 This repository consists of six folders, encompassing all relevant materials involved in the conduct of this research work.
 
## 2. Folder description
| Folder index |                                                    Folder description                                                    |
| ------------ | ------------------------------------------------------------------------------------------------------------------------ |
| 01           | **Folder 01** provides the original STL model, which has not undergone affine transformation.                            |
| 02           | **Folder 02** provides the STL model after affine transformation.                                                        |
| 03           | **Folder 03** provides the generated GCode print files.                                                                  |
| 04           | **Folder 04** provides a python script file for material compensation, and the specific usage method is described below. |
| 05           | **Folder 05** provides screenshots of software parameters used in research work.                                         |
| 06           | **Folder 06** provides videos captured during the printing process of affine-transformed models in research work.      |
| 07           | **Folder 07** provides relevant software involved in research work, and the specific usage method is described below.    |
                                                                                   
## 3. Usage description
 ### 3.1 Instructions for using the material compensation script
  This script software is developed based on the Python language and has been compiled and passed through **the Python 3.13.0 interpreter**. The script file is located in **folder 04**.
  
**Usage:** Command console mode of Windows system.

 Ensure that Python version 3.13 has been installed. Enter the following script command in the console:
 ```
 python .\python-script-material-compensation.py
 ```
 Just follow the prompts. Here is the script operation process:
 ```
Step1: Setting GCode files
        input the GCode file name:  input.gcode
        input the output GCode file name:output.gcode  
Step2: Material compensation begin...
Step2: Material compensation finish!
 ```
 
### 3.2  Instructions for using model affine transformation software
This software is developed in C++language, using Qt as the GUI development framework, and compiled through VS2019. The compiled software is compressed into **"Rotary3D.EE202507. zip"**, which is located in **folder 07**. Extract the compressed file, find the executable file: **Robo3D.exe**, double-click to run the software.
**Usage:** On Windows 10 or above operating systems, the desktop application Rotary3D.exe can be run by double clicking directly.

* Step1: Set rotary bed
    * The diameter and length of the cylindrical bed can be configured.
* Step2: Input the STL file
* Step3: Affine transformation
* Step4: Affine-transformed model file output


### 3.3 ModelLightV3 software
This software is a model processing software provided by HORI  3D printing company. The installation package is **"Modellight_Setup_V3053.rar"**, and the compressed file is located in **folder 07**.Extract the compressed file, find the executable file: **Modellight_Setup_V3053.exe**.
**Usage:** On Windows 10 or above operating systems, desktop application Modellight_Setup_V3053.exe can simply double-click to install this model process software..

According to the software instructions and the parameters provided in **folder 06**, a printed GCode file can be generated.