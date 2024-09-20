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
****
**ZSH:**
```
sudo pacman -S zsh
```
**Установить ohMyZsh:**
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
**Установить тему powerlevel10k:**
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
**Применить тему**
```
sudo nano ~/.zshrc
```
Заменить **ZSH_THEME="robbyrussell"** на **ZSH_THEME="powerlevel10k/powerlevel10k"**

**Если не выбрался zsh:**
```
sudo nano ~/.bashrc
```
*в первую строку:*
```
exec zsh
```
****
**Wifi connect:**
```
iwctl
station list
station wlan0 get-networks
station wlan0 connect <SSID_NAME>
```

****
**BSPWM Config**
```
sudo nano ~/.config/bspwm/bspwmrc
```

HZ:
```
xrandr
```
```
xrandr --output {output} --mode {resolution} --rate {rate}
```
