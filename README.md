# Hackintosh-LG-15N540
A bootable but not completely stable macOS Monterey-compatible Hackintosh EFI for the LG 15N540.

## Laptop Hardware
- Intel Core i7-4810MQ
- 16GB DDR3-1600MHz (2 x 8GB)
- Intel HD Graphics 4600
- Intel HM77 Chipset
- 120GB SATA M.2
- Qualcomm Atheros
- 1920 x 1080 60Hz LVDS (?)

## Limitations
The EFI will correctly install macOS on a storage drive. The laptop will also boot to it correctly.
However, the following errors occur when in macOS:
- Graphics acceleration randomly not working upon boot
  - If it runs on the GPU properly, it will say Intel HD Graphics 4600 1536MB.
  - If not, it will say 7MB.
- Kernel panic after 10 seconds when waking from sleep
