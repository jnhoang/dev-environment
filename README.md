# dev-environment

## mac setup

### remove mouse acceleration
defaults write .GlobalPreferences com.apple.mouse.scaling -1

###  desktop apps
- [postgres](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads)
- [postico](https://eggerapps.at/postico/)
- [iterm2](https://iterm2.com/)
- [docker](https://docs.docker.com/get-docker/)
- [vscode](https://code.visualstudio.com/download)
- [settings](https://github.com/jnhustin/dev-environment) in this repo
- [github desktop](https://desktop.github.com/)
- [figma](https://www.figma.com/downloads/)
- [ohmyzsh](https://ohmyz.sh/)
  - [honukai theme](https://github.com/oskarkrawczyk/honukai-iterm-zsh)
  - in `~/.zshrc`, update theme: `ZSH_THEME="honukai"`
- [milanote](https://milanote.com/)
- [figma](https://www.figma.com/downloads/)


### fonts
- move fonts inside the included font folder into the `font book`

### homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

### node
`brew install node`

### python
#### pyenv
```
brew update; brew install pyenv
pyenv install -v 3.9.1
pyenv global 3.9.1

# in ~/.zshrc
alias python='python3'
```
- https://stackoverflow.com/questions/69511006/cant-install-pyenv-3-8-5-on-macos-big-sur-with-m1-chip

#### pip
- [source](https://www.geeksforgeeks.org/how-to-install-pip-in-macos/)
```
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python3 get-pip.py
pip3 version
```

## things to install
- [homebrew](https://docs.brew.sh/Homebrew-on-Linux)
- [iterm2](https://iterm2.com/downloads.html)
- [vscode](https://code.visualstudio.com/)
- pyenv:  `brew update; brew install pyenv`
- virtualenv: `pip install virtualenv`


## vscode extensions
- better align (wwm)
- backet pair colorizer 2 (coenraadS)
- docker
- dotENV (mikestead)
- sublime text keymap and setting importer (microsoft)


# Chrome Extensions
- [adblock](https://chrome.google.com/webstore/detail/adblock-plus-free-ad-bloc/cfhdojbkjhnklbpkdaibdccddilifddb/related)
- [eye dropper](https://chrome.google.com/webstore/detail/eye-dropper/hmdcmlfkchdmnmnmheododdhjedfccka)
- [json viewer](https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh)
- [mod header](https://chrome.google.com/webstore/detail/modheader/idgpnmonknjnojddfkpgkljpfnnfcklj)
- [reddit enhancement](https://chrome.google.com/webstore/detail/reddit-enhancement-suite/kbmfpngjjgdllneeigpgjifpgocmfgmb)
- [redux devtools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd)
- [youtube nonstop](https://chrome.google.com/webstore/detail/youtube-nonstop/nlkaejimjacpillmajjnopmpbkbnocid?authuser=0)

# wallpapers
- [google photos](https://photos.app.goo.gl/TpXYHiNFwwGsgnZ97)
