#### Run to startup


#### Add fan sensors for z370/Coffee lake
Use [this guide](https://askubuntu.com/questions/711835/fan-control-on-asrock-x99-extreme4):
1. Open `etc/default/grub`
2. Append `acpi_enforce_resources=lax` to `GRUB_CMDLINE_LINUX=""` line.
3. `sudo update-grub`
4. `sudo reboot`
