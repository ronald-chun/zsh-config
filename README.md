# zsh-config
zsh configuration

# Installation
1. Clone the repository
```
git clone --recurse-submodules https://github.com/ronald-chun/zsh-config.git $HOME/.config/zsh
```

2. Copy the zshrc template to the root directory (If you already have the `.zshrc` file, please backup the orginal `.zshrc` first and merge the config )
```
cp zshrc-example $HOME/.zshrc
```
# Add plugins
1. Add the plugin as a submodule, eg.
```
git submodule add https://github.com/zsh-users/zsh-autosuggestions.git plugins/zsh-autosuggestions
```

2. Source the plugin in the `config` file, eg.
```
...
source ${DIR}/plugins/zsh-autosuggestions/zsh-autosuggestions.zsh
...
```