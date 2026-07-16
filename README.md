# oled_0.96_video

https://scontent.fjed2-2.fna.fbcdn.net/v/t1.15752-9/746878048_1717566662774794_5896726065488620736_n.jpg?_nc_cat=101&_nc_map=urlgen_bucketless&ccb=1-7&_nc_sid=fc17b8&_nc_ohc=NRYAE6t82HYQ7kNvwGVa2oQ&_nc_oc=Adp7TY_ztuRL0rfktjdPJVAUIZ2ZJESPX17uGoHOMPXpMFpNvhRHgB5orjSDL1NhSeY&_nc_zt=23&_nc_ht=scontent.fjed2-2.fna&_nc_ss=7baaf&oh=03_Q7cD5wFKMEVurE61KJxxDijAn7YaGK6amN8lYrdBgVLu92pPgQ&oe=6A807AD9


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
