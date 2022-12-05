# ESMUST

This is a repository to share an outcome model of the journal paper (ESMUST: EnergyPlus-driven surrogate model for urban surface temperature prediction).

## Description

This study presents a new urban surface temperature prediction model called the EnergyPlus-driven surrogate model for urban surface temperature (ESMUST). 
ESMUST was built using artificial neural networks with 42 million entries of a synthetic dataset and thirteen input features. 
During the validation process, ESMUST achieved 0.964 percent bias and efficiently predicted the surface temperature of 3D urban models with fewer inputs.

ESMUST was built using C# coding and operated in Autodesk Revit Dynamo tool.

## Getting Started

### Dependencies

* Autodesk Revit 2022 or higher
* Windows 10
* Autodesk Dynamo version 2.10 or higher

### Installing

1) Clone the GitHub repository
2) Place the cloned folder in the Revit folder (e.g., “C:\Program Files\Autodesk\Revit 2022”)
3) Search and open ‘Edit environment variables for your account’ on the Start menu
![image](https://user-images.githubusercontent.com/85502888/205560320-78cc645e-3c92-4b0a-acb6-81625403aa3b.png)

4) Click ‘Path’ variable and click ‘Edit’ 
![image](https://user-images.githubusercontent.com/85502888/205560405-34eef661-72fc-4b76-9a47-7322cb4e16c1.png)

5) Click ‘New’ and type the cloned folder’s directory (e.g., C:\Program Files\Autodesk\Revit 2022\ESMUST).

### Executing program

1) Start the Revit program 
2) Run ‘Dynamo’ in the Manage tab of the Revit software and load the example dynamo file, named Example.dyn, in the cloned folder. 
3) Click ‘File -> Import Library’ in the Dynamo to load ESMUST model. You can find the file, ESMUST.dll, in the cloned folder (e.g., C:\Program Files\Autodesk\Revit 2022\ESMUST\ESMUST.dll)
4) Click ‘Run’ at the bottom of the Dynamo to see the surface temperature results. 

## Help

Email: wyoo@tamu.edu

## Authors

* Dr. Wonjae Yoo / Texas A&M University / wyoo@tamu.edu
* Dr. Mark J. Clayton / Texas A&M University 
* Dr. Wei Yan / Texas A&M University 

