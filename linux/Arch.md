**Проверить все пакеты:**
```
sudo pacman -Syu
```

**Установить yay (Aur):**
```
sudo pacman -S --needed base-devel git
```
```
git clone https://aur.archlinux.org/yay.git
```
```
cd yay
```
```
makepkg -si
```

**Pamac:**
```
yay -S pamac-flatpak 
```

**Официальные репозитории:**
```
sudo pacman -S steam flatpak neofetch
```

**Flatpak:**
```
flatpak install flathub org.telegram.desktop com.mattjakeman.ExtensionManager com.discordapp.Discord com.github.tenderowl.frog io.github.vikdevelop.SaveDesktop
```

**Wifi connect:**
```
iwctl
station list
station wlan0 get-networks
station wlan0 connect <SSID_NAME>
```