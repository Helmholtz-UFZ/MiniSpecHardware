
<a href="https://www.ufz.de/index.php?en=33573">
    <img src="https://github.com/user-attachments/assets/1473d383-34d8-4ce1-82cc-d16e7eddfa3b" width="400"/>
</a>

<a href="https://www.ufz.de/index.php?en=45348">
    <img src="https://github.com/user-attachments/assets/57f0a57d-9991-4641-bbf8-b070567cca83" align="right" width="220"/>
</a>

# Custom PCB to connect Hamamatsu C12880MA Mini-Spectrometer with a STM32-Nukleo Board

The custom PCB is intended for connection to a NUCLEO-L476RG (STMicroelectronics) development board. 
However, other boards may also be compatible. 

The board consists primarily of an ADC [2] and a socket for the mini spectrometer and is more or less a breakout board 
that has to be plugged onto the Nucleo board.

We provide firmware for the NUCLEO-L476RG in a separate repository [1], it drives the sensor and offers a command line interface (UART)
to control the system.     


--- 

[2] AD7671, Analog Devices Inc

[1] [https://github.com/Helmholtz-UFZ/MiniSpecHardware](https://github.com/Helmholtz-UFZ/MiniSpecFirmware)
