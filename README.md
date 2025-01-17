# Grovr Vision AI Module

## What it is

Grove Vision AI Module contains camera (OV2640) and two microcontrollers.

- **Himax HX6537-A** is an ultra-low power, high performance microcontroller designed for battery-powered TinyML applications.
- ...

In addition, there are two sensors:

- Micropone
- 3D Accelerometer nad gyroscope,  6-axis Inertial Measurement Unit (IMU)

Dual 7-pin hraders are compatible XIAO series boards.

Operating Voltage 5v.

Baud rate 115200.

I2C interface.

The camera supports resolution up to 1600*1200 px, but is set to 192*192 px  due to the limitation of inference speed.

![Vision AI Module Front](img/Grove_vision_ai-01.jpg)
![Vision AI Module Back](img/Grove_vision_ai-02.jpg)

## Build Models

- [Ultralytics YOLOv5](https://ultralytics.com/yolov5)
- Github: [YOLOV5-SWIFT](https://github.com/Seeed-Studio/yolov5-swift) for AIoT hardware devices launched by Seeed
- Tutorial [Train and Deploy Your Own AI Model Into Grove - Vision AI](https://wiki.seeedstudio.com/Train-Deploy-AI-Model/)
- Tutorial [Train and Deploy Your Own AI Model Into SenseCAP A1101 & Grove - Vision AI](https://wiki.seeedstudio.com/Train-Deploy-AI-Model-A1101-Grove-Vision-AI/)
- [HIMAX Yolo-Fastest Person Detection Example For Seeed Grove Vision AI Module](https://github.com/HimaxSmartSensing/WE_I_Plus_User_Examples/tree/main/HIMAX_Yolo_Fastest_Person_Detection_Example_For_Grove_AI)

## Upload models to camera

The trained models are in the file `.uf2`

1. Connect USB-C cable and double click BOOT botton. GROVEAI will be mounted as drive.

## Arduino lib

- Github [Seeed-Grove-Vision-AI-Moudle](https://github.com/limengdu/Seeed-Grove-Vision-AI-Moudle)

## Datasheets

- [Himax HX6537-A](datasheets/Himax_HX6537-A09TDIG-1111V_Datasheet.pdf) pdf

## Links

- [Grove - Vision AI Module](https://www.seeedstudio.com/Grove-Vision-AI-Module-p-5457.html)
- [Grove-Vision-AI-Module](https://wiki.seeedstudio.com/Grove-Vision-AI-Module/) wiki
- [VisionAI Automatic Dog Treat Dispenser /wRoboflow and YOLOv5](https://www.hackster.io/satoshiii/visionai-automatic-dog-treat-dispenser-wroboflow-and-yolov5-a71fd2) Hackster.io
- [Smart Luffa Farming with LoRaWAN](https://www.hackster.io/meilily-li/smart-luffa-farming-with-lorawan-b705b0) Hackster.io


https://files.seeedstudio.com/grove_ai_vision/index.html