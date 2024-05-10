# WaveShare XCore407I board

STM32Cube project files 

## Prerequisites

Software:  
 
STM32CubeIDE for coding  
https://www.st.com/en/development-tools/stm32cubeide.html

STM32CubeProgrammer for programming  
https://www.st.com/en/development-tools/stm32cubeprog.html

Hardware:  

XCore407I board  
https://www.waveshare.com/wiki/XCore407I


## Usage

Download the whole project as a zip file  
or  
use this git command  
```  
git clone https://github.com/vik1228/XCore407I.git
```
Simple steps to build project and program board 

- Open the project with STM32CubeIDE  
- If you want modify the source code  
- Build the project ( Project / Build Project )  
- Binary files are created into Debug folder   
- Run STM32CubeProgrammer  
- Set BOOT CONFIG switch to SYSTEM position on XCore407I board  
- Set power selector switch into USB5V_FS position  
- Now plug your USB cable into USB_FS connector ( and into your PC )  
- In STM32CubeProgrammer select USB from the menu on the right  
- Click the refresh button and click the Connect button  
- Target information will appears (data about the STM32 MCU)  
- Click on the '+' icon and select Open file  
- Navigate into Debug folder and select XCore407I.elf file to open  
- One click onto Download button and the microcontroller will be programmed  
- Click onto Disconnect button and switch BOOT CONFIG to FLASH position  
- Reset or unplug-plug USB cable  
- Now the application is running  
- Connect 470 Ohm resistor and LED to the PI6 pin  
- LED is blinking  
