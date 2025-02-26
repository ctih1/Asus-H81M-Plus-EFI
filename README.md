# i7-4770-GT-1030-EFi
Opencore EFI for my computer.

## Specs
| Component | Model |
| --------- | ----- |
| CPU | Intel Core i7-4770 |
| GPU | NVIDIA Gefore GT 1030 |
| RAM | 16GB of DDR3 @ 1600mhz |
| Motherboard | Asus H81MD |
| Bluetooth (dongle) | Asus BT400 |
| WiFi | Realtek something |

## What works and doesn't
| Item | Works? |
| ----- | -----| 
| Bluetooth | Yes(1) |
| USB | Yes |
| Graphics Acceleration | Yes(2) |
| Airdrop | No |
| WiFI | No(3) |
| Power management | Yes |
| Sleep | No |
| Screen recording | No(4) |
| iServices (Apple music etc) | Yes |

1: Works with a Bluetooth dongle
2: Nvidia webdrivers only support macOS High sierra and lower, so to get the GPU to work in Monterey, you have to use Opencore Legacy Patcher. There are some minor glitches (mostly with blur), and screen recording is broken. 
3: WiFi is not supported, as the WiFi-card is a Realtek one.
4. Trying to screen record the entire screen simply results in a purple video. Recording specific applications with OBS works.


## The macOS experience
macOS has been quite pleasant to use on this computer, even though the GPU is not officially supported. I've done some video editing, coding, and light gaming (mostly Minecraft) on this machine, and they all perform about as well as they do on windows. NOTE: Certain apps just will not launch / work correctly because of the GPU being unsupported. Some of these apps include newer versions of Davinci resolve, and the Warp terminal app.


![Näyttökuva 2025-2-26 kello 17 30 43](https://github.com/user-attachments/assets/ad1942b5-2184-4617-8cc6-18ef813e48dd)
![image](https://github.com/user-attachments/assets/d4a1aea4-1a3b-4c44-9d37-420ca37a2e1b)


## Screenshots 
![image](https://github.com/user-attachments/assets/6f91e190-8094-44f3-b6ca-f1238f782e89)





