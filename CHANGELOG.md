# Change Log

## Unreleased

### Added
- Scripts in `scripts/` for any `rake` tasks missing them
- `git-tag` bin script
- Day One
- `kd` Bash alias
- `TablePlus` to `scripts/cask`
- Night Owl theme
- `ys` Bash alias for `yarn start`
- `github` to `scripts/cask`
- `figma` to `scripts/cask`

### Changed
- Better `Rakefile` with namespaces and descriptions
- Better `README` with `rake` tasks and descriptions
- Cleaned up `bash/partials/aliases`
- Cleaned up `bash/functions`
- Moved the VSCode to the right
- `prettierrc` to include `"proseWrap": "always"`

### Removed
- `omnigraffle` from `scripts/homebrew-packages`
- `git_tag` function
- Unnecessary line in `Rakefile` for disabling press and hold in macOS
- Tweetbot
- MindNode
- AppCleaner
- Nucleo

## 1.9.0 - 2018-12-07

### Added
- `Rocket` to `setup/cask`
- Vim "no fun" mode
- `prettier/prettierrc`
- `git_changes_since_version` Bash function
- `update_nvm` Bash function
- `setup/homebrew`
- `rake update` task

### Changed
- Removed `Arq` from `setup/cask`
- `setup/npm`
- ESLint setup
- VSCode settings
- `git/gitconfig`
- Replaced `ColorSnapper2` with `Sip`
- `setup/osx` is now `setup/macos`
- Moved `nvm` out of Homebrew
- `update` now includes `update_nvm`
- `brew` to `homebrew-packages`
- `Rakefile` to be better
- `setup/` directory to `scripts/`

### Fixed
- Wrong CleanMyMac version in `setup/cask`
- Installing Node
- Installing Ruby

## 1.8.0 - 2018-11-20

### Added

- `vim-javascript` plugin
- Spacemacs configuration
- `notion` to `setup/cask`
- `bettertouchtool` to `setup/cask`
- `visual-studio-code` to `setup/cask`
- `visual-studio-code-insiders` to `setup/cask`
- `Newton` to `setup/mas`

### Changed

- Vim colors
- Vim settings
- Auto-formatting settings in Vim
- VSCode settings
- Hyper settings
- Sublime Text settings/packages
- `tmuxline_snapshot`
- `git_remote_tracking_branch` function to accept source branch
- `setup/cask`
- `setup/mas`

### Removed

- Line numbers in Vim
- Disable Ultisnips in Vim

### Fixed

- Italics in tmuxline

## 1.7.0 - 2018-03-07

### Changed

- `setup/cask`
- `setup/mas`
- Visual Studio Code settings
- `git/gitignore` to `rebase` by default when pulling
- Use VSCode as the git diff tool
- New colors!

### Fixed

- Fixed a bug with Vim pane navigation

## 1.6.5 - 2018-01-13

### Changed

- Visual Studio Code settings
- Atom settings
- `setup/mas`
- `setup/cask`
- `vim/gvimrc` font size
- Sublime Text settings
- Global Node version to `8.6.0`
- `git/gitconfig`

### Added

- `github-desktop` to `setup/cask`
- `yarn` aliases
- `gem/gemrc` file

## 1.6.4 - 2017-09-15

### Changed

- Fixed Spotify status in tmuxline

## 1.6.3 - 2017-09-15

### Changed

- Fixed italics in tmuxline being overwritten

## 1.6.2 - 2017-09-15

### Changed

- Fixed italics in Bash prompt
- `Ale` plugin settings in Vim

## 1.6.1 - 2017-09-15

### Changed

- tmux project name now in italics!

## 1.6.0 - 2017-09-15

### Added

- `Ulysses.app` to `setup/mas`
- `language-graphql` package to Atom
-  `flow-bin` to `setup/npm`
- `vim-jsx-improve` plugin
- Hybrid color scheme
- `neovim` to `setup/brew`
- `tpm` aliases
- `pristine-ui` Atom package

### Changed

- Visual Studio Code settings
- Atom settings
- Hyper settings
- Sublime Text settings
- Vim active plugins
- Replaced `syntastic` with `ale`
- `vim/UltiSnips`
- Solarized-specific Vim settings
- `vimrc` settings
- `vim-easymotion` plugin source
- Reactivated `vim-gitgutter` plugin
- `gvimrc`
- Global Node version
- Visual Studio Code settings
- `vim`/`tmux` navigation settings
- Update bash prompt (italics for Git branch!)

### Removed

- Unused Vim mappings

## 1.5.0 - 2017-07-31

### Added

- Git aliases
- Heroku aliases
- `gl` Vim mapping
- Better Prettier support in Vim (change on save!)
- Initial stylefmt/stylelint support
- `Rocket.app` to `setup/cask`
- `Tweeten.app` to `setup/cask`
- `FontBase.app` to `setup/cask`
- New Atom snippets
- `watchman` to `setup/brew`

### Changed

- Update Atom settings
- Heroku `hd` alias
- Vim ruler to `80`
- Update Sublime Text settings
- Bash prompt
- Update Vim Solarized settings
- Update Visual Studio Code settings
- Updated ESLint configuration

### Removed

- Unused Git aliases

## 1.4.0 - 2017-05-25

### Added

- `vc` alias
- `Spark.app` to `setup/mas`
- `setup/eslint`
- `Pug` Sublime Text package
- `Atom Beta` to `setup/cask`

### Changed

- Updated Sublime Text settings
- Updated Hyper settings
- Updated Bash prompt
- Updated Visual Studio Code settings

### Removed

- `vim-gitgutter` plugin
- Disable Gulp autocomplete

## 1.3.0 - 2017-05-10

### Added

- New application in `setup/mas`
- `~/.editorconfig` file

### Removed

- Mappings for `gitgutter` Vim plugin

## 1.2.0 - 2017-05-09

### Added

- Yarn aliases
- `mongodb-compass` to `setup/cask`

### Changed

- Update Atom settings
- Update Visual Studio Code settings
- Update Sublime Text settings
- `ld` bash alias to show human-readable filesizes
- Bash prompt to include 😎 emoji
- Node modules in `setup/npm`
- Global Node version to `7.10.0`

### Removed

- Newton from `setup/mas`
- Unused bash aliases

## 1.1.0 - 2017-05-02

### Added

- Newton to `setup/mas`
- Noizio to `setup/mas`
- New options to `.gitconfig` (`git/gitconfig`)

### Changed

- Update Atom theme and settings
- Update Sublime Text settings
- Update Visual Studio Code settings
- Update tmux copy/paste commands to the new syntax
- `setup.md` to be more concise

## 1.0.0 - 2017-04-24

### Added

- Initial version
- `CHANGELOG.md` file
