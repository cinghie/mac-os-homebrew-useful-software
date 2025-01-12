# Mac OS Homebrew Useful Software
Use Homebrew to install all needed programs for your Mac OS

## Install Homebrew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Update Homebrew

```
brew update
brew upgrade
```

## Useful Software

```
brew install --cask macfuse
brew install --cask avg-antivirus
brew install --cask the-unarchiver
brew install --cask firefox
brew install --cask opera
brew install --cask tor-browser
brew install --cask thunderbird
brew install --cask vlc
brew install --cask spotify
brew install --cask gimp
brew install --cask adobe-acrobat-reader
brew install --cask libreoffice
brew install --cask libreoffice-language-pack
brew install --cask franz
brew install --cask skype
brew install --cask free-download-manager
brew install --cask macpass
brew install --cask anydesk
brew install --cask teamviewer
brew install --cask virtualbox
```

## Development Software

```
brew install wget
brew install curl
brew install git
brew install openjdk
brew install composer
brew install php@8.2
brew install cocoapods
brew install node
brew install watchman
brew install imagemagick
brew install ffmpeg
npm install -g react-native-cli
brew install --cask xampp
brew install --cask github
brew install --cask phpstorm
brew install --cask poedit
brew install --cask mysqlworkbench
brew install --cask android-studio
brew install --cask visual-studio
brew install --cask visual-studio-code
brew install --cask postman
```

## Setting XAMPP Permissions

```
sudo nano /Applications/XAMPP/xamppfiles/etc/httpd.conf
```

change

```
User nobody
Group nogroup
```

to

```
User your_mac_username
Group staff
```

## Game Software

```
brew install --cask steam
```

## Not Homebrew Software

https://www.google.com/intl/it_it/chrome/  
https://www.google.it/intl/it/drive/download/  
https://www.photopea.com/  

## See

https://brew.sh/
https://medium.com/@oscarmwana/quick-fix-wordpress-xampp-permissions-error-on-mac-e8cd843ef261  
https://blog.devgenius.io/switching-php-versions-on-macos-using-homebrew-2ee3058c8239  
