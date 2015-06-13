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

## License  Modified BSD (2-Clause)
Copyright (c) 2010-2011 VCAD System Research Program, RIKEN. All rights reserved.  
Copyright (c) 2012-2015 Advanced Institute for Computational Science, RIKEN. All rights reserved.  
Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:
- Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
- Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
