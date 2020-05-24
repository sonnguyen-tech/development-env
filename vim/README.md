Credit [https://github.com/erkrnt/awesome-streamerrc/blob/master/ThePrimeagen/.vimrc](https://github.com/erkrnt/awesome-streamerrc/blob/master/ThePrimeagen/.vimrc)

# Ubuntu

## Preinstall

Make sure you have to following before you dependencies

```
sudo apt-get install python3-dev cmake g++
```

Get vim [plugin](https://github.com/junegunn/vim-plug)

```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```



## .vimrc

Copy .vimrc from this repo to your local `~/.vimrc`

In your .vimrc install plugin by doing `esc` +  `:PlugInstall`

### Important ❗❗

You need to manual install YouCompleteMe

```
cd ~/.vim/plugged/YouCompleteMe

python3 install.py
```
