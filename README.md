Drew Barontini's Dotfiles
=========================

Installation
------------

```bash
bash <(curl -s http://drewb.io/install.sh)
bash install.sh
```

Once the script runs, you can `rm install.sh`.

### OS X Settings

```bash
bash .osx
```

### Homebrew

```bash
ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"
brew bundle Brewfile
```

#### NPM

Node is install via Homebrew, but you'll need to run this to install NPM:

```bash
bash <(curl -s https://npmjs.org/install.sh)
```

#### Fonts

To compile fonts properly, use [Font Custom](http://fontcustom.com/).

```bash
brew install fontforge ttfautohint
gem install fontcustom
```

### Rbenv

```bash
bash .rbenv
```

### OS X Applications

```bash
brew bundle Caskfile
```

Applications not in cask:

- [1Password](https://agilebits.com/onepassword/mac)
- [Postgres](http://postgresapp.com/)
- [Remote Buddy](http://www.iospirit.com/products/remotebuddy/)

And the rest are in the Mac App Store.

What's Included
---------------

- Git
- Bash
- Homebrew
- iTerm2 (colors)
- OS X Apps, Settings
- Rbenv
- Sublime Text
- Vim

