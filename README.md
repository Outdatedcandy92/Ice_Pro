# Ice Pro – Tiny FPGA Development Board

Ice pro is a tiny development board that uses the ICE40UP5K FPGA paired with a CH552 MCU for easy configuration and USB connectivity.
![DSC_0394 (Large)](https://github.com/user-attachments/assets/e0c715cc-0c5e-42cb-9012-640ff4e962c9)
![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/0cee1df6d375bf472326be1b302ac68e48b9e409_image.png)
![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/05854194547dbda17377130c25aab347348f5c63_image.png)

---

### How it works?
Unlike many FPGA boards that require an external USB programmer, Ice Pro uses the CH552 MCU to directly program the onboard SPI flash over USB.
When the board powers up:
-  The CH552 loads your FPGA bitstream into SPI flash.
- The ICE40UP5K automatically configures itself from the flash.
- You’re ready to run your FPGA design.


---

## Schematics

![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/72b0c0755421e9432732e3852006a32850f26304_image.png)

## PCB

![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/15fdb4cf581fc0d5847d0bfe3087894ede9d6a11_image.png)
