# Workspace-settings

Items and settings to make setting up a new computer easier.

## Great place to start
Download homebrew:
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew tap caskroom/cask
```

## Tools I download:
- [Visual Studio Code](https://code.visualstudio.com/)
- [Hyper](https://hyper.is/)
- [Chrome](https://www.google.com/chrome/browser/desktop/index.html) / [Chrome Canary](https://www.google.com/chrome/browser/canary.html)
  - [ColorZilla](http://www.colorzilla.com/)
  - [GraphiQL](https://chrome.google.com/webstore/detail/chromeiql/fkkiamalmpiidkljmicmjfbieiclmeij?hl=en)
  - React DevTools
  - Angular DevTools (Augury)
  - var_masterpiece
- [Firefox](https://www.mozilla.org/en-US/firefox/developer/)
- [SourceTree](https://www.sourcetreeapp.com/)
- [Slack](https://slack.com/downloads/osx)
- [VLC](https://www.videolan.org/vlc/index.html)
- [Spotify](https://www.spotify.com/us/download/other/)
- [Ag](https://github.com/ggreer/the_silver_searcher)
- [Node](https://nodejs.org/en/)
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [iterm2](https://www.iterm2.com/)

Great tool to help install apps  a good number of these apps quickly: [http://macapps.link/en](http://macapps.link/en)

This should install Firefox, Chrome, Canary, Sourcetree, VSCode, iTerm, Spotify, Slack
`curl -s 'http://macapps.link/en/firefoxdev-chrome-chromecanary-sourcetree-vscode-iterm-spotify-slack' | sh`

## Easy installing with brew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew tap caskroom/cask
brew install node
brew install the_silver_searcher
brew cask install google-chrome
brew cask install visual-studio-code
brew cask install iterm2
brew cask install slack
brew cask install sourcetree
brew cask install spotify
```
