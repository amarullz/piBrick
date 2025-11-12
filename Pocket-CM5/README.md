**piBrick Pocket-CM5** is a smartphone-sized handheld PC powered by the **Raspberry Pi CM5**, featuring a 3.91" AMOLED touch display and a QWERTY keyboard+trackpad from **BBQ20**.

This pocket computer is compact enough for mobile use, yet powerful and versatile for everyday computing. With its wide range of ports, it can be connected to a desktop setup and used as a full desktop computer.

![3D_pibrick-pocket-cm5_2025-11-11.png](https://image.easyeda.com/oshwhub/pullImage/02d73aa0625249bda34067aa7e459123.png)

**piBrick Pocket-CM5** is an Open Source Hardware.

**piBrick Pocket-CM5** is a great tool for engineers, sysadmins, and hackers.
The built-in QWERTY keyboard can function as an external USB keyboard and mouse — simply plug it into another computer or server and use it as a USB-HID device.
It runs a full Linux desktop with unlimited system administration and hacking tools, making it a compact yet complete on-site tool for your work.

There are many possible use cases for this device. It’s a building block — your creativity is the only limit.

This device was designed for manufacturing at JLCPCB, including component selection, design rules, and overall manufacturability. Anyone can easily order and assemble it through JLCPCB.

# Specifications:
- CORE: **Raspberry Pi CM5**
- Dimensions: **179 × 146 × 16 mm**
- Display: **3.91" AMOLED touchscreen — MIPI/DSI, 1080×1240 @ 60 Hz, 16M colors**
- Display Output: **Full-size HDMI + micro-HDMI**
- **USB:**
  - 1× USB 3 Type-A
  - 1× USB 3 Type-C
  - 1× USB 2 Type-C
  - 1× USB 2 Type-A
  - 1x USB 2 for Internal Add On
- Battery: **5000mAh LiPo Battery**
- **HID:**
  - BBQ20 QWERTY keyboard with integrated trackpad as mouse
  - Side rotary encoders with push switch
  - 5x Side User Buttons
- **Audio:**
  - Internal Sound Card with Amplifier
  - Internal Stereo speaker
  - Microphone from BBQ20 Keyboard
  - 3.5mm audio jack for headphone
- Accelerometer sensor
- Front camera (Raspberry Pi MIPI/CSI camera)
- **Storage**
  - Internal CM5 eMMC or Micro SD
  - M.2 NVMe Connector for SSD
- **Expansion Connector**
  - Internal USB 2.0
  - I2C Connector
  - GPIO Extension Connector
- User RGB LED, and Keyboard Layout RGB Indicator
- Body: **Open Source 3D printable frame & casing**

# Reproducable
The main PCB and Flex-PCB are easily reproducible at JLCPCB. You can open the project in EasyEDA Pro and simply click Order PCB. Everything is already configured for JLCPCB — you only need to adjust anything you feel is necessary.

**Here are some optional tips for ordering:**

- Make sure you use the default JLCPCB stack-up: JLC04161H-7628 (or just leave Specify Stackup set to No).
- The board already includes a 5×5 mm rectangular silkscreen area for the JLCPCB 2D barcode. Choose 2D Barcode (Serial Number), select 5×5 mm size, and Specify Position.
- All components are compatible with Economic Assembly. Extended parts cost slightly more but are still cheaper than Standard.
- For better cost efficiency, it’s recommended to order 10 pcs. Group-ordering for multiple people is often the most affordable approach.

# Project on EasyEda Pro
- For the best PCB and schematic appearance, please install the **Roboto Condensed** and **Roboto Condensed Bold** fonts first.
- You may modify and reproduce the design as you like, but please keep the license intact.
- Always follow the design rules and run DRC checks before manufacturing.


# Additional Peripherals
- **Mandatory**
  - Raspberry Pi CM5 (Lite or with eMMC) — Wireless version is recommended  
    (Active or passive heatsink also required)  
    https://www.raspberrypi.com/products/compute-module-5/?variant=cm5-104032
  - BlackBerry Q20 keyboard (find from online stores)
  - LiPo battery 5000 mAh with JST-2.0 mm connector
  - 3.92" AMOLED display with touchscreen from DXQ  
    https://dxq-lcd.com/products/1080x1240-3-92-inch-amoled-display
- **Optional**
  - Raspberry Pi Zero Camera  
    https://www.waveshare.com/rpi-zero-v1.3-camera.htm
  - NVMe SSD (size **2230** or **2242**)

# Updates
- October Update: https://amarullz.com/2025/10/22/pibrick-development-update-october/

# Links
- My Github: https://github.com/amarullz/
- Kernels & Tools: https://github.com/amarullz/piBrick_Display
- OSHWLab: https://oshwlab.com/amarullz/pibrick-pocketcm5