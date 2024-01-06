# Install
git clone the repo as ~/.config/nvim

# If using X11, install xclip to allow managing clipboard
```
sudo apt install xclip
```

# Recommended aliases
in bashrc or zshrc or whatever
```
alias vim="nvim"
alias fix='nvim `git diff --name-only | uniq`'
```
