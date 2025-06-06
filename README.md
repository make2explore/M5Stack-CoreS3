# M5Stack-CoreS3
Device overview and Getting Started with M5Stack's Core S3 Dev Kit  

<img src="/Images/CoreS3-1.jpg" height="200"> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; <img src="/Images/CoreS3-2.jpg" height="200" > &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; <img src="/Images/CoreS3-3.jpg" height="200" > 
  
**M5Stack CoreS3** is the third-generation main unit of the M5Stack development kit series. Its core controller uses the ESP32-S3 solution, featuring a dual-core Xtensa LX7 processor with a main frequency of 240MHz. It comes with WiFi functionality, onboard 16M Flash and 8M-PSRAM, and supports program downloading via the TYPE-C interface. It also supports OTG and CDC functions, making it easy to connect USB devices and flash firmware. The front side is equipped with a 2.0-inch capacitive touch IPS screen, with the panel made of high-strength glass. Below the screen is a built-in 0.3MP camera GC0308, along with a proximity sensor LTR-553ALS-WA. The power section uses the AXP2101 power management chip and a 4-way power flow control circuit, designed with low power consumption in mind. The board includes a six-axis motion sensor BMI270 and a magnetometer BMM150, a TF-card (microSD) slot, and a BM8563 RTC chip, providing precise timing and sleep-timer wake-up functions. For sound output, it uses a high-fidelity 16-bit I2S amplifier chip AW88298, with a built-in 1W speaker. For sound input, it uses the ES7210 audio decoding chip with dual microphone input. On the side of the device, there are independent power and reset (RST) buttons, with a built-in delay circuit. Holding the reset button for a long time will enter the program download mode. The CoreS3 kit comes with a DinBase base by default, making it easy to mount on DIN rails, walls, or screw-fixed installations. It can be powered by an external DC 12V (supports 9-24V) or an internal 500mAh lithium battery. The DinBase has multiple proto positions reserved for user DIY. This product is suitable for IoT development, various DIY projects, smart home control systems, and industrial automation control systems.
  
**M5Stack CoreS3** is a compact, powerful IoT development kit based on the ESP32-S3 dual-core processor, ideal for AI, edge computing, and smart device prototyping. It features a 2-inch capacitive touch IPS display, 16MB flash, 8MB PSRAM, built-in camera, dual microphones, speaker, and multiple sensors including IMU, magnetometer, and proximity sensor. With support for Wi-Fi, USB-C OTG, MicroSD, and Grove/M-Bus expansion, it's programmable via Arduino, MicroPython, or UIFlow, making it a versatile all-in-one solution for embedded and AIoT applications.
  
  
## Documentation

Refer the [Documentation website](http://docs.m5stack.com/en/core/CoreS3) for more information.  

**Hardware**
- [CoreS3](http://docs.m5stack.com/en/core/CoreS3)  
  
**Software**
- Arduino  
    [CoreS3 Arduino IDE Tutorial](http://docs.m5stack.com/en/arduino/arduino_ide)  
    [CoreS3 Arduino Library](https://github.com/m5stack/M5CoreS3)  
    [CoreS3 User Demo](https://github.com/m5stack/CoreS3-UserDemo/tree/main/firmware)  
  
- PlatformIO  
    [CoreS3 User Demo](https://github.com/m5stack/CoreS3-UserDemo/tree/main/firmware)  
  
- ESP-IDF  
    [Espressif's Board Support Packages - CoreS3](https://github.com/espressif/esp-bsp/tree/master/bsp/m5stack_core_s3)  
    [CoreS3 ESP-IDF BSP Tutorial](http://docs.m5stack.com/en/esp_idf/m5cores3/bsp)  
  
- Graphical Programming  
    CoreS3 Quick Start Guide  
    [UiFlow2](http://docs.m5stack.com/en/uiflow2/uiflow_web)  
    
- Home Assistant  
    This tutorial will introduce you to how to connect CoreS3 to Home Assistant  
    [Home Assistant Tutorial](http://docs.m5stack.com/en/guide/homeassistant/m5cores3/m5cores3_quick_start)  
    
- Other Quick Start Guides  
    [CoreS3 OpenAI Voice Assistant](http://docs.m5stack.com/en/guide/realtime/openai/m5cores3)   
    [CoreS3 XiaoZhi Voice Assistant](http://docs.m5stack.com/en/guide/realtime/xiaozhi/m5cores3)  
    [CoreS3 Restore Factory Firmware](http://docs.m5stack.com/en/guide/restore_factory/m5cores3)  
    

------------------------------------------------------------------------------------------------------

📕 **YouTube Video Links**  

▶️  This Dev Kit Can See, Hear, and Think 🤖 🔗 https://youtube.com/shorts/   
  
▶️  Voice, Vision, and Motion – CoreS3's Superpowers! 🔗  https://youtube.com/shorts/  

-------------------------------------------------------------------------------------------------------
📒 **Important Links**  
 
🌐 M5Stack - 🔗 https://docs.m5stack.com  
📒 CoreS3 🔗 https://docs.m5stack.com/en/core/Cardputer%20V1.1  
📙 CoreS3 Purchase 🔗 https://shop.m5stack.com/products/m5stack-cardputer-with-m5stamps3-v1-1  
⚙️ UIFLow2 Web IDE Docs🔗 https://docs.m5stack.com/en/uiflow2/cardputer/program  
⚙️ Arduino IDE Docs 🔗 https://docs.m5stack.com/en/arduino/arduino_ide  
📘 UIFLow2 Web IDE - 🔗 https://uiflow2.m5stack.com/  

🧰 Hardware  
--   [CoreS3-Store]  🔗 https://shop.m5stack.com/products/m5stack-cardputer-with-m5stamps3-v1-1  
--   [Sensors]  🔗https://shop.m5stack.com/collections/m5-sensor  

------------------------------------------------------------------------------------------------------

📜 Source Code, Circuit Diagrams and Documentation : 

🌐 GitHub Repository - 🔗 https://github.com/make2explore/M5Stack-CoreS3   
  
🌐 Hackster Blog - 🔗 https://www.hackster.io/make2explore  
  
🌐 Instructable Blog - 🔗 https://www.instructables.com/make2explore  
  

------------------------------------------------------------------------------------------  

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
