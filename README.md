# My_terminal

Steps to replicate my config:

1. Install the fonts "CascadiaCode" from [Nerd Fonts](https://www.nerdfonts.com/font-downloads) ([direct link](https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/CascadiaCode.zip))

2. Install some packages and utils

    ```winget install Git.Git --silent --accept-package-agreements --accept-source-agreements```<br>
    ```winget install GitHub.cli --silent --accept-package-agreements --accept-source-agreements```<br>
    ```winget install JanDeDobbeleer.OhMyPosh --silent --accept-package-agreements --accept-source-agreements```<br>
    ```Install-Module -Name Terminal-Icons -Repository PSGallery```<br>
    ```Install-Module -Name PSReadLine -AllowPrerelease```

3. Copy the PS1 file from this repository
