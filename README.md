# ArchLinux-Setup



# Nedeed fonts: <br>
noto-fonts noto-fonts-cjk noto-fonts-emoji

# hardware acceleration for browsers <br>
https://github.com/elFarto/nvidia-vaapi-driver - firefox


# Nvidia settings startup <br>
1) Run nvidia-settings and customize (this writes ~/.nvidia-settings-rc <br>
2) Create ~/.config/autostart/nvidia.desktop that contains the following: <br>
[Desktop Entry] <br>
Type=Application <br>
Exec=nvidia-settings -l <br>
Name[en_US]=nvidia-settingsOn <br>
Name=nvidia-settingsOn <br>

