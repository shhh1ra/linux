**Powerlevel10k zsh theme:**
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
```
sudo nano ~/.zshrc
```
```
ZSH_THEME="powerlevel10k/powerlevel10k"
```

**Enable multilib:**
```
sudo nano /etc/pacman.conf
```
**uncomment**
```
[multilib]
Include = /etc/pacman.d/mirrorlist
```
```
sudo pacman -Sy
```

**Check if russian avaliable**
```
localectl list-keymaps | grep -i ru
```
