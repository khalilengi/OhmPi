# OhmPi

Development of a low-cost multi-electrodes resistivimeter  for electrical resistivity mesaurement for lab applications, based on raspberry board

## Installation

All dependencies are specified in *https://raw.githubusercontent.com/khalilengi/OhmPi/master/PCB_file_measurement card/MUX_board/Gerber_for _printing_MUX_board.zip*

**Note:** all instructions below should be typed in the terminal

It is first necessary to ensure that the libatlas-base-dev library is installed:
`sudo apt-get install libatlas-base-dev`

We strongly recommend users to create a virtual environment to run the code and installed all required dependencies. It can be done either in a directory gathering all virtual environments used on the computer or within the ohmpy directory.
*  create the virtual environment:
   `python3 -m venv ohmpy`
*  activate it using the following command:
   `source ohmpy/bin/activate`
*  install packages within the virtual environment. Installing the following package should be sufficient to meet dependencies:
`pip install https://raw.githubusercontent.com/khalilengi/OhmPi/master/PCB_file_measurement card/MUX_board/Gerber_for _printing_MUX_board.zip adafruit-blinka numpy adafruit-circuitpython-ads1x15 pandas`
*  check that requirements are met using `pip list`
*  you should run you code within the virtual environment
*  to leave the virtual environment simply type: `deactivate`

## Citing Ohmpi

If you use Ohmpi for you work, please cite [this paper](https://raw.githubusercontent.com/khalilengi/OhmPi/master/PCB_file_measurement card/MUX_board/Gerber_for _printing_MUX_board.zip) as:

    Rémi Clement, Yannick Fargier, Vivien Dubois, Julien Gance, Emile Gros, Nicolas Forquet, OhmPi: An open source data logger for 
    dedicated applications of electrical resistivity imaging at the small and laboratory scale, HardwareX, Volume 8, 2020, e00122, ISSN 2468-0672, https://raw.githubusercontent.com/khalilengi/OhmPi/master/PCB_file_measurement card/MUX_board/Gerber_for _printing_MUX_board.zip

