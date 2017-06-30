# macsetup

## Install Homebrew

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## Install formulas

```
formulas="bash wget coreutils gnu-sed jq openssl gnutls s3cmd tree unrar watch ncdu"
brew install $formulas
```

## Install Casks

```
casks='ccleaner aws-vault virtualbox vagrant vagrant-manager visual-studio-code chefdk spotify spectacle slack caskroom/cask/google-drive'
brew cask install $casks

```
