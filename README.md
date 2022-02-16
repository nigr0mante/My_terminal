# My_terminal

Steps to replicate my config. At this moments it has the "transient prompt" enabled:

1. Install the fonts "CascadiaCode" from <a href="https://www.nerdfonts.com/font-downloads" target="_blank">Nerd Fonts</a> (<a href="https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/CascadiaCode.zip" target="_blank">direct link</a>)

2. Install some packages and utils

    ```winget install Git.Git --silent --accept-package-agreements --accept-source-agreements```<br>
    ```winget install GitHub.cli --silent --accept-package-agreements --accept-source-agreements```<br>
    ```winget install JanDeDobbeleer.OhMyPosh --silent --accept-package-agreements --accept-source-agreements```<br>
    ```Install-Module -Name Terminal-Icons -Repository PSGallery```<br>
    ```Install-Module -Name PSReadLine -AllowPrerelease```

3. Copy the PS1 file from this repository

    ```cd $HOME```<br>
    ```gh repo clone nigr0mante/My_terminal <username>/Documents/PowerShell```
    
