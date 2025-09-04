1. All software dependencies and operating systems (including version numbers)  
Operating systems: Windows 10 Home Chinese Version  
Software dependencies:   
Pycharm Community Edition 2021.3.2, Python 3.10, Keil uVision5, Lichuang EDA Professional Edition. 

2. Versions the software has been tested on Windows 10 Home Chinese Version

3. Any required non-standard hardware  
The hardware circuits in Multi-channel EMG circui (MCU main control Board).zip and Multi-channel EMG circuit (AD1298 front end).zip are required.

4. Installation guide  
Lichuang EDA Professional Edition run on https://pro.lceda.cn/editor.  
Pycharm Community Edition 2021.3.2 download on https://blog.jetbrains.com/pycharm/2022/01/2021-3-2/, and Install by default steps.  
Keil uVision5 download on https://www.keil.com/demo/eval/c51.htm, and Install by default steps.  
Python 3.10 download on https://www.python.org/, and Install by default steps.  

5. Expected output of STM32F103C8-ADS1298-Bluetooth.zip: If the code of STM32F103C8-ADS1298-Bluetooth.zip is burned into Multi-channel EMG circui (MCU main control Board).zip, the hardware circuit will transmit 8-channel differential signals to the server in real time.
Expected run time for demo on a "normal" destop computer Within one minute.
Expected output of MLP-Test.zip: The code in MLP-Test.zip implements the evaluation of the accuracy rate of action recognition for human-computer interaction signals.

6. How to run the software on your data:  
The software STM32F103C8-ADS1298-Bluetooth.zip is used to obtain 8-channel differential signals.
Selecting the data of Fig. S26 and Fig. S28 in the source data File-SI-1(Fig-S1-42). xlsx on  https://www.scidb.cn/en/s/QBr2Af and building the training set and test  set to run the MLP-Test.zip.It should be noted that the quantity of input data and the number of labels correspond to the samples.
