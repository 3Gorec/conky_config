#### Run at startup
I use [guide](https://help.ubuntu.com/community/SettingUpConky#Set_Conky_To_Start_At_Boot) for Ubuntu/gnome:
1. Press `Alt+F2`
2. Type `gnome-session-properties` then `Enter`
3. Press "Add", then add new program with Name: "Conky", command: `conky` 
4. Reboot

#### Add fan sensors for z370/Coffee lake
Use [this guide](https://askubuntu.com/questions/711835/fan-control-on-asrock-x99-extreme4):
1. Open `etc/default/grub`
2. Append `acpi_enforce_resources=lax` to `GRUB_CMDLINE_LINUX=""` line
3. `sudo update-grub`
4. `sudo reboot`
