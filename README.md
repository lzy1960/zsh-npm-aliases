# zsh-npm-aliases

Aliases for npm, yarn and pnpm in zsh

## Installation

1. Clone this repository into $ZSH_CUSTOM/plugins (by default ~/.oh-my-zsh/custom/plugins)

```bash
git clone https://github.com/lzy1960/zsh-npm-aliases ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/npm-aliases
```

2. Add the plugin to the list of plugins for Oh My Zsh to load (inside ~/.zshrc):

```vim
plugins=([...plugins] npm-aliases)
```

3. Start a new terminal session.

## License

This project is licensed under [MIT license](https://opensource.org/licenses/MIT). For the full text of the license, see the [LICENSE](https://github.com/lzy1960/zsh-npm-aliases/blob/main/LICENSE) file.

## Update

```bash
git -C ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/npm-aliases pull
```
