# Setup
My personal favourite tools/configs to use on Linux

## Clipboard history
https://hluk.github.io/CopyQ/ \
CopyQ

## Git config

```
git config --global core.editor vim
git config --global --type bool push.autoSetupRemote true
git config --global alias.st status
git config --global alias.co checkout
```

## Screenshot
https://flameshot.org/ \
flameshot

## Keyboard shortcuts
https://github.com/houmain/keymapper \
See keymapper.conf

## ZSHRC
```
bindkey '^H' backward-kill-word

PROMPT="%F{98}%m%f ${PROMPT}"
```