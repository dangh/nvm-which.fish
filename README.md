# nvm-which.fish
Locate node version installed by [nvm.fish](https://github.com/jorgebucaran/nvm.fish)

## Installation

```fish
fisher install jorgebucaran/nvm.fish
fisher install dangh/nvm-which.fish
```

## Usage

```fish
$ nvm-which 16
# not found

$ nvm-which 16 -i
# installing node v16
/Users/t/.local/share/nvm/v16.20.2
```
