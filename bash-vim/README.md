# Setting up Bash and VIM
Copy the .profile, .zshrc, .vimrc and .bash_profile files to your user root


```
brew cask install iterm2
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

git clone https://github.com/powerline/fonts.git
cd fonts
./install.sh
cd ..
rm -rf fonts
```

Likely you will also need to open you iTerm preferences [cmd+,], profiles > text, and update the font. I use Fira Mono.
