# Acer Nitro 5 AN515-52-52BW OpenCore Hackintosh EFI



<img align="right" src="https://support.apple.com/content/dam/edam/applecare/images/en_US/macos/psp-mini-hero-macos-high-sierra-whats-new_2x.png" alt="Critter" width="250">


**macOS Version: 11.2.2**

**OpenCore Version: [0.6.7 Official](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.6.7)**

Visão Geral do Projeto
Este OpenCore Hackintosh EFI é projetado para o laptop Acer Nitro 5 AN515-52-52BW, equipado com um processador Intel Core i5-8300H de 8ª geração, uma placa de vídeo NVIDIA GeForce GTX 1050 com 4 GB de memória VRAM e outros componentes compatíveis. O projeto é continuamente atualizado para garantir compatibilidade com as versões mais recentes do OpenCore e do macOS.

## Configuration

| Specifications | Detail | Working |
| :------------: | :------: | :--------: |
| Model | Acer Nitro 5 AN515-52-52BW | ✅ |
| Processor | Intel Core i5-8300H @ 2.30Ghz | ✅ |
| Memory | 24GB Micron DDR4 2666Mhz | ✅ |
| SSD | Nvme Xpg 256GB | ✅ |
| HDD | WD10SPZX 1TB | ✅ |
| iGPU | Intel UHD Graphics 630 | ✅ |
| dGPU | NVIDIA GeForce GTX 1050 4G | 🚫 |
| Sound Card | Realtek ALC236 | ✅ |
| Ethernet Card | Realtek RTL8111 | ✅ |
| Wireless Card | Inte Wireless-AC 9462 | ✅ |

## Working

- macOS 11.2.2
- CPU (Boost to 3.8Ghz)
- iGPU
- Ethernet
- Audio (Layout=15)
- USB (Customed by USBPorts.kext)
- Trackpad
- WebCam
- Bluetooth (With On/Off buttom)
- Wi-Fi (Supported by [AirportItlwm](http://bbs.pcbeta.com/viewthread-1848662-1-1.html))

## Not Working

- dGPU (Disabled by SSDT)
- HDMI (Directly link to dGPU)
- Internal SD Card Reader
