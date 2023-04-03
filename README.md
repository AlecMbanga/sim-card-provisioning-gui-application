# sim-card-provisioning-gui-application
This application is a Graphical User Interface for SIM card Provisioning of  sysmoUSIM-SJS1 SIM cards, it is used to program parameters of a SIM card e.g  IMSI, ICCID, KI, OP, OPC, etc. This application is a compliment to sysmo-usim-tool and pySim tools since they are being used to program SIM card parameters in the background. This application is a Linux(Ubuntu) based desktop application.
## Dependencies & Application installation

### Dependencies installation
                                      Run the following commands in Ubuntu terminal
* sudo apt-get install pcscd pcsc-tools libccid libpcsclite-dev python3-pyscard python3-serial python3-pip
* pip3 install pytlv cmd2 jsonpath-ng construct bidict gsm0338 pyyaml pycrypto
### Application installation
* Git clone https://github.com/AlecMbanga/sim-card-provisioning-gui-application.git
* Go inside the cloned folder and copy pysim and sysmo-usim-tool folders to your Home directory in Ubuntu. **IMPORTANT**: It is crucial that these two folders are placed in the HOME directory because this application references this path. Your Home directory path should be “/home/your-username/”.
* Go inside the cloned folder, you will see a debian package called "simwriting-1.0.deb". Open a terminal from this folder and execute the following command to install the application: "sudo dpkg -i simwriting-1.0.deb"
* To open the application click “Activies” on the top left corner and search “simwriting”, the application icon should appear, you can open by clicking that icon.
* For more details on how to use this application please see the documentation file inside this git folder



### The SIM writing GUI Image


![Screenshot from 2023-03-13 10-30-53](https://user-images.githubusercontent.com/49599591/229498896-c2269aed-1a9e-4736-8d03-0ce836b7652a.png)
