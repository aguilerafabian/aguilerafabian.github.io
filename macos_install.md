# MacOS - Installation process

Note:
- Execute in order
- Some apps will require admin priviligies

### Xcode
- Install Xcode from App Store

- Install Xcode command line tools
    ``` bash
    sudo xcode-select --install
    ```

### Homebrew
``` bash
. /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
- Add brew to PATH
    ``` shell
    (echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> $HOME/.zprofile
    ```

``` bash
exit
```
``` bash
brew update
brew upgrade
```

## System
``` bash
. brew install --cask commander-one
```
``` bash
. brew install --cask raycast
```
``` bash
. brew install --cask iterm2
```
``` bash
. brew install --cask clipy
```
``` bash
brew install --cask ccleaner
```
> Pide password de administrador al instalar
``` bash
. brew install --cask alt-tab
```
``` bash
. brew install wireguard-tools
```
``` bash
. brew install --cask authy
```
``` bash
. brew install --cask rectangle
```
``` bash
brew install --cask ledger-live
```
``` bash
. brew install --cask go2shell
```
``` bash
. brew install --cask balenaetcher
```
``` bash
. brew install wget
```
``` bash
. brew install htop
```
``` bash
. brew install tree
```
``` bash
. brew install bat
```
``` bash
. brew install speedtest-cli
```
> ##### Oh My ZSH
``` bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
>``` bash
>exit
>```
``` bash
brew install romkatv/powerlevel10k/powerlevel10k
```

## Text editing
``` bash
. brew install --cask sublime-text
```
``` bash
. brew install neovim
```

## Internet browsing
``` bash
. brew install --cask brave-browser
```

## Development
``` bash
. brew install jq
```
``` bash
. brew install --cask postman
```
``` bash
brew install --cask rowanj-gitx
```
``` bash
brew install --cask diffmerge
```
> Dar permiso de ejecucion a terceros al ejecutar

>##### Sdkman
>``` bash
>curl -s "https://get.sdkman.io/" | bash
>```
>``` bash
>exit
>```

>##### Visual Studio Code
>``` bash
>brew install --cask visual-studio-code
>```

>##### GVM
>``` bash
>bash < <(curl -s -S -L https://raw.githubusercontent.com/moovweb/gvm/master/binscripts/gvm-installer)
>```

>##### JAVA 17
>``` bash
>sdk install java 17.0.4-zulu
>```

>##### GO 18
>``` bash
>gvm install go1.18.5
>```
>``` bash
>gvm use go1.18.5 --default
>```




``` bash
brew install --cask intellij-idea-ce
```

``` bash
brew install tig
```

## Multimedia
``` bash
. brew install --cask spotify
```
``` bash
. brew install --cask xnviewmp
```
``` bash
. brew install --cask vlc
```
``` bash
. brew install --cask kindle
```

## Instant Messaging / Social
``` bash
. brew install --cask whatsapp  
```
``` bash
. brew install --cask telegram
```
``` bash
. brew install --cask discord
```

## Notas
``` bash
. brew install --cask obsidian
```

## Cloud storage
``` bash
. brew install --cask onedrive
```

## Reading
``` bash
. brew install --cask kindle
```

# Faltan

>GPG Keychain -> brew install --cask gpg-suite

#macOS 