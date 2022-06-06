# ESP8266 Deauther Version 2

<p align="center">
  <img alt="PICTURE logo" src="https://raw.githubusercontent.com/wiki/spacehuhn/esp8266_deauther/img/deauther_logo.png" width="200">
  <br>
  <b>Scan for WiFi devices, block selected connections, create dozens of networks and confuse WiFi scanners!</b>
  <br>
  <br>
</p>

## Difference to Version 3

[Version 3](https://github.com/SpacehuhnTech/esp8266_deauther/tree/v3) is in development. It is stable to use, but it is very different.  
It is command line based, which allows it to offer not just more features, but make them more customizable.  

| Feature | Version 2 | Version 3 |
| ------- | --------- | --------- |
| Web Interface | ✅ | |
| Display support | ✅ | |
| Serial Command Line | ✅ | ✅ |
| Scanner | ✅ | ✅ |
| Deauth attack | ✅ | ✅ |
| Beacon attack | ✅ | ✅ |
| Probe attack | ✅ | ✅ |
| [Huhnitor](https://github.com/spacehuhntech/huhnitor) support | | ✅ |
| Signal strength scanner | | ✅ |
| Authentication scanner | | ✅ |
| Rogue AP | | ✅ |

## Installation

Please refer to the [installation guide in this wiki](https://github.com/spacehuhntech/esp8266_deauther/wiki/Installation).  
If you're just looking for the .bin files, go to [releases](https://github.com/spacehuhn/esp8266_deauther/releases).  

## About this project
This software allows you to easily perform a variety of actions to test 802.11 wireless networks by using an inexpensive ESP8266 WiFi SoC (System On A Chip).  

The main feature, the deauthentication attack, is used to disconnect devices from their WiFi network.  
No one seems to care about this huge vulnerability in the official 802.11 WiFi standard, so I took action and enabled everyone who has less than 10 USD to spare to recreate this project.  
I hope it raises more attention on the issue. In 2009 the WiFi Alliance actually fixed the problem (see [802.11w](https://en.wikipedia.org/wiki/IEEE_802.11w-2009)), but only a few companies implemented it into their devices and software.  
To effectively prevent a deauthentication attack, both client and access point must support the 802.11w standard with protected management frames (PMF).  
While most client devices seem to support it when the access point forces it, basically no WiFi access point has it enabled.  

Feel free to test your hardware out, annoy these companies with the problem, share this project and push for a fix!
This project is also a great way to learn more about WiFi, micro controllers, Arduino, hacking and electronics/programming in general.  
**But please use this tool responsibly and do not use it against others without their permission!**

## WiFi Jammer

Many refer to this project as a WiFi jammer. This is problematic, because this firmware is **not** turning your ESP8266 into a radio or frequency jammer. But this is how most people imagine it without further explaination.  

So if you like to learn more about the difference, we made a whole video about it:  
[![Deauther or Jammer: What's the difference?](https://img.youtube.com/vi/gOyfD44A7rE/0.jpg)](https://www.youtube.com/watch?v=gOyfD44A7rE)

## Supported Development Boards

This firmware can run on any **ESP8266**, not however on the ESP32!  
The most popular development boards, the `NodeMCU` and `Wemos d1 mini`, work great for this project.  

If you like to support our work, you can buy get a boards made with this project in mind.  
They come preflashed with the firmware, so you can start right away.  

 

## Disclaimer

This project is a proof of concept for testing and educational purposes.  
Neither the ESP8266, nor its SDK was meant or built for such purposes. Bugs can occur!  

Use it only against your own networks and devices!  
Please check the legal regulations in your country before using it.  
We don't take any responsibility for what you do with this program.  




