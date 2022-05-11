# My_terminal

Steps to replicate my config. At this moments it has the "transient prompt" enabled:

1. Install the new Windows Terminal from <a href="https://www.microsoft.com/store/productId/9N0DX20HK701" target="_blank">Microsoft Store</a>

2. Install the last version of Powershell, also from <a href="https://www.microsoft.com/store/productId/9MZ1SNWT0N5D" target="_blank">Microsoft Store</a>

3. Install the fonts "CascadiaCode" from <a href="https://www.nerdfonts.com/font-downloads" target="_blank">Nerd Fonts</a> (<a href="https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/CascadiaCode.zip" target="_blank">direct link</a>)

4. Install some packages and utils:

    ```winget install Git.Git --silent --accept-package-agreements --accept-source-agreements```<br>
    ```winget install GitHub.cli --silent --accept-package-agreements --accept-source-agreements```<br>
    ```winget install JanDeDobbeleer.OhMyPosh --silent --accept-package-agreements --accept-source-agreements```<br>
    ```Install-Module -Name Terminal-Icons -Repository PSGallery```<br>
    ```Install-Module -Name PSReadLine -AllowPrerelease```

5. Clone the files from this repository:

    ```cd $HOME```<br>
    ```gh repo clone nigr0mante/My_terminal <username>/Documents/PowerShell```
    
6. Now you must copy/move the .json files inside your 'theme' for Oh-My-Posh folder (by default C:\Users\\<username\>\AppData\Local\Programs\oh-my-posh\themes)

*Preview of 'beni-in2lines.json'*
![beni-in2lines.json](https://i.imgur.com/rayy7ZN.jpg)

*Preview of 'atomic.omp.json'*
