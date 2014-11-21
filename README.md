# dotfiles-local

## Install

1. Clone [thoughtbot/dotfiles](https://github.com/thoughtbot/dotfiles):

`git clone git://github.com/thoughtbot/dotfiles.git ~/dotfiles-thoughtbot`

2. Clone [my local dotfiles](https://github.com/mxhold/dotfiles-local):

`git clone git@github.com:mxhold/dotfiles-local.git ~/dotfiles-local`

3. Install [rcm](https://github.com/thoughtbot/rcm):

`brew tap thoughtbot/formulae`
`brew install rcm`

4. Run `rcup` to symlink dotfiles from both directories:

`env RCRC=$HOME/dotfiles-local/rcrc rcup`
