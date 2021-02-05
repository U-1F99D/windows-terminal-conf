# windows-terminal-conf

## Settings
Copy contents of `settings.json`

## Fonts
```
git clone https://github.com/powerline/fonts.git --depth=1
.\fonts\install.ps1
```

GOTO -> [Nerd Fonts](https://www.nerdfonts.com/font-downloads)  
Download -> `Hack Nerd Font`  
Install -> `Hack Regular Nerd Font Complete Mono Windows Compatible.ttf`

## Powerline
```
Install-Module posh-git -Scope CurrentUser
Install-Module oh-my-posh -Scope CurrentUser

Set-Prompt

notepad $PROFILE
```

Append following lines:
```
Import-Module posh-git
Import-Module oh-my-posh
Set-Theme Paradox
```


### Inspired by
https://medium.com/@hjgraca/style-your-windows-terminal-and-wsl2-like-a-pro-9a2e1ad4c9d0