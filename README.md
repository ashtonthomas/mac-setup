# Set up your new Mac directions

## 1. install command line tools for building.
- [install/update Xcode](https://itunes.apple.com/us/app/xcode/id497799835?mt=12) from the "App Store"
- command line tools installed?: `$ pkgutil --pkg-info=com.apple.pkg.CLTools_Executables`
- if not: `$ xcode-select --install`
- open Xcode and agree to any terms (or things may just not work)

## 2. install homebrew
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
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
./install_brews
```
