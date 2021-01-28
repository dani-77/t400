# t400 Coreboot and Libreboot rom's

The BSDmyt400 and LinuxWmyt400 are coreboot, like marco_coreboot.rom.
The t400_8mb_ukqwerty_vesafb.rom is a libreboot rom, directly downloaded from libreboot git.

With coreboot or libreboot already flashed, flash using:
sudo flashrom -p internal -w <name>.rom -V

With stock bios, you should use an external flasher (Rpi, BBB or another). Find instructions at coreboot.org or libreboot.org or retroboot.org.
