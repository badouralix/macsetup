# macsetup

## Install Homebrew and Homebrew-Cask

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew tap caskroom/cask
```

## Install formulas and casks

```

cli_utils="bash coreutils gnu-sed jq gnutls ncdu nmap openssl telnet tree unrar watch wget vegeta"
brew install $cli_utils

# dev environment
dev_env="pyenv pyenv-virtualenv nvm yarn"
brew install $dev_env

# cloud and stuff
cloudz="aws-cli kubernetes-cli kubernetes-helm kubectx s3cmd tfenv vault"
cloudz_casks="aws-vault virtualbox vagrant vagrant-manager"
brew install $cloudz
brew cask install $cloudz_casks


# random tools
random_casks='ccleaner visual-studio-code chefdk spectacle'
brew cask install $random_casks

```
