# Song Lyrics and Image Display System

ESP32 mini project that displays pre-converted song lyric bitmap scenes on a 128×64 SSD1306 OLED display.

## Hardware
- ESP32
- 128×64 I2C OLED (SSD1306)

## Connections
- GND → GND
- VCC → 3.3V
- SDA → GPIO21
- SCL → GPIO22

The code uses `Wire.begin(21,22)` and OLED address `0x3C`.

## Status
Circuit verified. Source code will be added next.