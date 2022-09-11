# OPENCORE EFI for AMD Ryzen / MSI b550m bazooka / RX580

![Screenshot](/screenshot.png?raw=true)

**macOS version**: 11.6.7 (20G630) \
**OpenCore version**: 0.8.1

## Hardware Config

| **Component**    | **Model**                                  |
| ---------------- | ------------------------------------------ |
| CPU              | AMD Ryzen 5 3600                           |
| Motherboard      | MSI b550m Bazooka                          |
| RAM              | 16GB (2 x 8GB) Corsair Vengeance @ 2666MHz |
| GPU              | Asus RX580 8GB                             |
| Audio Chipset    | Realtek ALC892/ALC897                      |
| Ethernet         | Realtek RTL8111                            |

## Bios Settings

|        Config         | Status      |
|:---------------------:|------------ |
|     **Fast Boot**     | Disable     |
|    **Secure Boot**    | Disable     |
|        **CSM**        | Disable     |
| **Above 4G Decoding** | Enable      |

# Attention

Update **config.plist** in PlatformInfo > Generic with YOUR informations.
<br><br>
*1. MLB (Board Serial)
<br>
2. ROM (Mac Address)
<br>
3. SystemSerialNumber (Serial)
<br>
4. SystemUUID (SmUUID)*

Please use [*genSMBIOS*](https://github.com/corpnewt/GenSMBIOS/archive/refs/heads/master.zip) for generate values for above itens.
<br>
Please use [*ProperTree*](https://github.com/corpnewt/ProperTree/archive/refs/heads/master.zip) for configure/edit your config.plist.


# References
https://github.com/luchina-gabriel/BASE-EFI-AMD-RYZEN-THREADRIPPER

## Discord - Universo Hackintosh
- [Access Discord](https://discord.universohackintosh.com.br)
