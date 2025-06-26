# Starship Config

Install starship via Homebrew:

```shell
brew install starship
```

Download config:

```shell
gh repo clone pyk/config-starship ~/.config/starship
```

Add the following lines to `~/.zshrc`:

```shell
export STARSHIP_CONFIG=~/.config/starship/config.toml
eval "$(starship init zsh)"
```
