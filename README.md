Xcode
Homebrew
git?

# Installation:
Pre-Reqs
```
xcode-select --install
sudo xcodebuild -license accept
```

```
git clone git://github.com/MatchSG/dotfiles.git ~/dotfiles
cd ~/dotfiles
./install.sh
```

The Homebrew install of Neovim might not install the [Python client](https://github.com/neovim/python-client).

Run the following to install it.

```
pip2 install --upgrade neovim
pip3 install --upgrade neovim
```

Follow the instructions [here](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/) to setup an SSH key.
