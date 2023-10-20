# V-Isio

## Outline
V-Isio is a standalone application to visualize data on structured grid systems. This application is developed to support several PC environments, MacOSX, Linux, and Windows. Functoins provided are mainly desinged to depict thermal fluid simulation data, especially for FFV-C simulator. V-Isio can handle relatively large dataset owing to its efficient data structure and FFV-C's result files with a meta-data dfi file, which allows us to manage parallel distributed files directly.

## Software requirement
- GNUplot
If users want to use graph plot functions.

## Install
- Linux
	- CentOS/RHEL
  ```
  $ sudo rpm -Uvh Visio_xxx.arch.rpm
  ```
	- Ubuntu22
  ```
  $ sudo apt install -y libxml2-dev libwxgtk3.0-gtk3-dev libglew-dev libgle3-dev
  $ sudo dpkg -i v-isio_2.4.9-x_ubuntu22_amd64.deb
  ```

  V-Isio is installed under /usr/local/Vtools/bin.

- Windows
The installe package is provided. Run the program file `Visio_xxx_setup.exe`
You can lauch V-Isio from START MENU of your Windows system.

- MacOSX
The installer is provided by pkg format. Double clicking `Visio_xxx.pkg` will start installation process.
V-Isio is installed at `/Application/Vtools`
Please add command search path as follows:
`/Applications/Vtools/Visio.app/Contents/MacOS:/Applications/Vtools/bin`

## Contributors
- Kenji Ono  _ono.kenji.693@m.kyushu-u.ac.jp_
- Hiroyuki Yoshikawa  _yoh@fujitsu.com_

