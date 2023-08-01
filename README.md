# Unix Config

## Setup
Checkout this repo to `~/.unix_config`
```sh
git clone git@github.com:bradfordben/unix_config.git ~/.unix_config
```

Pull git sub modules
```sh
cd ~/.unix_config
git submodule update --init --recursive
```

 Setup symlinks
 ```sh
 ln -s ~/.unix_config/vim_config/.vimrc ~/.vimrc
 ln -s ~/.unix_config/bashrc_config/.bashrc ~/.bashrc
 ln -s ~/.unix_config/tmux_config/.tmux.conf ~/.tmux.conf
 ln -s ~/.unix_config/git_config/.gitconfig ~/.gitconfig
 ```
