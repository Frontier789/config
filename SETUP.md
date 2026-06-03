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
git config --global alias.lb '!f() { git reflog --format="%gs" | grep "^checkout: moving from" | awk '"'"'{print $NF}'"'"' | awk '"'"'!seen[$0]++'"'"' | head -n "${1:-5}"; }; f'
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
