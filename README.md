# Zsh/Starship

I use Zsh as my default shell, Oh-my-zsh for plugins and Startship for my prompt. The themes I have also require Nerd Fonts.
Zsh com Oh-my-zsh e Startship
- Run the installation commands below
- Usar .zshrc em `$HOME`.

```
#Oh-my-zsh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

#ZSH plugins
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
git clone https://github.com/agkozak/zsh-z ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-z

#Starship Prompt
curl -sS https://starship.rs/install.sh | sh

# Nerd Fonts - Hack font (via git)
git clone --depth 1 https://github.com/ryanoasis/nerd-fonts
cd nerd-fonts
./install.sh Hack

```

## Other Tools

```
### Basic tools, nerdfont, fuzzy finders
sudo apt update
sudo apt install peco -y
sudo apt install exa -y
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
~/.fzf/install

```

Comanados mais usados.

## Zsh-Z
```
z  # Pastas mais usadas
```
## FZF - Fuzzy Search
```
^r  # Procurar comandos
^t  # Procurar pastas
```
