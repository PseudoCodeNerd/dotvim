## pseudocodenerd's neovim config
well this is my personal setup and i wouldn't really recommend using it (it has some weird keybindings)

 `init.vim` has comments to tell you what everything does. Most of the comments are by my friend [soumitradev](https://github/com/soumitradev) (please pardon his attempt to be humorous, he is not...) and i've added some as well.

in the end, this config still remains inspired by dotangad's and me and soumi both thank him for giving us this starter to configure our own setups.

---

### Steps
*taken from dotangad's repo*

1. Clone this repo
```sh
mv $HOME/.config/nvim $HOME/.config/nvim.bak >> /dev/null
git clone https://github.com/pseudocodenerd/dotvim $HOME/.config/nvim
```

2. Install `vim-plug`
```sh
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

--- 

> p.s: soumi still is a vscode fanboy and has ported vsc keybindings to his vim config smh