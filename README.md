# zsh

```
sudo apt update
sudo apt install zsh -y
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## powerlevel10k

```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/powerlevel10k
```
~/.zshrc
```
ZSH_THEME="powerlevel10k/powerlevel10k"
```
## Auto-sugestion 
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```
~/.zshrc
```
plugins=(git zsh-autosuggestions <optional-other-plugins>)
```


# nvim

```
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim-linux-x86_64.tar.gz
sudo rm -rf /opt/nvim
sudo tar -C /opt -xzf nvim-linux-x86_64.tar.gz
```
~/.zshrc
```
export PATH="$PATH:/opt/nvim-linux-x86_64/bin"

´´´


