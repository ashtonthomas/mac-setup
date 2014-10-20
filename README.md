# Set up your new Mac directions

## 1. install command line tools for building.
- Open the "App Store" application
- Click "Update" for the "Command Line Developer Tools for OS X Mavericks"

If that doesn't work, [install Xcode](https://itunes.apple.com/us/app/xcode/id497799835?mt=12) and then install command line tools from there 

## 2. install homebrew
```
ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"
```

## 3. install rbenv || rvm 

**rbenv**
```
brew install rbenv
brew install ruby-build
```

**rvm**
```
curl -sSL https://get.rvm.io | bash -s stable --ruby=2.0.0
```

## 4.  Clone this repo and bundle
```
git clone git@github.com:bellycard/mac-setup.git
cd mac-setup
brew bundle
```
