# V-Isio

## Outline
V-Isio is a standalone application to visualize data on structured grid systems. This application is developed to support several PC environments, MacOSX, Linux, and Windows. Functoins provided are mainly desinged to depict thermal fluid simulation data, especially for FFV-C simulator. V-Isio can handle relatively large dataset owing to its efficient data structure and FFV-C's parallel distributed files, which are managed by dfi meta-data file. 

## Software requirement
- GNUplot    If users want to use graph plot functions

## Install
- Linux  
`$ install -Uvh Visio_xxx.arch.rpm`  
V-Isio is installed under /usr/local/Vtools/bin.

- Windows  
The installe package is provided. Run the program file `Visio_xxx.msi`  
You can lauch V-Isio from START MENU of your Windows system.

- MacOSX  
The installer is provided by pkg format. Double clicking `Visio_xxx.pkg` will start installation process.  
V-Isio is installed at `/Application/Vtools`  
Please add command search path as follows:  
`/Applications/Vtools/Visio.app/Contents/MacOS:/Applications/Vtools/bin`  

