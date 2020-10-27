# myConfigs

## Apps

```
sudo pacman -Sy --needed android-tools flatpak git curl gzip gnupg wget aria2 tor torsocks neofetch nano gparted lutris gamemode kgpg brave keybase keybase-gui kbfs steam
```


## Keybase
Import the public key:
` keybase pgp export | gpg --import`

Import the private key:
` keybase pgp export -s | gpg --allow-secret-key-import --import `

## Git

` git config --global color.ui true`

` git config --global user.name "Tobias"`

` git config --global user.email "tobiasvosk@gmail.com"`

` ssh-keygen -t rsa -b 4096 -C "tobiasvosk@gmail.com"`

` cat ~/.ssh/id_rsa.pub`

Paste to https://github.com/settings/ssh.

` echo 'export GPG_TTY=$(tty)' >> ~/.bashrc`

` echo 'export GPG_TTY=$(tty)' >> ~/.zshrc`

` git config --global user.signingkey 44EDA6D568651D26`

` git config --global commit.gpgsign true`

## Terminal config

```
sudo pacman -S zsh

sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

```

### Download plugins

```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/agkozak/zsh-z $ZSH_CUSTOM/plugins/zsh-z
```


### Ctrl + t to find files and Ctrl + r to find commands
```
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
~/.fzf/install
```
### Set zsh as default
```chsh -s $(which zsh)```

### After this copy and paste .zshrc to ~

### Theme: 
- Sweet
- Blur background
- Background transparency 30%





