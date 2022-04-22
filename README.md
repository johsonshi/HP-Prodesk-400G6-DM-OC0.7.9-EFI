# HP-Prodesk-400G6-DM-OC0.7.9-EFI
EFI for HP Prodesk 400G6 DM with VGA adapter
desktop config:

CPU: 10th 10500T
RAM: 8G
SSD: nanya 256G NVME
Audio: ALC897
wired ethernet: intel 1219
Wireless ethernet: RTL8821

all of them are default config. most of HW could work, known issues are:
1. wireless ethernet can't work because I can not find RT8821's driver under MacOS.
2. HDMI port can't work well after system be wakeuped from hibernation. reboot system could call HDMI back.
3. VGA adapter is not supported by MacOS. so I do not drvier it.

tested under bigSur11.6 and montonry12.3.1, not perfect but it could work and let you do comming configruation in the MacOS.
Hoping it could save your valueable time on this boring work.
