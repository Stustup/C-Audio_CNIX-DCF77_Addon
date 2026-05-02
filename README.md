# DCF77 Addon Board for the C-Audio Nixie Clock (CNIX)
(This project was sponsored by PCBWay)

This board adds automatic time setting via a DCF77 radio to CNIX. Also temperature and humidity readings are possible with a HTU21 sensor from TE Connectivity which can be read via I2C and viewed via the first submenu on the clock (instead of the manual time setting). The antenna is hold in place with cable ties.

<img src="./Hardware/doc/CNIX Addon 3D View.png" alt="3D view of the board without the clock" style="max-width: 100%; height: auto;">

The breakout pins are still accessable, as well as the I2C breakout, which can be used with a display while debugging.   

<img src="./Hardware/doc/CNIX Addon combined 3D.png" alt="3D view of the all three boards of CNIX" style="max-width: 48%; height: auto;"> <img src="./Hardware/doc/Real world picture.JPG" alt="Real world picture of the board with attached antenna" style="max-width: 48%; height: auto;"> 

The code to communicate with the modules remains on the main control PCB, which you can find [here](https://github.com/Stustup/C-Nixie_CNIX). This board uses the integrated ID system of CNIX via pins D2 and D3 and has the adress 0x0 (first addon board).

The addon board was sponsored by PCBWay. As always, their service was amazing and the facbrication as well as the shipping was fast. Because of the all-in-one customs and shipping price the handling of taxes and other fees was very easy.
I highly recommend their services if you want to build this PCB. [Click here](https://www.pcbway.com/orderonline.aspx) to get to the order form if you want to order this or any other PCBs.
