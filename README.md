# AstroNvim User Configuration

A user configuration for [Neovim](https://github.com/neovim/neovim), with the
help of [AstroNvim](https://github.com/AstroNvim/AstroNvim).

## 🛠️ Installation

_For more detailed instructions, check
[AstroNvim's website](https://astronvim.com/)_

#### Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
```

#### Clone AstroNvim

```shell
git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
```

#### Create a new user repository from their template

Go to their [configuration template](https://github.com/AstroNvim/user_example)
and press the "Use this template" button above to create a new repository to
store your user configuration.

You can also just clone that repository directly if you do not want to track
your user configuration in GitHub.

#### Clone the repository

```shell
git clone https://github.com/<your_user>/<your_repository> ~/.config/nvim/lua/user
```

#### Start Neovim

```shell
nvim
```

#### Check health

While `nvim` is open, type the following command to check for missing
dependencies.

```shell
:checkhealth
```
