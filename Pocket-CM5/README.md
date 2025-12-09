# piBrick Pocket-CM5

**piBrick Pocket-CM5** is a smartphone-sized handheld PC powered by the **Raspberry Pi CM5**, featuring a 3.91" AMOLED touch display and a QWERTY keyboard+trackpad from **BBQ20**.

This pocket computer is compact enough for mobile use, yet powerful and versatile for everyday computing. With its wide range of ports, it can be connected to a desktop setup and used as a full desktop computer.

![piBrick Pocket-CM5 Photo](docs/images/cover.jpeg)

**piBrick Pocket-CM5** is an Open Source Hardware.

**piBrick Pocket-CM5** is a great tool for engineers, sysadmins, and hackers.
The built-in QWERTY keyboard can function as an external USB keyboard and mouse — simply plug it into another computer or server and use it as a USB-HID device.
It runs a full Linux desktop with unlimited system administration and hacking tools, making it a compact yet complete on-site tool for your work.

There are many possible use cases for this device. It’s a building block — your creativity is the only limit.

This device was designed for manufacturing at JLCPCB, including component selection, design rules, and overall manufacturability. Anyone can easily order and assemble it through JLCPCB.

![piBrick Pocket-CM5 3D Render](docs/images/piBrick-3d-showcase.png)

# Specifications:
- CORE: **Raspberry Pi CM5**
- Dimensions: **80 × 145 × 19.6 mm**
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
- 🛟 piBrick Discord: https://discord.gg/57g8bzGu
- 🤖 My Github: https://github.com/amarullz/
- 🤖 piBrick Github: https://github.com/amarullz/piBrick
- 🔬 OSHWLab: https://oshwlab.com/amarullz/pibrick-pocketcm5
- 📺 Youtube: https://www.youtube.com/@amarullz
- 💝 Donation: https://paypal.me/amarullz

# Sponsored By
Thanks **OSHWLAB** Starts to make this project possible, **EasyEDA Pro** is rocks, and **JLCPCB** integration with EasyEda is awesome.

![piBrick Pocket-CM5 3D Render](docs/images/sponsors.png)
- OSHWLab: https://oshwlab.com/
- EasyEDA: https://easyeda.com/
- JLCPCB: https://jlcpcb.com/

# Mainboard Images

|  |  |  |
| --- | --- | --- |
| ![3d.png](https://image.easyeda.com/oshwhub/pullImage/7e793ed75c7044499532597f0de5bbb1.png) | ![main.png](https://image.easyeda.com/oshwhub/pullImage/fa229f3cc93b43e89b13f3abfab4aaaa.png) | ![face.png](https://image.easyeda.com/oshwhub/pullImage/3de887416d8f4eee9d05e6f8df5c5675.png) |
| ![copper-face.png](https://image.easyeda.com/oshwhub/pullImage/37ceceec44a54765bc5cfe82b846644d.png) | ![copper-main.png](https://image.easyeda.com/oshwhub/pullImage/cac3c1eaf0e24e729af3fb7c2e8b9f9d.png) |

# 3D Design

|  |  |  |
| --- | --- | --- |
| ![image1.png](https://image.easyeda.com/oshwhub/pullImage/37567d092c0c4ae9ac784ee84d8ab459.png) | ![image6.png](https://image.easyeda.com/oshwhub/pullImage/7729f6cbf3634d6fb6df91c9ef6769c0.png) | ![image2.png](https://image.easyeda.com/oshwhub/pullImage/89d144ab1340497d9e7c681092c1a168.png) |
| ![image3.png](https://image.easyeda.com/oshwhub/pullImage/c8b4134e7b7743e3a80cfed49683a039.png) | ![image5.png](https://image.easyeda.com/oshwhub/pullImage/0bde6a1de58e4a83b79775a77298d9f4.png) | ![image4.png](https://image.easyeda.com/oshwhub/pullImage/54cc8320537549e89cd78bb4a314ee70.png) |



# Photos
|  |  |  |
| --- | --- | --- |
| ![one.jpg](https://image.easyeda.com/oshwhub/pullImage/cb9a4c0a9b6d4f439f300fc9e96726ee.jpg) | ![pcbs.jpg](https://image.easyeda.com/oshwhub/pullImage/1ac5eb8104ae49dab25f1f33613c8e50.jpg) | ![flex.jpg](https://image.easyeda.com/oshwhub/pullImage/dead45bf05624de5a9debd8fef28a139.jpg) |
| ![display.jpg](https://image.easyeda.com/oshwhub/pullImage/b2f7e4d4dc454246b4f7cd7a89a856d9.jpg) | ![backs.jpg](https://image.easyeda.com/oshwhub/pullImage/9ad0408917eb4df29fa55edcfd07ff86.jpg) | ![package.jpg](https://image.easyeda.com/oshwhub/pullImage/b40cd5b4af094a6fa5a1a37011afa28a.jpg) |
