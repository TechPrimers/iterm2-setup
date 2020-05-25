# iTerm2 Setup details
The following are the iTerm2 setup details which I followed for my OSX

## Table of Contents
- [Installation](#installation)
- [Customization](#customization)
- [More customizations](#more-customizations)
- [Windows users](#windows-users)

## Installation
Installation steps for [iterm2](https://www.iterm2.com/) and [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) can be followed from this medium article by Adesh Gautam

<b>Source:</b> [Powerup your terminal using Oh My Zsh and iTerm2](https://medium.com/swlh/power-up-your-terminal-using-oh-my-zsh-iterm2-c5a03f73a9fb)

## Customization
Remove `username@machine_name` from the prompt by adding the below command in `~/.zshrc` file
```
export DEFAULT_USER=`whoami`
```
<b>Source:</b> [Gist .zshrc file](https://gist.github.com/logicmd/4015090)

## More customizations
If you thing, the above customizations are not enough, try this one which has steps for VSCode integrations too

<b>Source:</b> [Configuration of a beautiful efficient terminal and prompt on OSX in 7 minutes](https://medium.com/@Clovis_app/configuration-of-a-beautiful-efficient-terminal-and-prompt-on-osx-in-7-minutes-827c29391961)

### PowerLevel10k theme
- Used [Powerlevel10k](https://github.com/romkatv/powerlevel10k#powerlevel10k) Theme

## Windows users
You are not left alone, follow the below article to get these features on Windows 

<b>Source:</b> [How to install zsh and oh my zsh on Windows 10](https://evdokimovm.github.io/windows/zsh/shell/syntax/highlighting/ohmyzsh/hyper/terminal/2017/02/24/how-to-install-zsh-and-oh-my-zsh-on-windows-10.html)
