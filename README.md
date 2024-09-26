# V-Isio

## Outline
V-Isio is a standalone application to visualize data on structured grid systems. This application is developed to support several PC environments, MacOSX, Linux, and Windows. Functoins provided are mainly desinged to depict thermal fluid simulation data, especially for FFV-C simulator. V-Isio can handle relatively large dataset owing to its efficient data structure and FFV-C's result files with a meta-data dfi file, which allows us to manage parallel distributed files directly.

## Software requirement
- GNUplot
If users want to use graph plot functions.

## Install
- Linux
	- RHEL/CentOS/Rocky/Alma
  ```
  $ sudo dnf install -y libxml2 wxBase3 wxGTK3 glew libGLEW
  $ sudo dnf install ./Visio_xxx.arch.rpm
  ```
	- Ubuntu22
  ```
  $ sudo apt install -y libxml2 libwxgtk3.0-gtk3 libglew libgle3
  $ sudo apt install ./v-isio_2.4.9-x_ubuntu22_amd64.deb
  ```

  V-Isio is installed under /usr/local/Vtools/bin.

- Windows
The installe package is provided. Run the program file `Visio_xxx_setup.exe`
You can lauch V-Isio from START MENU of your Windows system.<br>
<i>Notice: v2.4.10+: volren method does not work on Windows. Use shaderVolren instead.</i>

- MacOSX
The installer is provided by pkg format. Double clicking `Visio_xxx.pkg` will start installation process.<br/>
V-Isio is installed at `/Application/Vtools`
Please add command search path as follows:
`/Applications/Vtools/Visio.app/Contents/MacOS:/Applications/Vtools/bin`

## Contributors
- Kenji Ono  _ono.kenji.693@m.kyushu-u.ac.jp_
- Hiroyuki Yoshikawa  _yoh@fujitsu.com_

