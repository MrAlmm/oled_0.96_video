# oled_0.96_video

file:///C:/Users/mam20/Downloads/746878048_1717566662774794_5896726065488620736_n.jpg


A project for playing video sequences on a 0.96-inch OLED display (SSD1306) using an ESP32.

## Features
*   **Video Playback:** Optimized frame-by-frame rendering for 0.96" OLED displays.
*   **Performance:** Designed to work with the ESP32 for smooth animation speeds.
*   **Lightweight:** Minimal memory footprint for embedded applications.

## Hardware Requirements
*   **Microcontroller:** ESP32 (DevKit recommended).
*   **Display:** 0.96" OLED Display (I2C interface).
*   **Wiring:**
    *   **VCC:** 3.3V
    *   **GND:** GND
    *   **SDA:** GPIO 21
    *   **SCL:** GPIO 22

## Software Requirements
*   **IDE:** PlatformIO or Arduino IDE.
*   **Libraries:** 
    *   Adafruit_SSD1306
    *   Adafruit_GFX

## Installation
1.  Clone this repository: `git clone https://github.com/MrAlmm/oled_0.96_video.git`
2.  Open the project in your preferred IDE.
3.  Install the required libraries via the Library Manager.
4.  Build and upload the code to your ESP32.

## Usage
Modify the frame array in `main.cpp` to include your own image data. You can convert your videos/images using an online "Image to C array" converter to generate the necessary byte arrays for your OLED.

## License
Distributed under the MIT License. See `LICENSE` for more information.
