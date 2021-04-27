# zshconfig

My custom zsh configuration. Install and enjoy.

## Installation

Install zsh and fuzzy search:

```sh
sudo apt install zsh fzf ripgrep fd-find silversearcher-ag
```

Change Shell to zsh:

```sh
chsh -s /usr/bin/zsh
```

Install oh-my-zsh:

```sh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

Link the contents of this repo:

```sh
ln -s ~/zshconfig/.oh-my-zsh/custom/aliases.zsh ~/.oh-my-zsh/custom/aliases.zsh
ln -s ~/zshconfig/.zshrc ~/.zshrc
ln -s ~/zshconfig/.p10k.zsh ~/.p10k.zsh
```

Pull zsh-autosuggestions:

```sh
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

Install the Sauce Code Pro Semibold Nerd Font Mono:

```sh
wget https://github.com/ryanoasis/nerd-fonts/raw/master/patched-fonts/SourceCodePro/Semibold/complete/Sauce%20Code%20Pro%20Semibold%20Nerd%20Font%20Complete%20Mono.ttf --directory-prefix=.local/share/fonts
```

Change your Terminal emulators font to the Sauce Code Pro Semibold Mono font.

Get Powerlevel 10k:

```sh
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
