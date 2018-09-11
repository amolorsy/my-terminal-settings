# My Terminal Settings
### zsh
```
brew install zsh
chsh -s /usr/local/bin/zsh
```

### [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) 
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

### [hyper](https://hyper.is/)
```
# .hyper.js
modules.exports = {
  config: {
    ...
    fontSize: 14,
    ...
    shell: '/usr/local/bin/zsh'
  }
}
```

### [hyper-snazzy](https://github.com/sindresorhus/hyper-snazzy)
`$ hyper install hyper-snazzy`
```
# .hyper.js
modules.exports = {
  ...
  plugins: ["hyper-snazzy"]
}
```

### [pure](https://github.com/sindresorhus/pure)
`$ npm install --global pure-prompt`
```
# .zshrc
autoload -U promptinit; promptinit
prompt pure
```

### [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) 
`brew install zsh-syntax-highlighting`
```
# .zshrc
plugins=(
  ...
  zsh-syntax-highlighting
)
```
```
# .zshrc
source /usr/local/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
```

### [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
`brew install zsh-autosuggestions`
```
# .zshrc
plugins=(
  ...
  zsh-autosuggestions
)
```
```
# .zshrc
source /usr/local/share/zsh-autosuggestions/zsh-autosuggestions.zsh
```

### 참고
[awesome-hyper](https://github.com/bnb/awesome-hyper)
