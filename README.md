# DAC 2020 Design Contest

# Note:
These files are still under development.  They should be stable by the end of January.

For full contest details, please see the [2021 DAC System Design Contest](https://dac-sdc-2021.groups.et.byu.net/doku.php) page.

For general questions regarding this contest, please use the Piazza page: piazza.com/dac_2018/winterterm12021/dacsdc2021

## Setup PYNQ on your Ultra96v2 board

  * Download the Ultra96v2 board image from http://www.pynq.io/board.html
  * Follow the instructions to image the SD card at https://pynq.readthedocs.io/en/latest/getting_started/pynq_image.html.  
  * Follow the instructions to setup and connect to the board at https://ultra96-pynq.readthedocs.io/en/latest/getting_started.html.

## Usage
The get started, users have to run the following command on the Ultra96 board:

```shell
cd /home/xilinx/jupyter_notebooks
sudo git clone https://github.com/jgoeders/dac_sdc_2021.git
```
Remember the user name and password are both `xilinx` for super user.

After the above step is completed successfully, you will see a folder `dac_sdc_2021` under your 
jupyter notebook dashboard.  Open the `sample_team/dac_sdc.ipynb` notebook for directions on where to begin.

## Folder Structure

1. sample_team: This folder contains files for a sample team.  This includes a <teamname>.bit and <teamname>.tcl file that defines the hardware, and a `.ipynb` jupyter notebook, and a `hw` folder that is used to create a Vivado project.

2. images: All the test images are stored in this folder.

3. result: The results contain the output xml produced when execution is complete, and contains the runtime, energy usage, and predicted location of each object in each image.


