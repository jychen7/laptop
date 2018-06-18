tap "thoughtbot/formulae"
tap "homebrew/services"
tap "universal-ctags/universal-ctags"
tap "caskroom/cask"

# Unix
brew "universal-ctags", args: ["HEAD"]
brew "git"
brew "openssl"
brew "rcm"
brew "reattach-to-user-namespace"
brew "the_silver_searcher"
brew "tmux"
brew "vim"
brew "watchman"
brew "zsh"

# Heroku
brew "heroku"
brew "parity"

# GitHub
brew "hub"

# Image manipulation
brew "imagemagick"

# Testing
brew "qt@5.5" if MacOS::Xcode.installed?

# Programming language prerequisites and package managers
brew "libyaml" # should come after openssl
brew "coreutils"
brew "yarn"

# Databases
brew "postgres", restart_service: :changed
brew "redis", restart_service: :changed
brew "mysql", restart_service: :changed

# Applications
cask "gpg-suite"

cask "iterm2"
cask "sourcetree"
cask "sublime-text"
cask "macvim"
cask "macdown"

cask "docker"
cask "sequel-pro"
cask "postico"
cask "postman"

cask "google-chrome"
cask "firefox"

cask "alfred"
cask "slack"
cask "snip"

cask "expressvpn"
cask "1password"
cask "wechat"
