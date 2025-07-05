# Mac OS Homebrew Development Useful Software
Use Homebrew to install all Development Useful Software for your Mac OS

## Install Homebrew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Update Homebrew

```
brew update
brew upgrade
```

## Development Software

```
brew install wget
brew install curl
brew install git
brew install openjdk
brew install composer
brew install php@8.2
brew install php@8.4
brew install cocoapods
brew install node
brew install watchman
brew install imagemagick
brew install ffmpeg
npm install -g react-native-cli
brew install --cask xampp
brew install --cask docker  
brew install --cask github
brew install --cask postman
brew install --cask phpstorm
brew install --cask poedit
brew install --cask mysqlworkbench
brew install --cask android-studio
brew install --cask visual-studio
brew install --cask visual-studio-code
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

## See

https://brew.sh/  
https://medium.com/@oscarmwana/quick-fix-wordpress-xampp-permissions-error-on-mac-e8cd843ef261  
https://blog.devgenius.io/switching-php-versions-on-macos-using-homebrew-2ee3058c8239  
