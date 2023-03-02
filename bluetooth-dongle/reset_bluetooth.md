https://askubuntu.com/questions/1375745/bluetooth-audio-a2dp-mode-stopped-working-after-21-10-update

Purge everything related to bluetooth : sudo apt purge pulseaudio-module-bluetooth bluetooth "bluez-*" bluez

Delete /var/lib/blueman and /var/lib/bluetooth

Reinstall : sudo apt install blueman bluez pulseaudio-module-bluetooth --install-suggests

Re-pair your devices
