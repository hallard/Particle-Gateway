Particle (formerly Spark) Gateway
=================================

The gateway can host several funny things like

- Socket to plug a Spark Core or Particle Photon
- Pins to connect I2C or SPI OLED 128x64
- Pins to connect 2.2" or 1.8" TFT LCD
- RFM69 or RFM12B on board module
- Lipo Battery connector for testing and move the Gateway (no charger on board)
- 3V3 On board regulator for harvesting devices if any to avoid pumping from Particle Regulator
- Data connection for any cheap ebay ASK RX receiver
- FTDI connection for those who want to debug serial or send data over real serial
- 2 x grove I2C connector to connect other I2C devices

Detailed Description
====================

Everything is documented on this dedicated [post][1]

### Schematic  
![schematic](https://raw.githubusercontent.com/hallard/Particle-Gateway/master/Particle-Gateway-sch.png)  

### Boards  
<img src="https://raw.githubusercontent.com/hallard/Particle-Gateway/master/Particle-Gateway-top.png" alt="Top" width="30%" height="30%">&nbsp;
<img src="https://raw.githubusercontent.com/hallard/Particle-Gateway/master/Particle-Gateway-bottom.png" alt="Bottom" width="30%" height="30%">&nbsp; 

You can order the PCB of this board at [OSHPARK][5]

### Assembled board

<img src="https://raw.githubusercontent.com/hallard/Particle-Gateway/master/Particle-Gateway-assembled.jpg" alt="Assembled TOP" width="30%" height="30%">&nbsp;
<img src="https://raw.githubusercontent.com/hallard/Particle-Gateway/master/Particle-Gateway-assembled-bot.jpg" alt="Assembled Bottom" width="30%" height="30%">

##License

You can do whatever you like with this design.

##Misc
See news and other projects on my [blog][2] 
 
[1]: https://hallard.me/particle-gateway/
[2]: https://hallard.me
[3]: https://github.com/thibdct/programmateur-fil-pilote-wifi/tree/master/Logiciel/remora
[4]: http://lowpowerlab.com/blog/2013/06/20/rfm69-library/
[5]: https://oshpark.com/projects/wUBgoDUV
