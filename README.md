## Breadboard Diagram
![987bad](https://github.com/user-attachments/assets/636bacc9-47b8-4dfc-abd3-c061c9ef03fe)

This Arduino program gradually fades five LEDs in and out using Pulse Width Modulation (PWM). The LEDs are connected to PWM-capable pins 3, 5, 6, 9, and 10. In the setup() function, all five pins are set as outputs. The loop() first fades in each LED by gradually increasing its brightness, then fades out each LED by decreasing the brightness. This is handled by the fadeLED() function, which adjusts the LED brightness in small increments (fadeValue = ±5) within a loop, ensuring a smooth transition. A 20ms delay between each step slows the fading effect for better visibility.
