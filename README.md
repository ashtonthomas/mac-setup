# Set up your new Mac directions

## 1. install rvm
```
\curl -sSL https://get.rvm.io | bash -s stable --ruby=2.0.0
```

## 2. install command line tools for building.
```
xcode-select --install
```

## 3. install homebrew
```
ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"
```

## 4.  Clone this repo and bundle
```
git clone git@github.com:bellycard/mac-setup.git
cd mac-setup
brew bundle
```
