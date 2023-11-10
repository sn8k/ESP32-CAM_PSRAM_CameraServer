# ESP32-CAM_PSRAM_CameraServer

CamWebServer adapted for ESP32-CAM PSRAM 1.3 + OV5640 Autofocus support + OV2640 support.
this is mainly a mix between :
- CameraWebServer exemple script from arduino IDE
- OV5640 Autofocus script from ESP
- OV2640 was already built in
- pinout configuration for ESP32-CAM PSRAM

  How to use :
  extract in a folder in the documents\arduino folder
  build and upload

  follow in serial Monitor.

Known bug : 
  - OV5640 have stripes / Bad quality

    
  I've made this for my personnal use, but feel free to optimize it !
  I'm no dev, so there are bugs :D

  pinouts used : 
[#define PWDN_GPIO_NUM     -1
#define RESET_GPIO_NUM    15
#define XCLK_GPIO_NUM     27
#define SIOD_GPIO_NUM     25
#define SIOC_GPIO_NUM     23

#define Y9_GPIO_NUM       19
#define Y8_GPIO_NUM       36
#define Y7_GPIO_NUM       18
#define Y6_GPIO_NUM       39
#define Y5_GPIO_NUM       5
#define Y4_GPIO_NUM       34
#define Y3_GPIO_NUM       35
#define Y2_GPIO_NUM       33
#define VSYNC_GPIO_NUM    22
#define HREF_GPIO_NUM     26
#define PCLK_GPIO_NUM     21
#define LED_GPIO_NUM     25
]
[
