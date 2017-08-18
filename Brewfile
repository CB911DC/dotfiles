# Use `brew bundle` to install the packages listed below

cask_args appdir: "/Applications"
tap "caskroom/cask"
tap "caskroom/fonts"
tap "caskroom/versions"
tap "homebrew/dupes"
tap "homebrew/versions"

# Core dependencies
cask "java" unless system "/usr/libexec/java_home --failfast"

# Command line apps
brew "ack"
brew "asciinema"
brew "awk"
brew "aws-shell"
brew "awscli"
brew "bash"
brew "bc"
brew "bfg"
brew "boost"
brew "bzip2"
brew "cloc"
brew "coreutils"
brew "curl"
brew "diffstat"
brew "diffutils"
brew "ec2-ami-tools"
brew "ec2-api-tools"
brew "ed"
brew "elm"
brew "expect"
brew "ffmpeg"
brew "filebeat"
brew "findutils"
brew "git", args: ["--without-completions"]
brew "git-extras"
brew "git-flow"
brew "gnu-tar"
brew "gnupg2"
brew "go"
brew "gpatch"
brew "gpg-agent"
brew "graphicsmagick"
brew "grep"
brew "groff"
brew "gzip"
brew "heroku"
brew "httpie"
brew "imagemagick"
brew "jq"
brew "kops"
brew "less"
brew "libxml2"
brew "libxslt"
brew "lsof"
brew "lua"
brew "luajit"
brew "mad"
brew "make"
brew "mas"
brew "maven"
brew "md5sha1sum"
brew "ncurses"
brew "nvm"
brew "openssl"
brew "pv"
brew "pyenv-virtualenv"
brew "pyenv"
brew "python3"
brew "rsync"
brew "screen"
brew "shellcheck"
brew "ssh-copy-id"
brew "tcpdump"
brew "tfenv"
brew "thrift"
brew "tmux"
brew "tree"
brew "unrar"
brew "unzip"
brew "vim", args: ["with-client-server", "with-luajit", "override-system-vi"]
brew "wget", args: ["with-gpgme"]
brew "whois"
brew "zlib"
brew "zsh"
brew "zsh-completions"

# Install more recent versions of some macOS tools
brew 'homebrew/dupes/grep'

# Desktop apps to install via Cask
cask "audim"
cask "atom"
cask "firefox"
cask "google-chrome"
cask "google-cloud-sdk"
cask "google-drive"
cask "handbrake"
cask "insomnia"
cask "intellij-idea"
cask "istat-menus"
cask "iterm2"
cask "osxfuse"
cask "slack"
cask "spotify"
cask "the-unarchiver"
cask "transmission"
cask "vagrant"
cask "vagrant-manager"
cask "virtualbox"
cask 'virtualbox-extension-pack'
cask "vlc"
cask "xquartz"

# Quicklook
cask 'qlcolorcode'
cask 'qlmarkdown'
cask 'quicklook-json'
cask 'quicklook-csv'
cask 'qlstephen'

# Fonts
cask 'font-sauce-code-powerline'
cask 'font-source-code-pro'
cask 'font-source-sans-pro'
cask 'font-source-serif-pro'

# Appstore apps
mas 'Numbers', id: 409203825
mas 'Pages', id: 409201541
mas 'Sketch', id: 402476602

# Clean
cleanup